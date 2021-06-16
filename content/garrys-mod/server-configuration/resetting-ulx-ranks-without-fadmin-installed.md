#### I have FAdmin on my server, how can I wipe ULX ranks?
See this article here: [Resetting Ulx Ranks With Fadmin Installed](https://help.hexanenetworks.com/garrys-mod/server-configuration/resetting-ulx-ranks-with-fadmin-installed)

#### Why does the method differ if FAdmin is installed?
Recently the ULX addon was updated, if their is missing data in ULib's data folder it will pull the groups directly from the FADMIN_GROUPS table in the sv.db, meaning that there is extra steps to wipe the ranks.

#### Method (Game Panel)
1. Navigate to the [Game Panel](https://hexane.gg) and proceed to login.
2. Click on **Game Services** button and if prompted select the server you would like to wipe the ranks of.
3. **Please ensure you STOP your service before you continue or you risk data corruption, you can do this by clicking the Stop button in the homepage of the gamepanel.**
4. Navigate to the **File Manager**.
5. Navigate to the ``garrysmod/data/ulib`` folder and proceed to delete the ``groups.txt`` file. This will be recreated with the default groups when you next launch your server.
![](https://raw.githubusercontent.com/HexaneNetworks/help-assets/master/assets/deleting-ulib-data.png)
6. Navigate to the [Game Panel](https://hexane.gg) and click the **Start** button to boot your server up.
