---
title: Manage the table view
description: You can display records and their fields in a table view, when accessing the record type page in Adobe Workfront Planning.
hidefromtoc: yes
hide: yes
recommendations: noDisplay, noCatalog
exl-id: 0dd723b5-d674-4626-8fc2-7da41f3b7f35
---
# Manage the table view

<!--
title: Manage the table view
description: You can display records in a table view when using Adobe Maestro. 
hidefromtoc: yes
author: Alina
feature: Work Management
role: User
hide: yes
-->

<!--update the metadata with real information when making this available in TOC and in the left nav-->

{{planning-important-intro}}

You can display records and their fields in a table view, when accessing the record type page in Adobe Workfront Planning. 

For information about record views and how to manage them, see [Manage record views](../views/manage-record-views.md).

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
<td>
   <p> Product</p> </td>
   <td>
   <p> Adobe Workfront</p> </td>
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
   <p>System administrators have access only the views they created or that are shared with them. </p>
  </td>
  </tr>
  
  <tr>
   <td role="rowheader">Access level configuration</td>
   <td> <p>There are no access level controls for Adobe Workfornt planning</p>  
</td>
  </tr>

  <tr>
   <td role="rowheader"><p>Permissions</p></td>
   <td> <p>Manage permissions to the view</p>  
</td>
  </tr>

<tr>
   <td role="rowheader">Layout template</td>
   <td> <p>Your system administrator must add the Maestro area in your layout template. For information, see <a href="../access/access-overview.md">Access overview</a>. </p>  
</td>
  </tr>
 </tbody>
</table>

## Manage a table view {#manage-a-table-view}

<!--insert screen shot of table view-->

When creating a table view, all records of the selected type display in a table. Each row is a unique record and each column is a record field. All fields and all records display by default. 

To manage a table view: 

1. Create a table view, as described in the article [Manage record views](../views/manage-record-views.md). 

    ![](assets/table-view-example.png)

1. (Optional) Click **Row height**, then select from the following options to modify the height of the table rows: 
    * Short
    * Medium
    * Tall 

