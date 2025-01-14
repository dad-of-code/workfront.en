---
user-type: administrator
content-type: how-to-procedural
product-area: system-administration
navigation-topic: workfront-testing-environments
title: Create or edit an environment promotion package
description: The environment promotion capability is intended to provide the ability to move configuration-related objects from one environment to another. Learn how to create an environment promotion package that you can then install in a different environment.
author: Becky
feature: System Setup and Administration
role: Admin
hide: yes
hidefromtoc: yes
recommendations: noDisplay, noCatalog
exl-id: 0ac8c7df-2d38-4291-861e-52fb5e748537
---
# Create or edit an environment promotion package

## Create a package

1. Go to the environment that you want to create the package in. This is the environment that you are copying objects **from**.
1. Click the **[!UICONTROL Main Menu]** icon ![Main Menu](/help/_includes/assets/main-menu-icon.png) in the upper-right corner of Adobe Workfront, or (if available), click the **[!UICONTROL Main Menu]** icon ![Main Menu](/help/_includes/assets/main-menu-icon-left-nav.png) in the upper-left corner, then click **[!UICONTROL Setup]** ![Setup icon](/help/_includes/assets/gear-icon-setup.png).
1. Select **System** in the left navigation, then select **Environment Promotion**.
1. Click **Create Package**.

   The New Promotion Package page opens.

1. In the **Package name** field, enter a name for the package.
1. In the **Description** field, enter a description for this package. 
1. To add an object to the package, click **Add Objects** in the left navigation and select the type of object you want to add.
1. Select one or more objects from the list, or type the name in the search bar and select the object when it appears in the list. You can select more than one object in the list.
1. Click **Add (X Objects)** to add the selected objects to the package.

   >[!INFO]
   >
   >**Example**
   >
   >If you have selected three projects to add to the project, the button says **Add 3 Projects**. 

   The objects that you have added appears in the Package Contents area on the right of the page.

1. To add another type of object, repeat steps 7-9.
1. (Optional) To remove an object from the package, hover over the object in the Package Contents area, then click the X next to the object.
1. After you have added all of the desired objects to the package, click **Save and Close** to save the package without assembling it.

   Or

   Click **Save and Assemble** to save and assemble the package.

   >[!NOTE]
   >
   >* The Save and Close and Save and Assemble buttons are available if a package has both a name with five or more characters and at least one object added to it.
   >* You cannot assemble a package that is in an installable status such as Testing or Active.

## Edit or assemble an existing package

1. Go to the environment that you want to create the package in. This is the environment that you are copying objects **from**.
1. Click the **[!UICONTROL Main Menu]** icon ![Main Menu](/help/_includes/assets/main-menu-icon.png) in the upper-right corner of Adobe Workfront, or (if available), click the **[!UICONTROL Main Menu]** icon ![Main Menu](/help/_includes/assets/main-menu-icon-left-nav.png) in the upper-left corner, then click **[!UICONTROL Setup]** ![Setup icon](/help/_includes/assets/gear-icon-setup.png).
1. Select **System** in the left navigation, then select **Environment Promotion**.
1. Select the package from the displayed list.
1. (Conditional) To see disabled packages, enable the **Show retired packages** option.
1. (Optional) To view the contents, including all objects and their sub-objects, click the drop-down arrow next to the object type in the **Contents** section.
1. (Optional) To view previous installations and installation attempts of this package, click **Deployments**.
1. (Optional) To edit the package, click **Edit Package** at the upper-right of the screen.
1. To install the package, click **Install** at the upper-right of the screen.

   For instructions on installing a package, see [Install an environment promotion package](/help/quicksilver/administration-and-setup/set-up-workfront/workfront-testing-environments/environment-promotion-install-package.md).
