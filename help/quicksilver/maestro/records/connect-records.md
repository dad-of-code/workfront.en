---
title: Connect records
description: After you create connections between record types, you can connect individual records to one another.
hidefromtoc: yes
hide: yes
recommendations: noDisplay, noCatalog
exl-id: 17796cdc-6de8-4209-a5af-b255dc64d70a
---
<!--when you make this live, update the metadata above to this: 
---
title: Connect records and objects
description: In addition to connecting Maestro records to one another, you can also connect Maestro records to objects from other applications.  
topic: Architecture
role: User
hidefromtoc: yes
hide: yes
---
-->
<!--update the metadata with real information when making this available in TOC and in the left nav-->

<!--if you change steps here, also update steps in the "Connect records" article-->

# Connect records 

{{planning-important-intro}}

You can connect Adobe Workfront Planning records to one another or to objects from other applications. 

You must first connect two record types to each other, or a record type to an object type from another application. This creates linked record fields. You can then connect records to one another or records to other objects from other applications using the linked record fields. 

Connecting records is similar to connecting records to objects from another application. 

For information about connecting record types to one another or to object types from other applications, see [Connect record types](../architecture/connect-record-types.md). 

For an example of connecting record types, see [Example of connecting record types and records](../architecture/example-connect-record-types-and-records.md).

You can connect the following: 

* Adobe Workfront Planning records
* Adobe Workfront Planning records with objects from other applications. 

  You can connect records to objects of the types listed below from the following applications:
  
  * Adobe Workfront

    * Projects
    * Portfolios
    * Programs
    * Company
    * Group

  * Adobe Experience Manager Assets

    * Image files
    * Folders

  <!--when you add more objects, fix the Access Requirements below which right now refer only to projects-->

## Access requirements

You must have the following access to perform the steps in this article: 

<table style="table-layout:auto">
 <col>
 </col>
 <col>
 </col>
 <tbody>
    <tr>
<tr>
<td>Product</p> </td>
   <td>
   <p> Adobe Workfront</p> 
   <p>To connect Adobe Workfront Planning records with Experience Manager Assets, you must have an Adobe Experience Manager Assets license and your organization's instance of Workfront must be onboarded to the Adobe Unified Experience. For information, see <a href="/help/quicksilver/workfront-basics/navigate-workfront/workfront-navigation/adobe-unified-experience.md">Adobe Unified Experience for Workfront</a>.</p>
   </td>
  </tr>  
 <td role="rowheader"><p>Adobe Workfront agreement</p></td>
   <td>
<p>Your organization must be enrolled in the early access stage for Workfront Planning </p>
   </td>
  </tr>
  <tr>
   <td role="rowheader"><p>Adobe Workfront plan</p></td>
   <td>
<p>Any</p>
   </td>
  </tr>
  <tr>
   <td role="rowheader"><p>Adobe Workfront license</p></td>
   <td>
   <p>Any</p> 
  </td>
  </tr>
  
  <tr>
   <td role="rowheader"><p>Access level configuration</p></td>
   <td> <p>There are no access level controls for Workfront Planning</p>  
</td>
  </tr>
<tr>
   <td role="rowheader"><p>Permissions</p></td>
   <td> <p>Manage permissions to a workspace to connect records </p>  
   <p>View or higher permissions to a workspace to view all connections to objects and fields from other applications, regardless of your access in other application. </p>
   <p>System Administrators have permissions to all workspaces, including the ones they did not create.</p>
</td>
  </tr>

<tr>
   <td role="rowheader"><p>Layout template</p></td>
   <td> <p>Your Workfront or group administrator must add the Planning area in your layout template. For information, see <a href="../access/access-overview.md">Access overview</a>. </p>  
</td>
  </tr>

 </tbody>
</table>

<!--Maybe enable this at GA - but Maestro is not supposed to have Access controls in the Workfront Access Level: 
>[!NOTE]
>
>If you don't have access, ask your Workfront administrator if they set additional restrictions in your access level. For information on how a Workfront administrator can change your access level, see [Create or modify custom access levels](../administration-and-setup/add-users/configure-and-grant-access/create-modify-access-levels.md). -->

