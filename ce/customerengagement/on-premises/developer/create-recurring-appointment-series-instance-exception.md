---
title: "Create a recurring appointment series, instance, or exception (Developer Guide for Dynamics 365 Customer Engagement) | MicrosoftDocs"
description: "programmatically create a recurring appointment master (series),  individual recurring appointment instances, exceptions to those instances, or convert an appointment to a recurring appointment."
ms.custom: 
ms.reviewer: pehecke

ms.suite: 
ms.tgt_pltfrm: 
ms.topic: how-to
applies_to: 
  - Dynamics 365 Customer Engagement (on-premises)
helpviewer_keywords: 
  - schedule and appointment entities, converting appointments to recurring appointments
  - identifying recurring appointment instances
  - recurring appointment series; instance; or exception, schedule and appointment entities
  - recurring appointment instances stored as appointment records, schedule and appointment entities
  - appointments
  - recurring appointment instances, updating; deleting; or identifying
  - appointments, converting to recurring appointments
  - converting appointments to recurring appointments
  - deleting recurring appointment instances
  - updating recurring appointment instances
  - creating a recurring appointment series; instance; or exception
  - schedule and appointment entities, creating a recurring appointment series; instance; or exception
ms.assetid: bb2eadf8-058e-43c2-9fda-c56ac501bc1c
caps.latest.revision: 29
author: JimDaly
ms.author: jdaly
search.audienceType: 
  - developer

---
# Create a recurring appointment series, instance, or exception

When you create a recurring appointment master (series), [!INCLUDE[pn_microsoftcrm](../includes/pn-microsoftcrm.md)] creates individual appointment instances based on the specified recurrence information. You can also create individual recurring appointment instances and exceptions to those instances, and you can convert an appointment to a recurring appointment.  
  
<a name="bkmk_createseries"></a>   
## Create a recurring appointment series  
 To create a recurring appointment series (a `RecurringAppointmentMaster` record), you can use the <xref:Microsoft.Crm.Sdk.Messages.BookRequest> message, the <xref:Microsoft.Xrm.Sdk.Messages.CreateRequest> message, or the <xref:Microsoft.Xrm.Sdk.IOrganizationService>.<xref:Microsoft.Xrm.Sdk.IOrganizationService.Create*> method.  
  
 When you create a recurring appointment series, the following things occur:  
  
1. A `RecurringAppointmentMaster` record (recurring appointment series) is created that contains the basic and recurrence information about the recurring appointment series. Each record can be uniquely identified using the `RecurringAppointmentMaster.ActivityId` property. Further, this recurring appointment series is also created and stored as an activity (`ActivityPointer`) record. The activity record can be uniquely identified using the `ActivityPointer.ActivityId` property.  
  
2. Individual recurring appointment instances are created based on the recurrence information and stored as `Appointment` records. These appointment objects are associated with the parent recurring appointment series using the `Appointment.SeriesId` property and have the same value as the parent recurring appointment series ID (`ActivityPointer.SeriesId`).  
  
    The value of the `Appointment.InstanceTypeCode` property is set to **Recurring Instance** (picklist value 2) for these appointment objects.  
  
   > [!NOTE]
   >  Recurring appointment instances are created based on the expansion model and the parameters that define it. [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Recurring Appointment Partial Expansion Model](recurring-appointment-partial-expansion-model.md).  
  
   For sample code that demonstrates how to create a recurring appointment series, see [Sample: Create a Recurring Appointment](sample-create-retrieve-update-delete-recurring-appointment.md).  
  
<a name="bkmk_createinstance"></a>   
## Create a recurring appointment instance  
 To create a recurring appointment instance (a `RecurringAppointmentMaster` record), you can use the <xref:Microsoft.Crm.Sdk.Messages.CreateInstanceRequest>. This message takes two parameters: the number of instances to be created and the recurring appointment series for which the instances have to be created.  
  
 The instances are created after the last instance in the recurring appointment series. Also, the instances are only created up until the future instance cutoff date, regardless of the number of instances you have specified for creation.  
  
<a name="bkmk_createexception"></a>   
## Create a recurring appointment exception  
 An exception is created when you either update or delete an instance of the recurring appointment. Recurring appointment instances are stored as an appointment record along like other appointments, and you can identify a recurring appointment instance using the `Appointment.InstanceTypeCode` attribute of an appointment record, which will have a value of **Recurring Instance** (picklist value 2).  
  
 You can create exceptions in the following ways:  
  
-   Use the <xref:Microsoft.Xrm.Sdk.Messages.UpdateRequest> class on the `Appointment` entity to update a recurring appointment instance, and set the value of the `Appointment.InstanceTypeCode` attribute to **Recurring Exception** (picklist value 3).  
  
-   Use the <xref:Microsoft.Xrm.Sdk.Messages.DeleteRequest> class on the `Appointment` entity to delete a recurring appointment instance. Deleting an appointment instance marks it an exception by creating an entry for the instance in the `RecurringAppointmentMaster.DeletedExceptionsList` attribute for the parent appointment series object.  
  
-   Use the <xref:Microsoft.Crm.Sdk.Messages.CreateExceptionRequest> class on the `Appointment` entity.  
  
<a name="bkmk_convert"></a>   
## Convert an appointment to a recurring appointment  
 A recurring appointment is an appointment with recurrence information. You can convert an existing appointment in [!INCLUDE[pn_microsoftcrm](../includes/pn-microsoftcrm.md)] to a recurring appointment by using <xref:Microsoft.Crm.Sdk.Messages.AddRecurrenceRequest>. When you convert an existing appointment to a recurring appointment, the data from the existing appointment is copied to a new recurring appointment master instance and the existing appointment is deleted.  
  
### See also  
 [Recurring Appointment Entities](recurring-appointment-entities.md)   
 [Update a recurring appointment](update-recurring-appointment.md)   
 [Sample: Create a Recurring Appointment](sample-create-retrieve-update-delete-recurring-appointment.md)   
 [Sample: Convert an Appointment to a Recurring Appointment](sample-convert-appointment-recurring-appointment.md)


[!INCLUDE[footer-include](../../../includes/footer-banner.md)]
