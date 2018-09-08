#### What does disallowing clientsize scripts do?
It prevents users from running clientside scripts when they are in your server.

#### Method (Game Panel)
1. Navigate to the [Game Panel](https://gamepanel.hexanenetworks.com) and 
proceed to login.
2. Click on the **Game Services** button and if prompted select the server you would like to disallow clientside scripts on.
3. Navigate to the **File Manager**.
4. Navigate to the ``garrysmod/addons/darkrpmodification/lua/darkrp_config`` and proceed to edit the **settings.lua** file.
5. Once editing the file, press **CTRL+F** and search for: ``GM.Config.disallowClientsideScripts``.
6. Scroll down to the highlighted line.
7. After the equals replace the ``false`` with ``true``.
8. Hit the save button in the top left of the file manager.
9. Navigate back to the [Game Panel](https://gamepanel.hexanenetworks.com)'s homepage and proceed to click **Restart**.