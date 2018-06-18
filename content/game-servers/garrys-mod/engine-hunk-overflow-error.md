#### What is it and why does it happen?
Engine Hunk Overflow is when the map which the server is attempting to load is large or poorly made, this overloads the games engine and causes a “Overflow” which prevents the server booting.
You'll see this error in the servers web console if you have this problem: `engine hunk overflow`

#### Solution to fix via the Game Panel
 1. Login to the [Game Panel](https://gamepanel.hexanenetworks.com)
 2. Navigate to the **Game Services**
	(If you have multiple servers, select the one you wish to apply the fix)
 3. Click on the **Commandline Manager**.
 4. Head over to **Custom Commandlines**.
 5. Create or edit the commandline 
 6. Tick the box to left side of the text ``hunkalloclightmaps``
 7. Save and proceed to restart the server