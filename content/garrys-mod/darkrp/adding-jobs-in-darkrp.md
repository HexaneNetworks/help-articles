#### Relevant Videos
[Using FileZilla (FTP) with Garry's Mod](https://www.youtube.com/watch?v=fwg3Dbty-dw)  
[Using WinSCP (FTP) with Garry's Mod](https://www.youtube.com/watch?v=QyBCXAaQG0Q)

#### Installing DarkRPModification
1. Navigate to the [Game Panel](https://gamepanel.hexanenetworks.com) and proceed to login.
3. Click on **Game Services** button and if prompted select the server you would like to install DarkRPModification to.
4. Navigate to the **Mod Manager**.
5. Install **DarkRP Modifications** which can be found under the **DarkRP** section.

#### Method 1 (FTP)
1. Login to your servers FTP using FileZilla or WinSCP - relevant videos can be found above.
2. Navigate to ``garrysmod/addons/darkrpmodification/lua/darkrp_customthings``.
3. Open the file titled ``jobs.lua``.
4. From here - you can either use a website tool to create jobs: [Csite.io](https://csite.io/tools/gmod-darkrp-job) or manually create them following the wiki: [Wiki](http://wiki.darkrp.com/index.php/DarkRP:Jobs)
5. Follow the instructions on the online tool or the official DarkRP wiki to help create the jobs.
6. Copy and paste the job you have created into the ``jobs.lua`` file under the line which states: **"Add jobs under the following line"**.
7. Proceed to save the file.
8. Restart the map or server.

#### Method 2 (Game Panel)
1. Navigate to the [Game Panel](https://gamepanel.hexanenetworks.com) and proceed to login.
2. Click on **Game Services** button and if prompted select the server you would like to add jobs to.
3. Navigate to the **File Manager**.
4. Navigate to ``garrysmod/addons/darkrpmodification/lua/darkrp_customthings``.
5. Open the file titled ``jobs.lua``.
6. From here - you can either use a website tool to create jobs: [Csite.io](https://csite.io/tools/gmod-darkrp-job) or manually create them following the wiki: [Wiki](http://wiki.darkrp.com/index.php/DarkRP:Jobs)
7. Follow the instructions on the online tool or the official DarkRP wiki to help create the jobs.
8. Copy and paste the job you have created into the ``jobs.lua`` file under the line which states: **"Add jobs under the following line"**.
9. Proceed to save the file.
10. Restart the map or server.

#### Example Job
![Job Example](https://raw.githubusercontent.com/HexaneNetworks/help-assets/master/assets/example-job.png)