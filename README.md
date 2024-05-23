# Holoearth Beta lutris installer
This lutris installer file is for Holoearth beta, which is developed by COVER corp and provides a platform for all the 
Hololive fans. With this script, you can run Holoearth beta under linux using the wine manager lutris.


This lutris installer is the first one that I wrote, so please let me know any improvements. 


Here are some points that I still struggle with:

- Firefox
	- Using firefox-esr and [placing ucrtbase.dll into it's installation directory with a wine override](https://appdb.winehq.org/objectManager.php?sClass=version&iId=41500#testdata), it won't crash anymore.
	- **BUT** Somehow when opening a new profile, it will crash, so you have to let it start once, have it crash and then you can use it without any problems
- Fonts in the installer
	- Even with cjkfonts and fakejapanese, blank squares will show up during the installer process
- Holoearth
	- performance is not great and could also crash randomly
	- find a way to enable english from a config file or something like that maybe? 
- Documentation
	- I plan to include a tutorial on how to navigate holoearth installation and first launch until the settings... maybe? 

