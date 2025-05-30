---
title: "Import accounts, leads, and more into Dynamics 365 Customer Engagement (on-premises)"
description: "Follow these steps to import data into Dynamics 365 Customer Engagement (on-premises). Data can be accounts, leads, opportunities, activities, and more."
ms.custom:
ms.reviewer: 

ms.suite: 
ms.tgt_pltfrm: 
ms.topic: how-to
applies_to: 
  - Dynamics 365 Customer Engagement (on-premises)
ms.assetid: dee40fe5-1942-4521-986f-714edfd36433
caps.latest.revision: 37
author: shwetamurkute
ms.author: smurkute
search.audienceType: 
  - enduser

searchScope:
  - D365-App-*
  - D365-Entity-account
  - D365-UI-*
  - Customer Engagement
---
# Import accounts, leads, or other data

::: moniker range=">= op-9-1"

[!INCLUDE [applies-to-unified-interface](../includes/applies-to-unified-interface.md)] [Import data](/powerapps/user/import-data)

Whether your data is stored in spreadsheets, databases, or other systems, you'll probably want to import the data into Dynamics 365 Customer Engagement (on-premises) so you can keep track of all your customer information in one place.  
  
 You can import any type of information, such as accounts, leads, or opportunities – even activities or cases. (The different types of information are called "record types.") Contacts typically come from an email program. You can read about this here: [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Import contacts](../basics/import-contacts.md)  
  
## Step 1: Get your import file ready  
 First, you'll need to get your data into a file.  
  
 Make sure your data is as complete and accurate as possible when you create the import file. Fill in any missing info, and verify that names and other information are spelled correctly.  
  
 These file formats are supported:  
  
- Comma-separated values (.csv)  
  
- Text (.txt)  
  
- Compressed (.zip)  
  
- Excel Spreadsheet 2003 (.xml)  
  
- Excel Workbook (.xlsx)  
  
  The maximum file size allowed for .zip files is 32 MB. For the other file formats, the maximum file size allowed is 8 MB.  
  
  > [!TIP]
  > 
  > If you need to import a larger amount of data, check out the developer documentation, [Import data](../developer/import-data.md) for additional details.  
  > 
  >  You can add multiple import files to a single .zip file, and then import the .zip file to bring in all the files at once. For example, if several salespeople enter leads from a tradeshow into different spreadsheets, you can gather them into one .zip file for import.  
  > 
  > 
  >  Your import will fail if you're using a template that you exported from Dynamics 365 Customer Engagement (on-premises) and then added a new column and are now importing the data back into Customer Engagement (on-premises).  
      
## Step 2: Run the Import Data wizard  
 You'll use the **Import Data** wizard to import the file.  
  
1. Go to **Settings** > **Data Management** > **Imports**.
  
2. On the command bar select **Import Data** > **Import Data**.
  
3. Browse to the folder where you saved the file that contains the import file. Select the file, and then select **Open**. Then, select **Next**.  
  
   > [!TIP]
   >  You can import only one file at a time. To bring in more files, run the wizard again later, or add all your import files to a single .zip file.  
  
