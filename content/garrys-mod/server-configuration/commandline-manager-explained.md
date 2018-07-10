#### Relevant articles
[Changing The Gamemode](https://help.hexanenetworks.com/garrys-mod/server-configuration/changing-the-gamemode)  
[Changing The Map](https://help.hexanenetworks.com/garrys-mod/server-configuration/changing-the-map)  
[Engine Hunk Overflow Error](https://help.hexanenetworks.com/garrys-mod/debugging/engine-hunk-overflow-error)  
[Valve Anti Cheat](https://support.steampowered.com/kb_article.php?p_faqid=370)  

#### What is the Commandline Manager?
The commandline manager for Garry's Mod allows you to edit and interact with the pre-defined startup parameters of your server.

#### Base requirements of a commandline
1. You must fill out the **Description** text field, for example ``Garry's Mod Commandline``.
2. You must tick the **Select** box to the left of: **Server Config**, **Gamemode**, **RCon Password** and **Startup map**.
3. It's advised that you leave any values you are unsure of as the default - especially **Server Config**.
4. Both your **Gamemode** and **Startup map** must be valid for the server to boot correctly. See relevant article above.

#### Reaching the Commandline Manager
1. Navigate to the [Game Panel](https://gamepanel.hexanenetworks.com) and proceed to login.
2. Navigate to the **Commandline Manager**.
3. Click on the **Custom Commandlines** tab.
4. Click **New** to create a new one or click **Edit** to edit an existing one.

#### Commandline options
**Server Config** = Defines the file name of your ``server.cfg`` (This value is set by default, we advise against changing it)  
**Gamemode** = Defines the gamemode that your Garry's Mod server will be running, this should always be the foldername of the gamemode, for example ``darkrp``  
**Disable Valve Anti-Cheat** = Disables Valve Anti-Cheat. See relevant articles for more information.  
**RCon Password** = Defines the password that you must use to allow usage of the RCon.  
**Startup map** = The map that your server will use when the server initially boots. For example ``rp_downtown_v4c_v2``.  
**Steam API Auth Key** = The key used when setting up a Steam WorkshopDL. You can find this here: [Steam API Key](https://steamcommunity.com/dev/apikey).  
**Tickrate** = The rate at which the server refreshes. Higher is reccomended for a lower playercount and for gamemodes such as Deathrun. Lower tickrate is reccomended for heavily intense gamemodes such as DarkRP with a fair amount of players and addons.  
**Workshop Collection ID** = Defines the ID of your Workshop collection that you are using for your Garry's Mod servers WorkshopDL.  
**hunkalloclightmaps** = Used to prevent your server crashing when using large maps such as Evocity and Rockford. See relevant articles for more information.  