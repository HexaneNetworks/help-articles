#### Relevant Videos
[Using FileZilla (FTP) with Garry's Mod](https://www.youtube.com/watch?v=fwg3Dbty-dw)  
[Using WinSCP (FTP) with Garry's Mod](https://www.youtube.com/watch?v=QyBCXAaQG0Q)

#### Method 1 (Game Panel)
1. Navigate to the [Game Panel](https://gamepanel.hexanenetworks.com) and proceed to login.
2. Click on **Game Services** button and if prompted select the server you would like to change the name of.
3. Navigate to **Configuration Files**.
4. Edit the ``server.cfg`` file.
5. Scroll to the bottom of the file.
6. On a **new line**, add ``sv_loadingurl "YOUR URL HERE"``
7. Save the file.
8. Restart the map or server.

#### Method 2 (FTP)
1. Login to your servers FTP using FileZilla or WinSCP - relevant videos can be found above.
2. Navigate to ``garrysmod/cfg``.
3. Find the ``server.cfg`` file and proceed to edit it.
4. Scroll to the bottom of the file.
5. On a **new line**, add ``sv_loadingurl "YOUR URL HERE"``
6. Save the file.
7. Restart the map or server.

#### Example
![Adding a loading screen](https://raw.githubusercontent.com/HexaneNetworks/help-assets/master/assets/png/example-loading.png)