## Considerations about connecting records

* After you connect record types, the connected record types display as linked record fields in the table of the record types they are linked from and on the records' pages. 
* You can browse and add records and objects of the linked record and object types from the linked record fields. 
* You can add fields of the linked record types to the table of the record type you are linking from. 
* You cannot manually update the values of linked fields on the records you are linking from. 

  The values of the linked fields of the linked records populate the Workfront Planning record that you are linking from automatically from the original record or object. 

* Everyone with access to Workfront Planning and View or higher permissions to the workspace can see the connections that you make between records or between records and other applications' objects. They can view connected records and objects regardless of their permissions in the  applications you are connecting to. 
* You can view and edit everyone else's connections, if you have Manage permissions to the workspace where the connected records are. 
* You can connect one record to one or multiple objects from another application.
* To link records with other records or objects, you must have the following:

  * At least one workspace, record type, and record. 

      For more information, see the following articles:

      * [Create workspaces](../architecture/create-workspaces.md)
      * [Create record types](../architecture/create-record-types.md)
      * [Create records](../records/create-records.md)

  * Connections between record types, or between record types and objects from other applications. For information, see [Connect record types](../architecture/connect-record-types.md)
* You can connect objects from Workfront to Workfront Planning records in the following areas:
  * From a Planning record in Workfront Planning. 
  * From the Planning section of a Workfront object. 
  
## Connect records from Workfront Planning

### Connect Adobe Workfront Planning records

{{step1-to-maestro}}

  The last-accessed workspace should open by default. 

1. (Optional) Expand the downward-pointing arrow to the right of an existing workspace name and select the workspace that you want to connect records from.
1. Click the card of a record type to open the record type page. 
1. Select a **Table** view from the **View** drop-down menu in the upper-right corner of the record type page. 
1. (Optional) Add records to the record type that you selected by adding a new row to the table. For information, see [Create records](../../maestro/records/create-records.md). 
1. (Conditional) After you connected the selected record type with another record type, go to  the linked record column and double-click the cell corresponding to the record that you want to link with other records.

    ![](assets/connect-other-records-smaller-box-in-table-view.png)

1. Do one of the following:

    * Click a connected record's name from the list to add it to the selected record. The record is added automatically.
    * Start typing the name of a record and click it when it displays in the list. The record is added automatically. 
    * Click **See all** to display all records. 

1. (Conditional) If you clicked **Select all** in the previous step, the **Connect objects** box displays. 

    ![](assets/connected-objects-table-for-records.png)

1. Start typing the name of a record in the search box, then select it when it displays in the list

    Or

    Select the name of one or multiple records in the box, then click **Connect objects** in the upper-right corner of the Connect objects box. 

    >[!TIP]
    >
    >    You can open a record's page, find the linked record field and click **Connect records** in the field to add records from the connected record or object type. 
    >
    >![](assets/connect-records-from-record-page-field.png)

    The following are added:

    * The linked records display in the linked record field of the record that you selected in step 6. <!--accurate?--> 
    * The linked fields are populated with the information from the linked records, if you added linked lookup fields when you connected the record types. 
    
    Updating the linked records updates the linked fields for the records that you are linking from automatically. You cannot manually edit linked fields. 
        
      >[!TIP]
      >
      >*  We use "linked fields" and "lookup fields" interchangeably. 
      >
      >* If you enabled the **Allow multiple records** setting when you connected the record types, the values of fields for the multiple selected objects are either displayed separated by commas or are aggregated according to the aggregator you chose.
    
1. (Optional) Close the record type page and go to the workspace you selected. 
1. Click the card for the record type that you linked to. 

    For example, if you connected the **Campaign** record with the Product record, click the **Product** card. 
  
    The record type card should open in the Table view. If not, select a table view. 
  
    Notice that the **Campaign** linked record field displays the names of the campaigns you linked to products in the Product record type page. Updating the Campaign information automatically updates the Campaign linked record field for the Product record type.

