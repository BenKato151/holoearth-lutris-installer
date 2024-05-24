# Holoearth Beta lutris installer
This lutris installer file is for Holoearth beta, which is developed by COVER corp and provides a platform for all the 
Hololive fans. With this script, you can run Holoearth beta under linux using the wine manager lutris.


This lutris installer is the first one that I wrote, so please let me know any improvements. 


Here are some points that I still struggle with:

- Firefox
	- Using firefox-esr and installing ucrtbase2019 with winetricks, it won't crash anymore.
	- **BUT** Somehow when opening a new profile, it will crash, so you have to let it start once, have it crash and then you can use it without any problems.
  		That's why I suggest to launch firefox once after installation.
- Fonts in the installer. 
	- Even with cjkfonts and fakejapanese, blank squares will show up during the installer process
- Holoearth
	- performance is not great and could also crash randomly. Disabling Motion Blur and Cast Shadows seems to improve this
	- english at boot: Success, but I am not really happy that I had to edit hex values for it xD If someone finds a better way to do that, pls let me know! :)
- Documentation
	- I plan to include a tutorial on how to navigate holoearth installation and first launch until the settings... maybe? 


Some of the steps that I have written in here, do come from [this reddit comment](https://www.reddit.com/r/Hololive/comments/14rznad/comment/jqwtwm1/) a few months ago, where we did some first steps into getting holoearth working on linux.
Since the newest update, I got back into it and wanted to automate the installation process a bit xD
