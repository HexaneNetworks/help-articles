#### What does a door group do?
A door group allows you to whitelist a door to every Team you have specified for that door group, meaning anyone that isn't apart of one of those teams can't unlock and lock the door. An example of where this would be used is the Police Department, locking it for Cops and Mayors only.

#### Installing DarkRPModification
1. Navigate to the [Game Panel](https://gamepanel.hexanenetworks.com) and proceed to login.
2. Click on **Game Services** button and if prompted select the server you would like to install DarkRPModification to.
3. Navigate to the **Mod Manager**.
4. Install **DarkRP Modifications** which can be found under the **DarkRP** section.

#### Method
1. Navigate to the [Game Panel](https://gamepanel.hexanenetworks.com) and proceed to login.
2. Click on **Game Services** button and if prompted select the server you would like to add door groups to.
3. Navigate to the **File Manager** and proceed to the ``garrysmod/addons/darkrpmodification/lua/darkrp_customthings`` directory.
4. Edit the ``doorgroups.lua`` file.
5. In a new tab, navigate to the [CSite Door Group Generator](https://csite.io/tools/gmod-darkrp-door).
6. In the **Name** field proceed to fill out out what you would want to appear on the door, for example *"Cops and Mayor only"*.
7. In the **Jobs** field fill out the teams for each job you would like added to the door group, press enter after writing each team name.
8. Ensure that CSite says that all the required fields are filled in and proceed to copy the Door Group code and paste it into the ``doorgroups.lua`` file we have open in another tab.

#### Example
![](https://raw.githubusercontent.com/HexaneNetworks/help-assets/master/assets/png/creating-door-groups.png)