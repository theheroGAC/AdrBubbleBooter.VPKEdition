# AdrBubbleBooter.VPKEdition
Adrenaline Bubble Booter VPK Edition (C) 2017-2020 LMAN &lt;LeecherMan>


Directly boot any PSP file (ISO\CSO\PBP\PSOne) from LiveArea's Bubbles.

v0.9:
-Rewrote booter codes and updated adrenaline version to v6.8.
-Re-added ability to use any png image as startdat boot logo when booting bubbles -> Add any 24bit png image with size of 480x272 into bubble data folder ex. data/boot.png.
-Added ability to automatically load any saved state upon booting bubbles for each bubbles -> Adjust Auto Load State option in Booter tab in Adrenaline menu.
-Added ability to skip auto load saved state if enabled upon booting bubbles when holding L-Trigger while booting bubble.
-Added ability to restart booter -> Go to Booter tab in Adrenaline menu and press on the 'Restart Booter' option.
-Added ability to reset booter settings -> Go to Booter tab in Adrenaline menu and press on the 'Reset Booter Settings' option.
-Added ability to exit game from booter tab -> Go to Booter tab in Adrenaline menu and press on the 'Exit Game' option.
-Added ability to suspend game when opening adrenaline menu -> Adjust the Suspend option in Booter tab in Adrenaline menu.
-Added ability to change Adrenaline menu colors by editing the colors in 'menucolor.bin' file.
-Added a new option to Adrenaline settings to keep aspect ratio when scaling psp or pops screen in Adrenaline menu.
-Added date, time and battery percentage string to Adrenaline menu title.
-Updated 'PS button' for Booter mode -> You can change it to open Adrenaline menu or Go to LiveArea screen -> Adjust PS Button option in Booter tab in Adrenaline menu.
-Updated minor code in Adrenaline regarding saving state to prevent losing the existing saved state file if an error occurred.
-Updated the included AdrBubbleBooterCreator to the latest version.
-Some other minor changes.

v1.0:
-Updated adrenaline version to v6.9.
-Added ability to change game cpu clock speed per bubble.
-Added ability to enable or disable high memory layout per bubble.
-Added ability to enable or disable nonpdrm engine per bubble.
-Re-added ability to enable or disable plugins option per bubble.
-Updated CPU speed list with more values for both adrenaline and booter.
-Updated configuration binary file for booter.
-Some minor typo-change.

v1.1:
-Restore visibility of the USB option on non PSVTV.
-Fixed AdrBubbleBooter installer typo version of the LiveArea bubble.

v1.2:
-Updated 'PS button' for Booter mode with a new option.
-Improved frame pacing when using Original graphics mode by CruelTott.
-Fixed "Cannot access the virtual memory card" issue for PSOne.

v1.3:
-Updated adrenaline version to v7.0.
-Added suspend threads option to adrenaline bubble menu.

Like my works, you can buy me a cup of coffee:
https://sites.google.com/site/theleecherman/donate

Homepage:
If you want to check for latest updates, plugins, tools: 
https://sites.google.com/site/theleecherman

Usage:
-Install Adrenaline v6.X and 661.PBP file if it is not already installed,
 then run it from the bubble and make sure it's working fine before doing anything.
*** THIS IS JUST ONE TIME UNLESS THERE IS A NEW UPDATED VERSION ***
-Copy 'AdrBubbleBooterInstaller.vpk' to your PSVita 'ux0:' then install and run it
 to install\update the required files for AdrBubbleBooter, after that remove it if you want.
-Reboot the PSVita for changes to take effect if it is not rebooted by the installer.
*** THIS IS FOR MAKING BUBBLE FOR EACH FILE ***
-Start AdrBubbleBooterCreator.exe and fill the required fields then press 'Create' button
 to create a VPK file for each file you want to direct boot it, after that copy the generated
 VPK file to your PSVita and install it.
*** THIS IS FOR CHANGING BOOT CONFIGS FOR THE BOOTED BUBBLE ***
-Start the PSVita and boot the created VPK bubble, open adrenaline menu and go to Booter tab
 then change the settings and exit the menu to save the configs.

Credits and special thanks to TheFloW.

Enjoy :)
