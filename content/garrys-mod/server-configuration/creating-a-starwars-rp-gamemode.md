#### Relevant Links
[Using FileZilla (FTP) with Garry's Mod](https://www.youtube.com/watch?v=fwg3Dbty-dw)
[Using WinSCP (FTP) with Garry's Mod](https://www.youtube.com/watch?v=QyBCXAaQG0Q)


#### What does this change impact?
This makes your gamemode appear as "StarwarsRP" in the server browser.

#### Prerequisites
This article only covers the method to create a StarwarsRP gamemode using an FTP client as that makes the process much easier. Please see the **Relevant Links** section and refer to one of the videos linked there depending on which is your preferred FTP client.

#### Preparing the gamemode
1. Navigate to the [DerivedRP Release Page](https://github.com/FPtje/DarkRP/releases) and proceed to click on and download ``derivedrp.zip``.
2. Using any extraction software of your choice (WinRAR is recommended), open the ``derivedrp.zip`` file and proceed to drag the ``derivedrp`` folder to your Desktop.
3. Rename the ``derivedrp`` folder to ``starwarsrp`` and proceed to open it.
4. Rename the ``derivedrp.txt`` to ``starwarsrp.txt`` and proceed to edit the file. 
5. Replace the title field with ``"StarwarsRP"``.  
![](https://raw.githubusercontent.com/HexaneNetworks/help-assets/master/assets/starwarsrp-txt.png)  
6. Navigate back into the ``derivedrp`` folder and proceed to open the ``gamemode`` folder.
7. Edit both the ``cl_init.lua`` and the ``init.lua`` and proceed to change the ``GM.Name`` to ``StarwarsRP``.
![](https://raw.githubusercontent.com/HexaneNetworks/help-assets/master/assets/starwars-init-lua.png)


#### Installing the gamemode
1. Navigate to the [Game Panel](https://hexane.gg) and proceed to login.
2. Click on the **Game Services** button and if prompted select the server you would like to install StarwarsRP to.
3. Navigate to the **Mod Manager** and proceed to install the latest version of DarkRP.
4. Open up your preferred FTP client and proceed to login, if you're having trouble with this step refer to the videos in the **Relevant Links** section.
5. Navigate to the `garrysmod/gamemodes` directory and proceed to drag in the StarwarsRP derived gamemode we prepared earlier.
6. Proceed to follow the [Changing The Gamemode](https://help.hexanenetworks.com/garrys-mod/server-configuration/changing-the-gamemode) article set the gamemode to ``starwarsrp``.
7. Restart your server.
