#### What is a Steam Game Server Login Token (GSLT)?
It's a token (like a password) used to authenticate your server with Steam. 

#### Creating your token
1. Navigate to [https://steamcommunity.com/dev/managegameservers](https://steamcommunity.com/dev/managegameservers)
2. Create the token and fill out the App ID of the game your server is running.
Garry's Mod = `4000`
CSGO = `730`
TF2 = `440`  

#### Adding your token to the server
1. Login to the [Game Panel](https://hexane.gg)
2. Navigate to **Game Services**
	(If you have multiple servers, select the one you wish to apply the token to)
3. Click on the **Commandline Manager**.
4. Navigate to your custom commandline and edit.
6. Paste your token in the `Game Server Login Token` box. 
7. Save and proceed to restart the server.

Feel free to contact us if you have any questions or problems with this. 

More information is located on the Gmod Wiki regarding the tokens: https://wiki.facepunch.com/gmod/Steam_Game_Server_Accounts