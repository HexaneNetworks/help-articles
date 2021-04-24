#### What does this script do?
It disables the collisions between players and vehicles, as a result players can walk through vehicles and take no damage from impact. This is the most effective way of mitigating the ability for cars to kill players.

#### Method
1. Navigate to the [Game Panel](https://gamepanel.hexanenetworks.com) and 
proceed to login.
2. Click on **Game Services** button and if prompted select the server you would like to disable vehicle collisions on.
3. Navigate to the **File Manager**.
4. From there, proceed to navigate to the `garrysmod/lua/autorun/server` directory.
5. Create a file titled `disable_vehicle_collisions.lua`.
6. Proceed to paste the following script in:
```
hook.Add("PlayerSpawnedVehicle","DisableCollisionVehicle", function(ply, ent)
  if IsValid(ent) then
    ent:SetCollisionGroup(COLLISION_GROUP_WEAPON)
  end
end)
```
7. Click the **Save** button.
8. Navigate back to the [Game Panel](https://gamepanel.hexanenetworks.com).
9. Restart your server.

#### Example
![](https://raw.githubusercontent.com/HexaneNetworks/help-assets/master/assets/disable_vehicle_collisions.png)