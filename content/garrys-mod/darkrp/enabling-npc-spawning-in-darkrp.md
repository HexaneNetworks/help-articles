#### Method (Game Panel)
1. Navigate to the [Game Panel](https://hexane.gg) and proceed to login.
2. Click on the **Game Services** button and if prompted select the server you would like to enable the spawning of NPCs on.
3. Navigate to the **File Manager**.
4. Navigate to the ``garrysmod/addons/darkrpmodification/lua/darkrp_config`` and proceed to edit the **settings.lua** file.
5. Once editing the file, press **CTRL+F** and search for: ``GM.Config.adminnpcs``.
6. Scroll down to the highlighted line.
7. Please refer to the **Value Options** section below that described what the different numbers mean.
8. By default the value of ``GM.Config.adminnpcs`` will be 3, change it to the value you would like according to the **Value Options** section below.
9. Proceed to click the **Save** button in the navigation bar.
10. Navigate back to the [Game Panel](https://hexane.gg)'s homepage and proceed to click **Restart**.

#### Value Options
**0** - This allows everyone to spawn NPCs.
**1** - Allows admins or higher to spawn NPCs.
**2** - Allows Superadmins or higher to spawn NPCs.
**3** - Allows the spawning of NPCs via the RCON only.
