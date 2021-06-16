#### Why should I replace the default DarkRP F4 Menu?
When installing your own F4 menu, it is good practice to disable DarkRPs default F4 menu.

#### Method
1. Navigate to our [Game Panel](https://hexane.gg/) and proceed to login.
2. Click on the **Game Services** button and if prompted select the server you would like to disable the default F4 menu on.
3. Navigate to the **File Manager**.
4. Navigate to the `garrysmod/addons/darkrpmodification/lua/darkrp_config` and proceed to edit the `disabled_defaults.lua` file.
5. Once you're editing the file, press **CTRL+F** and search for `DarkRP.disabledDefaults["modules"]`.
6. Find the line that begins with `["f4menu"]`.
7. Change the value of this property from `false` to `true`.
8. Once completed, click the save button. You will be directed to the file manager again.
9. Restart your server, after this process is finished, the default DarkRP F4 menu will be disabled.


#### Example
![Changing the value](https://raw.githubusercontent.com/HexaneNetworks/help-assets/master/assets/disabling-default-f4-menu.png)
