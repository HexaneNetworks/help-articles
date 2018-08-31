#### What does exporting a MySQL database do?
Exporting a MySQL database downloads a backup of the database to your system, allowing you to restore **some data** if there happens to be any data loss.

#### Method
1. Login to [cPanel](https://cpanel.hexanenetworks.com) by doing one of the following: using the login information provided in the **Web Hosting Information** email or using the CPanel shortcut in the [Billing Area](https://billing.hexanenetworks.com/)
2. Once you are in cPanel search for **phpMyAdmin** and proceed to click on the appropriate result.
3. In the sidebar on the left select the database you would like to export.
4. In the navigation bar at the top head to the **Export** section.
5. In the **Export method** select the **Quick** option. We won't be covering the **Custom** option in this article as we expect only advanced users to use that option.
6. In the **Format** dropdown we recommend selecting **SQL**.
7. Hit the **Go** button, this should produce a ``.sql`` file, this is your exported database. If you open it you will see the SQL code for the table structure and contents of the database.

#### Example
![](https://raw.githubusercontent.com/HexaneNetworks/help-assets/master/assets/png/exporting-a-database.png)