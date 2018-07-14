#### What does this impact?
This will change your startup map, in addition to this it will change the map that your server is listing as using in the Garry's Mod server list.

#### Method
1. Navigate to the [Game Panel](https://gamepanel.hexanenetworks.com) and proceed to login.
2. Click on **Game Services** button and if prompted select the server you would like to change the name of.
3. Navigate to the **File Manager**.
4. Navigate to the ``garrysmod/maps`` directory and find the file of the map you installed in there.
5. Note down the filename of the map **without** the ``.bsp`` file extension. For example ``rp_downtown_v4c_v2``.
6. Navigate to the **Commandline Manager**.
7. Click on the **Custom Commandlines** tab.
8. Click the **New** button to create a new commandline.
9. Refer to this article: [Commandline Manager Explained](https://help.hexanenetworks.com/garrys-mod/server-configuration/commandline-manager-explained) and edit your commandline appropiately.
10. Change the **Startup map** to the map name that we noted down earlier, for example ``rp_downtown_v4c_v2``.
11. Navigate back to the **Custom Commandlines** tab and ensure that commandline is **Selected**.
12. Restart your server.

#### Example
![Example Map](https://raw.githubusercontent.com/HexaneNetworks/help-assets/master/assets/png/startup-map.png)