### Connect Adobe Workfront Planning records to Workfront objects

<!--when we will have more applications to link to from Maestro, change the title to something like: Connect Maestro records to objects from other applications-->

After you created a connection between a record type and a Workfront object type, you can connect individual records to objects in Workfront. The Workfront fields you connected are automatically populated on the records you are linking the objects from.

>[!NOTE]
>
>You cannot connect Workfront object types with Workfront Planning record types from Workfront.


{{step1-to-maestro}}

  The last-accessed workspace should open by default. 

1. (Optional) Expand the downward-pointing arrow to the right of an existing workspace name and select the workspace that you want to connect records from.
1. Click the card of a record type to open the record type page. 
1. Select a **Table** view from the **View** drop-down menu.

1. Click **New record**  to add individual records to the record type that you selected. For information, see [Create records](../../maestro/records/create-records.md). 
1. (Conditional) After you connected the selected record type with a Workfront object type, go to  the linked object column and double-click the cell corresponding to the record that you want to link with objects from Workfront.

    ![](assets/connect-projects-smaller-box-in-table-view.png)

1. Do one of the following:

    * Click an object from the list to add it to the selected record. Objects are listed alphabetically. The object is added automatically.
    * Start typing the name of an object and click it when it displays in the list. The object is added automatically. 
    * Click **See all** to display all objects you have at least permissions to view.

1. (Conditional) If you clicked **See all** in the previous step, the **Connect objects** box displays. 

    ![](assets/connect-objects-box-to-select-projects.png)

1. Start typing the name of a Workfront object in the search box, then select it when it displays in the list

    Or

    Select the name of one or multiple objects in the box, then click **Connect objects** in the upper-right corner of the Connect objects box. 

    >[!IMPORTANT]
    >
    >* You can only add Workfront objects you have access to view. 
    >
    >* Once you add Workfront objects, everyone with View or higher permissions to the workspace can view the Workfront objects and their field information, regardless of their permissions or access in Workfront.

    The following are added: 

    * The selected Workfront objects are added to the linked record field. 
    * If you added them when you connected the record type with Workfront, the linked fields (or the lookup fields) of the Workfront objects are automatically populated with information from Workfront. 

    >[!TIP]
    >
    >You can open a record's page, find the linked record field and click the **+** icon in the field to add objects from the connected object type.

    For more information about connecting record types with objects from another application, see [Connect record types](../architecture/connect-record-types.md).
     
1. (Optional) Click the name of a Workfront object connected to a Workfront Planning record either in the linked field of a table view or from the linked field in the record page.

    This opens the read-only Workfront Planning record page for the linked Workfront object. The fields you selected as lookup fields when you connected the record type with the Workfront object display in the Workfront Planning record page. 

   >[!TIP]
   >
   >* When you enable the Allow multiple records setting, the values of the lookup fields are either displayed separated by commas or are aggregated according to the aggregator you chose.
   >
   >* A linked record field is not created for the linked Workfront objects in Workfront.

1. (Optional) To open the linked Workfront object in Workfront, click **Go to source** in the upper-right corner of the Workfront object's record page. 

    ![](assets/workfront-project-maestro-details-page-with-go-to-source-link.png)

    This opens the Workfront object page, if you have at least View permissions to view the object. You can edit information about the Workfront object, if you have permissions to do so. 

1. (Optional) From the table view of the record type, hover over the column header of the linked Workfront object, and click the drop-down menu, then click **Edit lookup fields**.

1. Add Workfront object fields from the **Unselected fields** area

    Or

    Remove Workfront object fields fro the **Selected fields** area. 

    This adds or removes linked fields from the Workfront Planning records. The information associated with the removed fields remains in Workfront. 


### Connect Workfront Planning records to Adobe Experience Manager objects

<!--when we will have more applications to link to from Maestro, change the title to something like: Connect Maestro records to objects from other applications-->

