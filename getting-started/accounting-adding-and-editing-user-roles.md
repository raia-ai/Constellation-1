# Accounting - Adding and Editing User Roles

The purpose of this article is to explain the purpose of a user role and show how to set up a new role or edit an existing role. &#x20;

When adding a new user to the Accounting program, each user will need to be assigned a **User** **Role**.  A **User** **Role** defines which **Module**, a user will have access to, and which **Processes**, **Reports**, and/or **Setup** menu items the user will have access to in each module.&#x20;

For example, in the screenshot below, there are three **User Roles** available for selection, **Admin**, **Bookkeeper**, and **Processor**.  The **Admin** user role has access to **All Modules**, the **Bookkeeper** user role has access to the **AP**, **Bank**, **GL**, and **Payroll** modules, and the **Processor** user role has access to the **Agents**, **Sales** and **Trust** modules.  &#x20;

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/a32dbc93-6baa-4d84-b85d-318874737a11)

If you like, you can further define permissions, within each module, by menu item.  To add a new user role, or further define a user role within each module, by menu item, navigate to **System>>Setup>>Roles**. &#x20;

To edit an existing user role, follow the steps below:

* Highlight the **Role** you would like to edit.&#x20;
* Click **Edit**.&#x20;

If you would like to provide permission to additional modules, check the box to the right of the module in the **View?** column. &#x20;

If you would like to further define the user role within each module, check the **Show Module Permissions Details?** box.  Once the box is checked, you will see a **Module Permission Details** grid appear.  Listed in this grid, are all menu items, within each module selected for the **Role**.  For example, when editing the Bookkeeper Role, since they only have access to the **AP**, **Bank**, **GL**, **and Payroll** modules, you will only see menu item options for these modules.  Note, the menu items for each module, are grouped by **Type**.  For example, all **Processing** menu items will appear first, followed by all **Report** menu items, then **Setup** menu items will appear at the end of the selection list.  To remove the permission for a specific menu item, simply uncheck the box in the **Visible** column to the right of the menu item. &#x20;

![](https://constellation1.na3.teamsupport.com/api/attachments/action/1/1b56f745-be89-4c15-b837-36e64c5bbfc8)

Once all changes have been made, click **Save**.  Note, the changes will not take effect until the user logs out of the program and then back in again.  &#x20;

Recommendation for menu items that most users should not have access to:

* Agents>>Setup>>Mark Agent Charges/Credits As Posted to G/L. &#x20;
  * This function should only be performed under the guidance of an Accounting Support Technician.
* Accounts Payable>>Setup>>Mark AP Activity as Posted to G/L.
  * This function should only be performed under the guidance of an Accounting Support Technician.
* Bank>>Setup>>Mark Deposits as Posted to G/L.
  * This function should only be performed under the guidance of an Accounting Support Technician.
