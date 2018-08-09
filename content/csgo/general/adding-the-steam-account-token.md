#### What is a steam account token (GSLT)?
GSLTs is a string of text which CSGO servers require upon botting to make them appear as a public server.

#### Creating your token.
1. Navigate to [https://steamcommunity.com/dev/managegameservers](https://steamcommunity.com/dev/managegameservers)
2. Create the token. See the screenshot for an example. 

![](https://raw.githubusercontent.com/HexaneNetworks/help-assets/8d0854eaf18929c39b841ab226a7ed6e8b7d4fbf/assets/png/steamaccounttokencsgo.png)

#### Adding your token to the server.
1. Login to the [Game Panel](https://gamepanel.hexanenetworks.com)
2. Navigate to **Game Services**
	(If you have multiple servers, select the one you wish to apply the token to)
3. Click on the **Commandline Manager**.
4. Click **Select** on one of the pre-made commandlines.
6. Paste your token in the `sv_setsteamaccount` box. 
7. Save and proceed to restart the server.