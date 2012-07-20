WARNING: This is a BETA editor. Make a back-up of your Citizens and Denizen directories BEFORE using this software.

NOTE: CitizensUI is currently only compatible with citizens2 build 223 and Denizen build 124

CitizensUI is a .NET graphical user interface for the minecraft/bukkit plugin Citizens2 and associated character plugins.

Features:
 - No YAML to deal with!
 - Edits basic citizens2 NPCs and Denizens (other types coming soon!)
 - Pick your requirements, commands, items, colors, and scripts from convient drop-down lists.
 - Add large blocks of text with color to denizen scripts, with optional waits between lines.


![page1](http://i.imgur.com/bKXT3.png)

![page2](http://i.imgur.com/S0GDl.png)


To install:

- You will need .NET framework 3.5.
- Open the latest zip file on the [downloads](https://github.com/jrbudda/CitizensUI/downloads) page
- Extract the contents to the directory of your choice.
- Run the CitizensUI.exe
- The first time you run the program, it will prompt you to select your minecraft server 'plugins' directory.
- Click Load and it will load the data from the Citizens saves.yml, and the Denizen assignments.yml and all the files in the Denizen scripts folder.

Add and edit to your heart's delight.

When done, click save, this will overwrite the previously existing files. All scripts will be written to a single Scripts.yml file and other yml files in the scripts directory will be deleted.

Reload your citizens and denizen from the server. Any new NPCs you created will have to be spawned to set their location.



Known Limitations:
- Script Command and Requiremnt data is not verified for syntax. The proper syntax for each command is shown, it is up to you to format the data correctly.
- Cannot edit Sentry info (guard location, targets) yet.
- Alchemist, Blacksmith and Cititraders not fully supported yet.
- Cannot edit npc location or waypoints.
- Does not load or list denizen Bookmarks