>[!IMPORTANT]
>
>You must have an Adobe Experience Manager Assets license, and your organization's instance of Workfront must be onboarded to the Adobe Business Platform or the Adobe Admin Console to be able to connect Workfront Planning records to Adobe Experience Manager Assets.
>
>If you have questions about onboarding to the Adobe Admin Console, see the [Adobe Unified Experience FAQ](/help/quicksilver/workfront-basics/navigate-workfront/workfront-navigation/unified-experience-faq.md).

After you create a connection between a record type and Adobe Experience Manager Assets, you can connect individual records to Experience Manager assets. The asset fields you connected from Experience Manager Assets when you created the connection automatically populate on the record type you linked from.

{{step1-to-maestro}}

  The last-accessed workspace should open by default. 

1. (Optional) Expand the downward-pointing arrow to the right of an existing workspace name and select the workspace that you want to connect records from.
1. Click the card of a record type to open the record type page. 
1. Select a **Table** view from the **View** drop-down menu in the upper-right corner of the record type page.

1. (Optional) Click **New record** to add new records to the record type that you selected. For information, see [Create records](../../maestro/records/create-records.md). 
1. (Conditional) After you connected the selected record type with Experience Manager Assets, go to the linked object column and hover over the cell corresponding to the record that you want to link with other objects from Experience Manager, then click the **+** icon. 

    >[!TIP]
    >
    >  You can add click the **+** icon in the linked object field in the record page to connect assets to the record.

    The **Select Assets** box displays. <!--we might change this to Connect assets-->

    ![](assets/select-assets-box-for-aem-record-connections.png)

1. Click to select some of the following types of assets:

    * Images
    * Folders

    You can select multiple assets. 

    >[!IMPORTANT]
    >
    > You can connect only assets you have access to view in Experience Manager. Once connected, all Workfront Planning users can view the assets in Workfront Planning, regardless of their access in Experience Manager Assets. 

1. Click **Select**. <!-- we might change this to Connect-->

    The following are added: 

    * The selected Experience Manager assets are added to the linked record field. 
    * The linked fields (or lookup fields) populate with information from the Experience Manager connected assets. 
    
      Any existing information from the fields of the Experience Manager assets displays in the linked or lookup fields automatically. 

      >[!TIP]
      >
      >* If you enabled the Allow multiple records setting, the values of the multiple objects display either separated by commas or aggregated according to the aggregator you chose.
      >
      >* A linked record field to the Workfront Planning linked records is not created for the linked Experience Manager assets in the Experience Manager Assets application. 
     
1. (Optional) Go to the record type you linked to Experience Manager Assets from and click the name of an asset in the linked record field. The Experience Manager details of the asset display in a pop-up window. <!--update screen shot with hi-rez picture-->

    ![](assets/asset-pop-up-window-with-aem-details-and-thumbnail.png)

    The following fields display for an image file:

    * A thumbnail of the image
    * The image file name
    * Dimensions
    * Size
    * Description
    * The file path in Experience Manager
    * The asset type
    * Date created
    * Date modified 

1. (Optional) To open the Experience Manager assets record page in Experience Manager, go to the record type page of the record you are linking from, click the name of an asset in the linked record field to open the pop-up window, then click the **Open** icon ![](assets/open-asset-icon.png) to open the asset. 

   This opens the Experience Manager asset in Adobe Experience Manager Assets.  

1. (Optional) From the table view of the record type, hover over the column header of the linked Experience Manager asset, and click the drop-down menu, then click **Edit lookup fields**.

1. Add Experience Manager Assets object fields from the **Unselected fields** area

    Or

    Remove Workfront object fields fro the **Selected fields** area. 

    This adds or removes linked fields from the records. The information associated with the removed fields remains in Adobe Experience Assets.

## Connect records from Workfront objects

You must have the following to connect Workfront Planning records from Workfront objects: 

* Connections between record types and Workfornt object types.
* At least one connection between a record and a Workfront object. 
* Your Workfront or group administrator must add the Planning section to the Workfront object types that can connect to Planning record types. 

For more information, see [Manage records in the Planning section of Adobe Workfront objects](/help/quicksilver/maestro/records/manage-records-in-planning-section.md).
