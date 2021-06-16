#### How did the update impact removing Workshop addons?
Garry's Mod changed the way you load addons into your server via a WorkshopDL. All addons are now cached in ``garrysmod/cache/srcds``, as a result of this, when you remove an item from your Workshop collection you must remove the file titled the Workshop ID of the addon you are attempting to remove from that directory.

#### Method (Game Panel)
1. Navigate to your Workshop collection.
2. Remove the addon(s) you would like to remove from your Workshop collection.
3. Navigate to the page for each Workshop addon you want to remove, right click on the page and click **Copy Page URL**.  
![](https://raw.githubusercontent.com/HexaneNetworks/help-assets/master/assets/removing-workshop-addons.png)
4. Proceed to take the Workshop ID from the end of the URL.
    For example the Workshop ID for `https://steamcommunity.com/sharedfiles/filedetails/?id=248302805` would be ``248302805``
5. Navigate to the [Game Panel](https://hexane.gg) and 
proceed to login.
6. Click on **Game Services** button and if prompted select the server you would like to remove a workshop addon from.
7. Navigate to the **File Manager**. 
8. Navigate to the ``garrysmod/cache/srcds`` directory.
9. Delete any files that are titled the Workshop ID of the addon you are trying to remove. For example ``248302805.gma``.
