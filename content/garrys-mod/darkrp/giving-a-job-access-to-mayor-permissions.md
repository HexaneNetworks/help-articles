#### What does giving a job access to the mayor permissions do?
Allows them to run all the commands listed in the F1 menu for mayors, including but not limited to the creation of laws, the providing of warrants and more.

#### Method
1. Navigate to the [Game Panel](https://hexane.gg) and proceed to login.
2. Click on the **Game Services** button and if prompted select the server you would like to edit the jobs of.
3. Navigate to the ``garrysmod/addons/darkrpmodification/lua/darkrp_customthings`` directory and proceed to edit the ``jobs.lua`` file.
4. Find the job that you would like to give access to mayor permissions.
5. Ensure there is a comma at the end of the last variable in the job code.
6. Add a new line and input ``mayor = true``.
7. Save the file and navigate back to the [Game Panel](https://hexane.gg) homepage.
8. Restart your server.

#### Example
![](https://raw.githubusercontent.com/HexaneNetworks/help-assets/master/assets/mayor-permissions.png)
