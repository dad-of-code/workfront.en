---
title: License type overview when using Adobe Workfront Planning
description: Your access to Adobe Workfront Planning depends on your license type, in addition to your permissions to objects.
hidefromtoc: yes
hide: yes
recommendations: noDisplay, noCatalog
exl-id: 10dee6f9-06ff-435a-81a4-2125642fab59
---
<!--update the metadata with real things when making this public; also update the description with something like this: Not all users in the organization have the same access and permissions to use Adobe Workfront plannint. This article describes the levels of access that users could have to Adobe Workfront Planning. -->
<!--update the title and the metadata title if Workfront Planning is NOT its own product - because the title is too generic for it being a Workfront capability-->

# License type overview when using Adobe Workfront Planning

{{planning-important-intro}}

Your Adobe Workfront license type works in conjunction with your Adobe Workfront Planning permissions to give you access to view, contribute, or manage workspaces. <!--add more objects here when we can grant other object-specific permissions-->

Users with all license types can view, create, edit, or manage Workfront Planning views. 

This article describes the types of licenses needed in Workfront, and the permissions granted to workspaces in Workfront Planning based on each license type. 

A user with a lower-level license type has restricted permissions to workspaces when using Workfront Planning capabilities. 

>[!INFO]
>
>**EXAMPLE:** 
>
>Requestors (or Collaborators, according to the new license model) cannot contribute to or manage workspaces and their objects. 
>
>There is an indication in the sharing box that users cannot be granted permissions to contribute to or manage a workspace when they hold a lower-level license. 
>
>![](assets/permissions-grayed-out-for-requestor-user.png)


For information about permissions to objects in Workfront Planning, see [Overview of sharing permissions in Adobe Workfront Planning](/help/quicksilver/maestro/access/sharing-permissions-overview.md). 

## The relationship between Workfront license types and Workfront Planning permissions

The table below describes the relationship between the license type of a user in Adobe Workfront and the level of permissions you can grant to them to Adobe Workfront Planning objects based on that license. 

Granting a user permissions to a workspace also grants them permissions to record types, records, and fields. 


| Adobe Workfront license type*                                   | Permissions allowed in Adobe Workfront Planning                                                                                                                                             |
|------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|New: Standard <br> or <br>Current: Plan                    | Users can create and manage workspaces, record types, and records.<br> System administrators have Manage permissions to all workspaces, including the ones they did not create.                                                                                                                     |
| New: Light <br> or <br>Current: Work                      | Users can contribute and view a workspace shared with them, as well as the record types and records from that workspace. <br> Users can create, edit, delete records in the workspaces where they have Contribute permissions.            |
| New: Contributor <br> or <br>Current: Reviewer or Requestor | Users can view the workspaces shared with them, as well as the record types and records of those workspaces. <br> Users cannot create, edit, or delete record types or records. |

*For more information, see [Access requirements in Workfront documentation](/help/quicksilver/administration-and-setup/add-users/access-levels-and-object-permissions/access-level-requirements-in-documentation.md). 