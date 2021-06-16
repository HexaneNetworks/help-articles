#### What do jail positions do?
As different maps have different locations for the police department and more importantly the jail cells, DarkRP allows any job with the chief variable set to true to set custom jail positions. This means that when a player is arrested they are teleported to one of the jail positions.

#### Method
1. Navigate to the [Game Panel](https://hexane.gg) and proceed to login.
2. Click on the **Game Services** button and if prompted select the server you would like to edit the jobs of.
3. Navigate to the ``garrysmod/addons/darkrpmodification/lua/darkrp_customthings`` directory and proceed to edit the ``jobs.lua`` file.
4. Find the job that you would like to give access to jail positions.
5. Ensure there is a comma at the end of the last variable in the job code.
6. Add a new line and input ``chief = true``.
7. Save the file and navigate back to the [Game Panel](https://hexane.gg) homepage.
8. Restart your server.

#### Example
![](https://raw.githubusercontent.com/HexaneNetworks/help-assets/master/assets/png/jailpositions.png)
