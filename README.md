# Holoearth Beta lutris installer
This lutris installer file is for Holoearth beta, which is developed by COVER corp and provides a platform for all the 
Hololive fans. With this script, you can run Holoearth beta under linux using the wine manager lutris.


This lutris installer is the first one that I wrote, so please let me know any improvements. 


Here are some points that I still struggle with:
- Under Wayland (atleast for me with KDE Plasma), the Holoearth Launcher will just be a black window.
	- Starting Lutris with `PROTON_USE_WINED3D=1 lutris` works.
	- After the Holoearth Launcher installed the base game, you will need to restart lutris once the Holoearth Launcher installs the base game without PROTON_USE_WINED3D, so just normally to get the game working
- winetricks does not work with GE-Proton9-15 and I don't really know what to do with this.

