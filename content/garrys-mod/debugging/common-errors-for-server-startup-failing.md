The common errors found in the [web console](https://help.hexanenetworks.com/game-servers/general/web-console-explained) that causes the server to not start, with the reasoning, example and fix explained here.

----

## Gamemode Error
`Error: Couldn't change active gamemode - 'example' not found`

##### Reasoning
This error occurs when the gamemode imputed in the commandline doesn’t exist or is broken within the `/garrysmod/gamemodes/` directory. Ensure the name imputed into the commandline manager in the `Gamemode` box is the exact same name as the folder of the gamemode in it's directory. 

##### Example

**Incorrect** name used in the commandline manager for the DarkRP gamemode. 

![Gamemode Error Example Image Incorrect](https://github.com/HexaneNetworks/help-assets/blob/38ed262d4f2a8ab9b00a76a7235a2f7ac9c72601/assets/png/gamemode-error-commandline-wrong.png?raw=true)

**Correct** name used in the commandline manager for the DarkRP gamemode. 

![Gamemode Error Example Image Correct](https://github.com/HexaneNetworks/help-assets/blob/38ed262d4f2a8ab9b00a76a7235a2f7ac9c72601/assets/png/gamemode-error-commandline-correct.png?raw=true)

**Folder Name** for the DarkRP Gamemode located in `/garrysmod/gamemodes/`

![Gamemode Error Example Image File Directory](https://github.com/HexaneNetworks/help-assets/blob/38ed262d4f2a8ab9b00a76a7235a2f7ac9c72601/assets/png/gamemode-error-filemanager-foldername.png?raw=true)



#### Resolving the Error via the Game Panel File Manager

1. Login to the [Game Panel](https://gamepanel.hexanenetworks.com)
2. Navigate to the **Game Services**
	(If you have multiple servers, select the one you wish to apply the fix)
3. Click on the **Commandline Manager**.
4. Head over to **Custom Commandlines**.
5. Create or edit the commandline.
6. Edit the text in the box of the ``Gamemode`` section to the folder name listed in `/garrysmod/gamemodes/`
7. Save and proceed to restart the server.

----
## Map Error
`Error: map load failed: example not found or invalid`

Reasoning
This error occurs when the map imputed in the custom commandline doesn’t exist or is invalid in the `/garrysmod/maps/` directory. The map name may be incorrect or the map needs to be uploaded to the maps folder or mounted on via the steam workshop to be found by the server.

#### Resolving the Error via the Game Panel File Manager

1. Login to the [Game Panel](https://gamepanel.hexanenetworks.com)
2. Navigate to the **Game Services**
	(If you have multiple servers, select the one you wish to apply the fix)
3. Click on the **Commandline Manager**.
4. Head over to **Custom Commandlines**.
5. Create or edit the commandline.
6. Edit the text in the box of the ``Map`` section to the map name listed in `/garrysmod/map/`. *Example: rp_downtown_v4c_v2*
7. Save and proceed to restart the server.