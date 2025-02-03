# Clock-Maker-English-Patch

Official English Version: https://www.nintendo.com/us/store/products/clock-maker-my-clock-ver-digital-with-timer-switch/

Hello! This is an English translation patch for Clock Maker.

[Clock Maker : My Clock - ver. digital (with timer)] - Full Title

The patches are in xdelta format and you'll need a couple of things to get started.

First, you need xDelta: https://www.romhacking.net/utilities/598/
and NxDumpTool: https://github.com/DarkMatterCore/nxdumptool

Use NxDumpTool to create a romFS dump of your copy of the game, then get 4 files from your dump.
"resources.assets" ; "sharedassets1.assets" ; "sharedassets2.assets" ; "sharedassets3.assets"

Copy them into wherever you put your xDelta patches from the download, and patch each file from your romFS dump with the corresponding patch.

Then, we'll make a LayeredFS folder structure to have these newly patched files loaded instead of the original game files.

Folder structure should look like this:

SDROOT\atmosphere\contents\0100BA3018C10000\romfs\Data\ *4 patched files here*

Start up the game and enjoy!

I did a quick bug check but I'm not 100% sure everything is fine, if there is an issue just let me know and I'll fix it. 

Enjoy!
