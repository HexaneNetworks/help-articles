#### What does this impact?
This will change your startup map, in addition to this it will change the map that your server is listing as using in the Garry's Mod server list.

#### Method
1. Navigate to the [Game Panel](https://hexane.gg) and proceed to login.
2. Click on **Game Services** button and if prompted select the server you would like to change the map of.
3. Navigate to the ``garrysmod/maps`` directory and find the file of the map you installed in there.
4. Note down the filename of the map **without** the ``.bsp`` file extension. For example ``rp_downtown_v4c_v2``.
5. Navigate to the **Commandline Manager**.
6. Click on the **Custom Commandlines** tab.
7. Click the **New** button to create a new commandline.
8. Refer to this article: [Commandline Manager Explained](https://help.hexanenetworks.com/garrys-mod/server-configuration/commandline-manager-explained) and edit your commandline appropriately.
9. Change the **Startup map** to the map name that we noted down earlier, for example ``rp_downtown_v4c_v2``.
10. Navigate back to the **Custom Commandlines** tab and ensure that commandline is **Selected**.
11. Restart your server.

#### Example
![Example Map](https://raw.githubusercontent.com/HexaneNetworks/help-assets/master/assets/startup-map.png)