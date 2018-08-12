#### What does enabling the spawning of vehicles do?
It allows the group of users you specified in the settings file to spawn entities from the **Vehicles** tab in the spawn menu.

#### Method (Game Panel)
1. Navigate to the [Game Panel](https://gamepanel.hexanenetworks.com) and 
proceed to login.
2. Click on the **Game Services** button and if prompted select the server you would like to enable the spawning of vehicles on.
3. Navigate to the **File Manager**.
4. Navigate to the ``garrysmod/addons/darkrpmodification/lua/darkrp_config`` and proceed to edit the **settings.lua** file.
5. Once editing the file, press **CTRL+F** and search for: ``GM.Config.adminvehicles``.
6. Scroll down to the highlighted line.
7. Please refer to the **Value Options** section below that described what the different numbers mean.
8. By default the value of ``GM.Config.adminvehicles`` will be 3, change it to the value you would like according to the **Value Options** section below.
9. Proceed to click the **Save** button in the navigation bar.
10. Navigate back to the [Game Panel](https://gamepanel.hexanenetworks.com)'s homepage and proceed to click **Restart**.

#### Value Options
**0** - This allows everyone to spawn vehicles.
**1** - Allows admins or higher to spawn vehicles.
**2** - Allows Superadmins or higher to spawn vehicles.
**3** - Allows the spawning of vehicles via the RCON only.

#### Example
![Enable Spawning of Vehicles in DarkRP](https://raw.githubusercontent.com/HexaneNetworks/help-assets/master/assets/png/adminvehicles.png)