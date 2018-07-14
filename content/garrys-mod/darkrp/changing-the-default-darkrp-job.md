#### What does changing the default DarkRP job do?
Changing the default DarkRP job means that when a player initially connects to your server, they won't be placed in the Citizen job by default, they will be placed in the job you specified. This is useful for servers that provide an alternative type of roleplay such as StarwarsRP and MilitaryRP.

In addition to this, when a player is demoted they will be reverted back to this job.

#### Method (Game Panel)
1. Navigate to the [Game Panel](https://gamepanel.hexanenetworks.com) and proceed to login.
2. Click on **Game Services** button and if prompted select the server you would like to change the name of.
3. Navigate to the **File Manager**.
4. Navigate to the ``garrysmod/addons/darkrpmodification/lua/darkrp_customthings`` and proceed to edit the **jobs.lua** file.
5. Scroll down to the line containing ``GAMEMODE.DefaultTeam = TEAM_CITIZEN``.
6. By default, the ``GAMEMODE.DefaultTeam`` variable will be defined as ``TEAM_CITIZEN``, in order to change the default job, you must replace ``TEAM_CITIZEN`` with the desired default job's team, for example ``TEAM_HEXANE``.
7. Once you have done this, click the **Save** button in the navigation bar.
8. Navigate back to the [Game Panel](https://gamepanel.hexanenetworks.com)'s homepage and proceed to click the **Restart** button.
9. Once the restart process has finished, rejoin your server.

#### Example
![Changing Default Job](https://raw.githubusercontent.com/HexaneNetworks/help-assets/master/assets/png/change-default-job.png)