1. Update the following view elements as described in the subsections below:
    * [Columns (or fields)](#add-columns-or-fields)
    * [Rows (or records)](#add-rows-or-records)
    * [Filters](#add-filters) 
    * [Grouping](#add-groupings)
    * [Sort](#add-a-sort) 


### Add columns (or fields) {#add-columns}

The column headers of a table view display fields associated with the records in the view. The same fields displayed in the table view also display in the Details section of a record. For more information, see [Edit records](../records/edit-records.md). 

<!--this is not available yet:You can display record fields (or columns) in both a table and a timeline view. However, the number of columns displayed in the table of the timeline view is limited and you cannot add columns in addition to those selected by default.-->

Adding columns to a view is identical to adding fields to a record type.  

You can add up to 500 fields (or columns) in a table view. 

1. Go to a record type page and select a **Table** view from the view drop-down menu.

    <!-- replace above with this when view redesign: Go to a record type page and click a table view tab, or click **+ View **to add a new view, then choose **Table**. -->
1. Start adding fields (or columns), as described in the article [Create fields](../fields/create-fields.md). 

    The columns you add are visible to all users who access the record type and are added as new fields on the record's page.
   
1. Do one of the following to reorder columns in the table:

    * Grab the column header and drag and drop it in the desired position. The column you moved briefly displays with a blue background until you make other adjustments to the table. 

    * Click **Fields** in the table's toolbar, then drag and drop the fields in the desired order, then click outside the **Fields visibility and order** box to close it.

        ![](assets/fields-setting-table-view-toolbar-expanded.png)


        >[!TIP]
        >
        >* The Name field is always the first field in the table view, by default. This is considered a primary field. 
        >
        >* You cannot move the Name field to another position, unless you designate another field as the primary field. For more information, continue with Step 4. <!--accurate?-->
        >
        >* You cannot hide or delete a primary field. 
        >
        >* The primary field is frozen and is not part of the horizontal scroll.
 
    * Replace the field in the first column with another field by changing the primary field. For more information, continue to step 4. <!--accurate?-->

1. (Optional) Hover over a field name in the column header of any field that does not display in the first column of the table, click the downward-pointing arrow to the right of the field name, then click **Set as primary field**. 
    
    ![](assets/set-as-primary-field-option-table-view.png)

1. Click **Set field** to confirm. 

    The field becomes a primary field which means it displays as the first column of the table view. The previous primary field moves to the second column.

    >[!NOTE]
    >
    >   * Only fields of the following types can be primary fields: 
    >
    >       * Single-line text
    >       * Number
    >       * Formula
    >
    >   * The primary field is always frozen and cannot be moved. You can select another field to replace a primary field, if you need to move it to another position. 
    >
    >   * Changing the primary field in your table view affects the view for all other users who choose it.
    >
    >   * Changing the primary field in a table view affects all your table views. 
    >
    >   * You cannot delete or hide a primary field. 
    >
    >   * The value listed in the primary field is always hyperlinked to the record's page.

1. Click and drag the column separation lines and drop them in the desired spot to increase the width of the columns. 

    >[!TIP]
    >
    >The changes you make to the column width and order are permanent and visible to all users who access the record type. 

1. Hover over the column header, then click the downward-pointing arrow, then click **Hide field**

    Or

    Click **Fields** in the table toolbar and disable the toggle associated with the fields (or columns) you want to hide. The **Fields visibility and order** box displays.

    >[!TIP]
    >
    >The number of hidden fields displays to the left of the Fields icon in the toolbar.


1. Click the **Fields** icon and enable the toggle associated with the fields you want to display in the columns of the table. All fields display by default.

1. Do the following to quickly find records that match a keyword:

    1. Click the **Search** icon ![](assets/search-icon.png) and start typing a keyword associated with any field of a record that displays on the screen. The number of correct matches displays next to the search item and the field with the correct match is highlighted. 

        ![](assets/search-box-with-results-blue-outline-table-view.png)

        You can use any word or special character that is visible on the screen. 
    
        You cannot use keywords that are associated with fields that are hidden in the table view. 

    1. Press **Enter** on your keyboard to go to the next found field. 

    1. (Optional) If there is more than one match, click the up and down arrows to the right of the search keyword to find all the matches in the table. 

    1. Click the **x** icon in the search box to clear the search keyword. 
   

### Add rows (or records) {#add-rows}

The rows of a table view display individual records of the selected record type. 

You can have up to 50,000 records (or rows) for a record typeS. 

1. Go to a record type page and select a **Table** view from the view drop-down menu.

<!-- replace above with this when view redesign: Go to a record type page and click a table view tab, or click **+ View **to add a new view, then choose **Table**. -->
1. Start adding records (or rows), as described in the article [Create records](../records/create-records.md). 

    The records you add in the table view are saved immediately and are visible to all users who have View or higher permissions to the workspace. 

1. (Optional) Add a thumbnail to each record, and click **Fields** in the upper-right corner of the table, then select the toggle for the **Thumbnail** field to display it to the left of the primary field. It is deselected by default. 
    
    For information, see [Add a thumbnail to a record](/help/quicksilver/maestro/records/add-thumbnails-to-records.md).

1. (Optional) Select one or multiple records in a row, then drag and drop the **handle** icon ![](assets/handle-icon.png) to the left of the record name to reorder the rows. 

    >[!NOTE]
    >
    >You cannot reorder rows if you apply at least one sort to the table view. 

    <!-- this is not possible right now:

    1. To reorder the rows, click the row header, drag and drop it in the desired location. 

        The changes you make to the row order are permanent and visible to all users who access the record type
    -->

<!-- this section below links from the timeline view; consider splitting them if they become different-->

### Add filters {#add-filters}

Filters help you reduce the amount of information displayed on the screen.

Consider the following when working with filters in the table view: 
<!-- this list is almost identical to the one for the table view - update both-->

* The filters you create for the table view work independently from the filters in the timeline view when applied to the same record type. 

* The filters are unique to the view that you select. Two table views of the same record type can have different filters applied to them. Two users looking at the same table view see the same filter that is currently applied. 

* You cannot name the filters you build and apply to a table view.

* Removing filters removes them from anyone accessing the same record type as you and uses the same view as you use.

* Adding filters to the table view is identical to adding filters to the timeline view. 

* You can filter by connected record fields or lookup fields, but not for those fields that allow linking to multiple records.

To add a filter to a table view: 

1. Create a table view for a record type page, as described in the article [Manage record views](../views/manage-record-views.md). 
1. Select a table view, then click **Filters** in the upper-right corner of the table.    
1. Click **Add condition** and add the following information: 

    * Select a field that you want to filter by <!-- the tip below might change-->

    * Select an option (or a filter modifier) to define what kind of condition the field must meet

        The table below displays the available modifiers for each type of field.

        <table>
        <thead>
        <tr>
            <th><b>Field type</b></th>
            <th><b>Modifiers</b></th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <td>Single-line, Paragraph, Formula </td>
            <td><p>Contains</p>
            <p>Does not contain</p>
            <p>Is</p>
            <p>Is not</p>
            <p>Is empty</p>
            <p>Is not empty</p></td>
        </tr>
        <tr><td>Single-select</td>
            <td><p>Is</p>
            <p>Is not</p>
            <p>Is any of</p>
            <p>Is none of</p>
            <p>Is empty</p>
            <p>Is not empty</p></td>
        </tr>
        <tr>
            <td>Multi-select, People</td>
            <td><p>Has any of</p>
            <p>Has all of</p>
            <p>Is exactly</p>
            <p>Has none of</p>
            <p>Is empty</p>
            <p>Is not empty</p></td>
        </tr>
        <tr>
            <td>Number, Percentage, Currency</td>
            <td><p>=</p>
            <p>≠</p>
            <p> < </p>
            <p>></p>
            <p>≤</p>
            <p>≥</p>
            <p>Is empty</p>
            <p>Is not empty</p></td>
        </tr>
        <tr>
            <td>Date</td>
            <td><p>Is</p>
            <p>Is not</p>
            <p>Is after</p>
            <p>Is before</p>
            <p>Is between</p><p>Is not between</p>
            <p>Is empty</p><p>Is not empty</p></td>
        </tr>

        <tr>
            <td>Checkbox</td>
            <td><p>Is</p>
        </tr>
        </tbody>
        </table> 

    * Select a value for the field selected. 

     ![](assets/filter-ui-table-view.png)

    There is no limit to how many filtering conditions you can add.

1. (Optional) Click **Add condition** to add another filtering option and repeat the above steps. The number of filters applied displays to the left of the Filters icon. 
1. Click the following operators to indicate how the filter conditions are joined and should be applied:

    * **And**: All specified conditions must be met. 
    * **Or**: Any of the specified conditions must be met. This is the default option. 
    
    The list of records is filtered automatically.  <!--at this time, you can't name and save the filter - but will this change?!-->
    <!-- asked on the task for the simple filters whether there is a limitation for how many statements a filter can have?!-->
    
1. (Optional) Click **Filters**, then click the **x** icon to remove a filter. <!--right now you cannot "clear all" for filters, but this might come later-->

### Add groupings {#add-groupings}

<!--this section exists in the timeline view too, but the display is slightly different, so I kept both steps; consider updating both sections if any updates to groupings are introduced-->

You can group records by similar information when applying  a grouping to a view.

Adding groupings in the table view is similar to adding groupings to the timeline view. 

Consider the following:

* You can apply groupings both in the table and timeline views. The groupings of the table view are independent from those in the timeline view of the same record type.
* You can apply 3 levels of grouping in a view. The records are grouped in the order of groupings that you select. 
<!--* You can apply up to 4 levels of grouping when using the API. --checking on this one for now-->
* The groupings are unique to the view that you select. Two table views of the same record type can have different groupings applied to them. Two users looking at the same table view see the same grouping that is currently applied. 
* You cannot name the groupings you build for a table view.
* Removing groupings removes them from anyone accessing the same record type as you and who displays the same view as you do. 
* You can edit records listed under a grouping. 
* You can group by connected record fields or lookup fields, but not for those fields that allow linking to multiple records.
<!--checking into this: * You can apply up to 4 levels of grouping when using the API. -->
<!-- checking also into this: * You cannot group by a Paragraph-type field.-->

To add a grouping:

1. Create a timeline view for a record type, as described in the article [Manage record views](../views/manage-record-views.md). 
1. Click **Grouping** in the upper-right corner of the table view.

    ![](assets/grouping-ui-table-view-with-linked-fields.png)

1. Click one of the suggested fields, or click **Choose a different field**, search for a different field, then click it when it displays in the list.

    The grouping is applied automatically to the table and records display under the grouping separation line.
    
1. (Optional) Repeat the above steps to add up to 3 groupings. 

    The number of fields selected for the grouping displays next to the Grouping icon. 

    ![](assets/grouping-applied-in-table-view.png)

1. (Optional) Inside the **Group records by** box, click the **x** icon to the right of a field selected for the grouping to remove the grouping

    Or

    Click **Clear all** to remove all fields.  

1. Click outside the **Group records by** box to close it. 
1. (Optional) Click **+ New < Record type name >** at the end of any grouping to add new records, then refresh your page to add the new record to the appropriate grouping. <!--this might need to be changed when they add the Refresh button on the toolbar of the table view-->

### Add a sort {#sort-information} 

By applying a sort, you can organize information in a given order. 

You can sort the following information:

* All records in a table view. <!--or timeline view. ***********verify this is the case for the timeline view*********************-->
<!--* All groupings. - this is not available yet-->

Consider the following when sorting records in the table view: 

<!-- if this is available for the timeline view, update both when you update one-->

* Sorting is unique to the view that you select. Two table views of the same record type can have different sorting criteria applied to them. Two users looking at the same table view see the same sorting that is currently applied. 

* You cannot name the sortings you build and apply to a table view.

* The sorting you create is preserved when you navigate away.

* You can sort by as many fields as you see displayed in the table view of a record type.

* Linked fields are sortable only if they allow single values, or if they allow multi-select values with the summarization option selected (sum, average, max, min).

* Removing sorting criteria removes them from anyone accessing the same record type as you and uses the same view as you use.

* You can sort by connected record fields or lookup fields, but not for those fields that allow linking to multiple records.

To sort <!--ungrouped (add this when sorting for groupings will be available--> records, do the following:

1. Create a table view, as described in the article [Manage record views](../views/manage-record-views.md).
1. Click the **Sort** icon ![](assets/sort-icon.png) in the upper-right corner of the table
    
    Or

    Hover over the name of a column in the table view, click the downward-pointing arrow to the right of the column header name, then click **Sort by this field**. The field is added as a sorting selection in the Sort icon in the upper-right corner of the table view.

1. In the **Sort records by** box, click one of the suggested fields, or click **Choose a different field** and search for a different field, then click it when it displays in the list. 

    The sorting is applied automatically to the table view and records display sorted by your selected criteria. 

    <!-- add a step that you can rearrange the sorting fields here, when this will be possible-->
    
1. (Optional) Repeat the above steps to sort by additional fields.  

    The number of fields that you are sorting by displays to the left of the Sort icon in the upper-right corner of the toolbar. You can choose only fields that display in the columns of the table view.

1. (Optional) In the **Sort records by** box, click the **x** icon to the right of a sorting field to remove the sort

    Or

    Click **Clear all** to remove all fields from the sort. 

1. Click outside the **Sort records by** box to close it. 

    ![](assets/sorting-in-table-view.png)

    The information displayed in the table is sorted according to your selected criteria. 
    
    The fields selected for the sort display a sorting icon followed by a number that indicates the order in which the sorting is applied. 
    
<!-- this is not available yet: 

To sort grouped records: 

1. Create a view, as described in [Create or edit record views](#create-or-edit-record-views). 
1. ************************* add steps here for sorting grouped records****************

-->
