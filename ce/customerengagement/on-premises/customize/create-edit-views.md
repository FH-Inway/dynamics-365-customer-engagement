---
title: "Types of views in Dynamics 365 Customer Engagement (on-premises)"
description: "Views help you define how a list of records is displayed in the app. This page provides an overview of the types of views and how to create and customize them."
keywords: 

ms.custom: 
ms.topic: overview
applies_to: 
  - Dynamics 365 for Customer Engagement (online)
ms.assetid: 826fb059-a552-4db5-bf40-6a80cfa0fc0e
ms.author: matp
author: Mattp123
ms.reviewer: 
ms.suite: 
ms.tgt_pltfrm: 
caps.latest.revision: 25
topic-status: Drafting
search.audienceType: 
  - customizer

---

# Overview of types of views and how to create them

[!INCLUDE [applies-to-on-premises](../includes/applies-to-on-premises.md)] [Understand model-driven app views](/powerapps/maker/model-driven-apps/create-edit-views) 

With Dynamics 365 Customer Engagement (on-premises), use views to define how a list of records for a specific entity is displayed in the application. A view defines:  
-  The columns to display    
-  How wide each column should be    
-  How the list of records should be sorted by default  
-  What default filters should be applied to restrict which records will appear in the list  
  
A drop-down list of views is frequently displayed in the application so that people have options for different views of entity data.  
  
The records that are visible in individual views are displayed in a list, sometimes called a grid, which frequently provides options so that people can change the default sorting, column widths, and filters to more easily see the data that’s important to them. Views also define the data source for charts that are used in the application.

## Types of Views 
There are three types of views: *personal*, *system*, and *public*.

This topic is about how system administrators and system customizers work with system and public views. For more information about personal views, see [Create, edit, or save an Advanced Find search](../basics/save-advanced-find-search.md).  
  
### Personal views  
You and anyone else who has at least User level access to actions for the Saved View entity can also create personal views. As system administrator, you can modify the access level for each action in the security role to control the depth to which people can create, read, write, delete, assign, or share personal views.  
 
Personal views are owned by individuals and, because of their default User level access, they are visible only to that person or anyone else they choose to share their personal views with. You can create personal views by saving a query that you define by using Advanced Find or by using the **Save Filters as New Views** and **Save Filters to Current View** options in the list of views. These views are typically included at the bottom in lists of system or public views that are available in the application. While you can create a new personal view based on a system or public view, you cannot create a system or public view based on a personal view.  
  
### System views  
As a system administrator or system customizer, you can edit system views. System views are special views the application depends on, which  exist for system entities or are automatically created when you create custom entities. These views have specific purposes and some additional capabilities.    
  
|System Views|Description|  
|------------------|-----------------|  
|**Quick Find**|The default view used when searches are performed using **Quick Find**. This view also defines which fields are searched when using search capabilities of **Quick Find** and **Lookup** views.|
|**Advanced Find**|The default view used to display results when using **Advanced Find**. This view also defines the columns used by default when new custom public views or personal views are created without defining a view to use as a template.|  
|**Associated**|The default view that lists the related entities for a record.|  
|**Lookup**|The view you see when you select a record to set for a lookup field.|  

These views are not shown in the view selector and you can’t use them in sublists in a form or as a list in a dashboard. You cannot delete or deactivate these views. [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Remove views](../customize/remove-views.md)  
  
System views are owned by the organization so that everyone can see them. For example, everyone has organization-level access to read records for the View (savedquery) entity. These views are associated with specific entities and are visible within the solution explorer. You can include these views in solutions because they are associated with the entity.  
  
### Public views  
Public views are general purpose views that you can customize as you see fit. These views are available in the view selector and you can use them in sub-grids in a form or as a list in a dashboard. Some public views exist by default for system entities and for any custom entity. For example, when you create a new custom entity, it will have the following combination of public and system views.  
  
|Name|Type|  
|----------|----------|  
|**Active** *\<entity plural name>*|Public|  
|**Inactive** *\<entity plural name>*|Public|  
|**Quick Find Active** *\<entity plural name>*|Quick Find|  
|*\<entity name>* **Advanced Find View**|Advanced Find|  
|*\<entity name>* **Associated View**|Associated|  
|*\<entity name>* **Lookup View**|Lookup|  
  
You can create custom public views. You can delete any custom public views you create in an unmanaged solution. You cannot delete any system-defined public views. Custom public views added by importing a managed solution may have managed properties set that can prevent them from being deleted, except by uninstalling the managed solution. 

## Create or edit views
You can create or edit views in two ways:
- **Using the App Designer:** If you’re creating views for the first time, you may want to start with the App Designer, which provides a simple and intuitive UI with drag-and-drop capabilities. [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Create and edit public or system views by using the app designer](../customize/create-edit-views-app-designer.md). 
- **Using the Solution Explorer:** If you’re already experienced with [!INCLUDE[pn_dynamics_crm](../includes/pn-dynamics-crm.md)], you may want to use the Solution Explorer. [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Create or edit a view](../customize/create-and-edit-views.md).

## Customize views
As a system administrator and system customizer, you can customize the views through controls by making grids (lists) editable and compatible for Unified Interface. The following controls are used:
- **Editable Grid:** Allows users to do rich in-line editing directly from grids and sub-grids whether they’re using a web app, tablet, or phone. [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Make grids (lists) editable using the Editable Grid custom control](../customize/make-grids-lists-editable-custom-control.md)
- **Read Only Grid:** Provides users an optimal viewing and interaction experience for any screen size or orientation such as mobiles and tablets by using responsive design principles. [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Specify properties for Unified Interface apps](../customize/specify-properties-for-unified-interface-apps.md)

### See also  
[Get started with customization](../customize/getting-started-customization.md)     
[Create and design forms](../customize/create-design-forms.md)   


[!INCLUDE[footer-include](../../../includes/footer-banner.md)]
