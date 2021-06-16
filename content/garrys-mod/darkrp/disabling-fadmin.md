#### Why would I want to disable FAdmin?
If you have installed ULX, running two admin addons typically isn't a good idea. Whilst they are built to work together issues with permissions and rank inheritance can arise. In addition to this with FAdmin disabled, wiping the ULX ranks becomes much easier, see this article here for more information: [Resetting Ulx Ranks](https://help.hexanenetworks.com/garrys-mod/server-configuration/resetting-ulx-ranks).

#### Method
1. Navigate to our [Game Panel](https://hexane.gg/) and proceed to login.
2. Click on the **Game Services** button and if prompted select the server you would like to disable FAdmin on.
3. Navigate to the **File Manager**.
4. Navigate to the `garrysmod/addons/darkrpmodification/lua/darkrp_config` and proceed to edit the `disabled_defaults.lua` file.
5. Once you're editing the file, press **CTRL+F** and search for `DarkRP.disabledDefaults["modules"]`.
6. Find the line that begins with `["fadmin"]`.
7. Change the value of this property from `false` to `true`.
8. Once completed, click the save button. You will be directed to the file manager again.
9. Navigate back to our [Game Panel](https://hexane.gg/).
10. Restart your server, after this process is finished, FAdmin will be disabled.

#### Example
![](https://raw.githubusercontent.com/HexaneNetworks/help-assets/master/assets/disabling-fadmin.png)