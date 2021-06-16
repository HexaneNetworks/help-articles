#### Relevant videos
[Extracting Garry's Mod Workshop Addons](https://www.youtube.com/watch?v=-d8JXI7QUhE)
[Using FileZilla (FTP) with Garry's Mod](https://www.youtube.com/watch?v=fwg3Dbty-dw)  
[Using WinSCP (FTP) with Garry's Mod](https://www.youtube.com/watch?v=QyBCXAaQG0Q)

#### What happens when I add the map to the FastDL?
When players join your server, during the loading process they will download the map.

#### Preparing the map
1. Follow the video listed above in the **Relevant videos** section in order to extract the Workshop version of the map.
2. Open the extracted folder and proceed to open the ``maps`` folder.
3. Drag the file inside of the maps folder to your Desktop, this file should end in **.bsp** if you have file extensions enabled.

#### Uploading and synchronizing the map (Game Panel)
1. Navigate to the [Game Panel](https://hexane.gg) and proceed to login.
2. Click on **Game Services** button and if prompted select the server you add the map to the FastDL of.
3. Navigate to the **File Manager**.
4. Navigate to the ``garrysmod/maps`` directory.
5. Click the **Upload** button and proceed to upload the map.
![Upload location](https://raw.githubusercontent.com/HexaneNetworks/help-assets/master/assets/png/uploading-map-gamepanel.png)
6. Return to the [Game Panel](https://hexane.gg).
7. Click the **Fast Downloads Sync** button.
8. Wait until the console states that the synchronization has finished, this may take a while.
9. Restart your server.

#### Uploading and synchronizing the map (FTP)
1. Login to your servers FTP using FileZilla or WinSCP - relevant videos can be found above.
2. Navigate to the ``garrysmod/maps`` directory.
![Upload location](https://raw.githubusercontent.com/HexaneNetworks/help-assets/master/assets/png/uploading-map-ftp.png)
3. Drag the map file we prepared earlier into that directory and wait for the transfer to finish.
4. Navigate to the [Game Panel](https://hexane.gg) and proceed to login.
5. Click the **Fast Downloads Sync** button.
6. Wait until the console states that the synchronization has finished, this may take a while.
7. Restart your server.
