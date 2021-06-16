#### Why should I disable default DarkRP jobs?
Disabling the default DarkRP jobs could be something you want to do if you have made a different gamemode of some sort. In example; StarWarsRP, PoliceRP, etc.

#### Method
1. Navigate to our [Game Panel](https://hexane.gg/) and proceed to login.
2. Click on the **Game Services** button and if prompted select the server you would like to disable the default jobs for.
3. Navigate to the **File Manager**.
4. Navigate to the `garrysmod/addons/darkrpmodification/lua/darkrp_config` and proceed to edit the `disabled_defaults.lua` file.
5. Once you're editing the file, press **CTRL+F** and search for `DarkRP.disabledDefaults["jobs"]`.
6. Find the jobs that you wish to disable within this section, these jobs are mapped by their command.
7. When you have the jobs you wish to disable, change the value at the end of the line from `false` to `true`. This will disable the job, if you wish to re-enable the job again then change the value from `true` to `false`.
8. Once you have altered the jobs, click the save button. You will be directed to the file manager again.
9. Restart your server, after this process is finished, the jobs will be disabled on launch.


#### Example
![Changing the value](https://raw.githubusercontent.com/HexaneNetworks/help-assets/master/assets/png/disabling-default-darkrp-jobs.png)
