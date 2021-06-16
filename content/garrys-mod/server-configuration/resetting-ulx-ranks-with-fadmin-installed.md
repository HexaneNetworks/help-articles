#### I don't have FAdmin installed, how can I reset my ULX ranks?
[Resetting Ulx Ranks Without Fadmin Installed]((https://help.hexanenetworks.com/garrys-mod/server-configuration/resetting-ulx-ranks-without-fadmin-installed))

#### Why does the method differ when FAdmin is installed?
Recently ULX was updated, if their is no data present in the `garrysmod/data` folder it now checks the sv.db table for FAdmin and pulls the data from there and updates the data folder accordingly.

Unfortunately this makes resetting the ranks more difficult then before. Not only do you have to wipe the data folder but you also must modify the sv.db, which is rather risky. So going forward provided you aren't making any use of FAdmin we suggest you **disable it** in ``garrysmod/addons/darkrpmodification/lua/darkrp_config/disabled_defaults.lua``.

#### Method (Game Panel)
1. Navigate to the [Game Panel](https://hexane.gg) and proceed to login.
2. Click on **Game Services** button and if prompted select the server you would like to wipe the ranks of.
3. **Please ensure you STOP your service before you continue or you risk data corruption, you can do this by clicking the Stop button in the homepage of the gamepanel.**
4. Navigate to the **File Manager**.
5. Navigate to the ``garrysmod/data/ulib`` folder and proceed to delete the ``groups.txt`` file. This will be recreated with the default groups when you next launch your server.
![](https://raw.githubusercontent.com/HexaneNetworks/help-assets/master/assets/png/deleting-ulib-data.png)
6. Navigate back to the ``garrysmod`` folder and proceed to find the ``sv.db`` file.
7. Click on the download button on the same line as the ``sv.db`` file and proceed to drag and drop it onto your desktop.
8. Navigate to the [SQLite Browser](https://sqlitebrowser.org/) website and proceed to download the client for your operating system, in this example we will be referring to the Windows client only, however the method shouldn't differ too much between the different clients.
9. Run through the installation of SQLite Browser and proceed to open it.
10. Once it is open, click the **Open Database** button in the header and proceed to select the sv.db file we downloaded earlier.
11. Navigate to the **Browse Data** tab.
![](https://raw.githubusercontent.com/HexaneNetworks/help-assets/master/assets/png/opening-svdb.png)
12. In the table dropdown, proceed to select the ``FADMIN_GROUPS`` table.
13. Click inside of the table and proceed to press **CTRL+A** to select all records.
14. Proceed to click the **Delete Record** button in the top right of the **Browse Data** tab.
15. Click the **Write Changes** button in the header.
![](https://raw.githubusercontent.com/HexaneNetworks/help-assets/master/assets/png/modify-svdb.png)
16. Close the SQLite Browser application.
17. Navigate back to the [Game Panel](https://hexane.gg) and proceed to login.
18. Navigate to the **File Manager** and to the ``/garrysmod`` directory.
19. Proceed to upload the modified ``sv.db`` file to the directory.
20. Navigate to the [Game Panel](https://hexane.gg) and click the **Start** button to boot your server up.