4. Review the file name, and if the file is in .xlsx, .xml, .csv, .txt or .zip format, verify that the field and data delimiters are correct. In most cases, you can accept the default delimiters, follow this step if you wish to check them:  
  
   1.  Click **Delimiter Settings**, and then select the characters used to separate the contents of fields and pieces of data. (These characters are called "delimiters.")  
      
       The default delimiter for fields is a comma (,).The other supported delimiters for fields are colon (:), semicolon (;), and tab character (/t). 
  
       **Example of field delimiter:**  

          Company Name,Address,City,State  
        
       The default delimiter for data is double quotation marks (").The other supported delimiters for data are single quotation mark ('), and **None**.  
    
       **Examples of data delimiter:**  
        
          Company Name,Address  
        
          "Fabrikam, Inc.","150 A Street"  
        
       > [!NOTE]
       >  Because an XML file does not use delimiters, if you upload a file that is in XML Spreadsheet 2003 format, or a .zip file that contains XML Spreadsheet 2003 files, the delimiter information won't be available.  
          
5. Select **Next**. 
 
6. Select how the wizard determines which fields to use for the data. More information: [Select a data map](select-data-map.md). 
  
   - Select **Default (Automatic Mapping)** if you want the wizard to determine the corresponding fields in Dynamics 365 Customer Engagement (on-premises) automatically. If the wizard can't find a field, you'll have the opportunity to "map" it yourself.   
     -- OR --  
  
   - Select **For Generic Contact and Account Data** if your import file contains contacts and accounts (and contacts are the main type of data).   
     -- OR --  
  
   - If available for your organization, select a custom data map. (You'll see them in the list if they're available to you.)  
  
7. Select **Next**.  
  
8. If prompted, in the Dynamics 365 Customer Engagement (on-premises) **Record Types** drop-down list, select the type of records you are importing, for example **Account** or **Lead**. Then, select **Next**.  
  
9. Confirm that the Import Data wizard has mapped all the pieces of info (called "fields") in the import file to the correct fields in Dynamics 365 Customer Engagement (on-premises). You may need to scroll down to see all the fields in the import file. For any record type with an alert icon, map the field from your import file to a corresponding field in Dynamics 365 Customer Engagement (on-premises).
      
   For example, an import file containing contacts may have a field for First Name, Last Name, and Job Title. Make sure those fields are mapped correctly to the corresponding fields in Dynamics 365 Customer Engagement (on-premises).  
      
   For any field in the import file that is marked **Not Mapped**, go to the **Dynamics 365 Customer Engagement (on-premises) Field Types** drop-down list and select the field name to use in Dynamics 365 Customer Engagement (on-premises). You may need to scroll down to see all available fields.  
    
10. After reviewing the field mapping, select **Next**.  
  
11. Review the summary, and then select **Next**.  
  
12. Select additional import settings. More information: [Review settings and import data](review-settings-import-data.md).  
  
    -   If it's okay for the Import Data wizard to import duplicate records, in the **Allow Duplicates** section, select **Yes**.  
  
        > [!CAUTION]
        >  In most cases, to avoid importing duplicate information, you should keep this option set to **No**.  
  
    -   To set who owns the imported records, in the **Select Owner for the Imported Records** section, select the **Lookup** button ![Lookup button.](../basics/media/lookup-button.gif "Lookup button"). Select **Look Up More Records**, type the person's name, and then select **Add**.  
  
        > [!NOTE]
        >  How do you decide who should "own" the imported data? Usually, the owner is the person responsible for taking action on the data. Here's an example: If your import file contains contacts you collected at a trade show and you want to assign a user to follow up with these contacts, select that person for the owner. To assign someone other than yourself as the owner of the imported records, your security role must include permissions to create records for the user. If you don't have sufficient permissions, the wizard assigns you as the owner of the imported records by default.  
  
    -   To save these import settings so you can use them again, enter a name for the settings (called a "data map").  
  
         The next time you run the Import Data wizard, you'll see the new data map listed under **Custom Maps**.  
  
13. Select **Submit**.  
  
14. To verify that the wizard was successful, select **Imports**, and then review the report. Otherwise, select **Finish**.  

15. If needed, learn about removing duplicates: [Merge duplicate records for accounts, contacts, or leads](merge-duplicate-records-accounts-contacts-leads.md)
  



[!INCLUDE[footer-include](../../../includes/footer-banner.md)]


::: moniker-end

::: moniker range="< op-9-1"


[!INCLUDE [applies-to-on-premises](../includes/applies-to-on-premises.md)] [Import data](/powerapps/user/import-data)

Whether your data is stored in spreadsheets, databases, or other systems, you'll probably want to import the data into Dynamics 365 Customer Engagement (on-premises) so you can keep track of all your customer information in one place.  
  
 You can import any type of information, such as accounts, leads, or opportunities – even activities or cases. (The different types of information are called "record types.") Contacts typically come from an email program. You can read about this here: [!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Import contacts](../basics/import-contacts.md)  
  
## Step 1: Get your import file ready  
 First, you'll need to get your data into a file.  
  
 Make sure your data is as complete and accurate as possible when you create the import file. Fill in any missing info, and verify that names and other information are spelled correctly.  
  
 These file formats are supported:  
  
- Comma-separated values (.csv)  
  
- Text (.txt)  
  
- Compressed (.zip)  
  
- Excel Spreadsheet 2003 (.xml)  
  
- Excel Workbook (.xlsx)  
  
  The maximum file size allowed for .zip files is 32 MB. For the other file formats, the maximum file size allowed is 8 MB.  
  
  > [!TIP]
  > 
  > If you need to import a larger amount of data, check out the developer documentation, [Import data](../developer/import-data.md) for additional details.  
  > 
  >  You can add multiple import files to a single .zip file, and then import the .zip file to bring in all the files at once. For example, if several salespeople enter leads from a tradeshow into different spreadsheets, you can gather them into one .zip file for import.  
  > 
  > 
  >  Your import will fail if you're using a template that you exported from Dynamics 365 Customer Engagement (on-premises) and then added a new column and are now importing the data back into Customer Engagement (on-premises).  
      
## Step 2: Run the Import Data wizard  
 You'll use the **Import Data** wizard to import the file.  
  
1. Go to **Settings** > **Data Management** > **Imports**.
  
2. On the command bar select **Import Data** > **Import Data**.
  
3. Browse to the folder where you saved the file that contains the import file. Select the file, and then select **Open**. Then, select **Next**.  
  
   > [!TIP]
   >  You can import only one file at a time. To bring in more files, run the wizard again later, or add all your import files to a single .zip file.  
  
4. Review the file name, and if the file is in .xlsx, .xml, .csv, .txt or .zip format, verify that the field and data delimiters are correct. In most cases, you can accept the default delimiters, follow this step if you wish to check them:  
  
   1.  Click **Delimiter Settings**, and then select the characters used to separate the contents of fields and pieces of data. (These characters are called "delimiters.")  
      
       The default delimiter for fields is a comma (,).The other supported delimiters for fields are colon (:), semicolon (;), and tab character (/t). 
  
       **Example of field delimiter:**  

          Company Name,Address,City,State  
        
       The default delimiter for data is double quotation marks (").The other supported delimiters for data are single quotation mark ('), and **None**.  
    
       **Examples of data delimiter:**  
        
          Company Name,Address  
        
          "Fabrikam, Inc.","150 A Street"  
        
       > [!NOTE]
       >  Because an XML file does not use delimiters, if you upload a file that is in XML Spreadsheet 2003 format, or a .zip file that contains XML Spreadsheet 2003 files, the delimiter information won't be available.  
          
5. Select **Next**. 
 
6. Select how the wizard determines which fields to use for the data. More information: [Select a data map](select-data-map.md). 
  
   - Select **Default (Automatic Mapping)** if you want the wizard to determine the corresponding fields in Dynamics 365 Customer Engagement (on-premises) automatically. If the wizard can't find a field, you'll have the opportunity to "map" it yourself.   
     -- OR --  
  
   - Select **For Generic Contact and Account Data** if your import file contains contacts and accounts (and contacts are the main type of data).   
     -- OR --  
  
   - If available for your organization, select a custom data map. (You'll see them in the list if they're available to you.)  
  
7. Select **Next**.  
  
8. If prompted, in the Dynamics 365 Customer Engagement (on-premises) **Record Types** drop-down list, select the type of records you are importing, for example **Account** or **Lead**. Then, select **Next**.  
  
9. Confirm that the Import Data wizard has mapped all the pieces of info (called "fields") in the import file to the correct fields in Dynamics 365 Customer Engagement (on-premises). You may need to scroll down to see all the fields in the import file. For any record type with an alert icon, map the field from your import file to a corresponding field in Dynamics 365 Customer Engagement (on-premises).
      
   For example, an import file containing contacts may have a field for First Name, Last Name, and Job Title. Make sure those fields are mapped correctly to the corresponding fields in Dynamics 365 Customer Engagement (on-premises).  
      
   For any field in the import file that is marked **Not Mapped**, go to the **Dynamics 365 Customer Engagement (on-premises) Field Types** drop-down list and select the field name to use in Dynamics 365 Customer Engagement (on-premises). You may need to scroll down to see all available fields.  
    
10. After reviewing the field mapping, select **Next**.  
  
11. Review the summary, and then select **Next**.  
  
12. Select additional import settings. More information: [Review settings and import data](review-settings-import-data.md).  
  
    -   If it's okay for the Import Data wizard to import duplicate records, in the **Allow Duplicates** section, select **Yes**.  
  
        > [!CAUTION]
        >  In most cases, to avoid importing duplicate information, you should keep this option set to **No**.  
  
    -   To set who owns the imported records, in the **Select Owner for the Imported Records** section, select the **Lookup** button ![Lookup button.](../basics/media/lookup-button.gif "Lookup button"). Select **Look Up More Records**, type the person's name, and then select **Add**.  
  
        > [!NOTE]
        >  How do you decide who should "own" the imported data? Usually, the owner is the person responsible for taking action on the data. Here's an example: If your import file contains contacts you collected at a trade show and you want to assign a user to follow up with these contacts, select that person for the owner. To assign someone other than yourself as the owner of the imported records, your security role must include permissions to create records for the user. If you don't have sufficient permissions, the wizard assigns you as the owner of the imported records by default.  
  
    -   To save these import settings so you can use them again, enter a name for the settings (called a "data map").  
  
         The next time you run the Import Data wizard, you'll see the new data map listed under **Custom Maps**.  
  
13. Select **Submit**.  
  
14. To verify that the wizard was successful, select **Imports**, and then review the report. Otherwise, select **Finish**.  

15. If needed, learn about removing duplicates: [Merge duplicate records for accounts, contacts, or leads](merge-duplicate-records-accounts-contacts-leads.md)
  



[!INCLUDE[footer-include](../../../includes/footer-banner.md)]

::: moniker-end
