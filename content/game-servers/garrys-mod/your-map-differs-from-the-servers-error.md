#### What is it and why does it happen?
The "Your map differs from the server" error is produced when a player tries to connect when they have a different map download that is under the same name as the map your server/the server you are trying to join is currently running.

#### Method - For the Player
1. Navigate to your Steam directory.
	*For example C:\Program Files (x86)\Steam
2. From there, navigate to ``steamapps/common/GarrysMod/garrysmod/maps``.
3. Proceed to remove any maps that have the same name as the map that the server you are trying to connect to is running.
3. Navigate back to the ``garrysmod`` directory and enter the ``addons`` directory.
4. Proceed to remove any maps that have the same name as the map that the server you are trying to connect to is running.
5. Restart Garry's Mod.
6. Attempt to connect to the server.

##### If the issue persists:
1. Navigate to your Steam directory.
	*For example C:\Program Files (x86)\Steam
2. From there, navigate to ``steamapps/common/GarrysMod/garrysmod/downloads/server``.
3. Delete the contents of the folder.
	*Note: This **removes** all files you have installed from any server, as a result you will redownload everything upon joining a server.
4. Reconnect to the server.

#### Method - For the Server Owner
1. Navigate to the [Game Panel](https://gamepanel.hexanenetworks.com) and proceed to login.
2. Navigate to the **File Manager**
3. Navigate to the ``garrysmod/maps`` directory.
4. Proceed to rename the map that you are currently using on the server.
5. If you are using FastDL for your map, sync the FastDL.
6. Restart your server.