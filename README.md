# Galaban's Moon Plugin
A simple moon plugin to warn about upcoming moon conjunctions and let you know the current state of the moon phases

Commands:

    moons  - shows the current state of the moons.
    moons help - shows the help screen
    moons <channel> - Echos the next three moon conjunction on a channel
    moons miniwin   - show/hide the miniwindow
    moons miniwin reset - resets the miniwindow in case it gets lost
    moonticks - enable/disable showing the moons every tick
    moonalerts - enable/disable the alerts regarding conjunctions
    moonlevel - sets how much output to show

The layout for the miniwindow is locked along with the other Aardwolf plugins.  "aard layout lock" and "aard layout unlock" will lock and unlock the layout, preventing/allowing the miniwin from being repositioned.

Note: You can also use "3moons" or "moon" for the channels, help, miniwin and moon commands

## To install
1. Download the raw file from github:
https://raw.githubusercontent.com/aardSzz/moons/master/Galabans_Moons.xml
2. Place the raw file into your "plugins" directory.  This is found in your Mushclient folder under /worlds/plugins.
3. Install the plugin in MushClient.  From the "File" menu, choose "plugins", then "Add".  Select the file and choose "OK".
