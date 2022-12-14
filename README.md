# BootVideoRandomizerForSteamDeck

## About
This repository contains the scripts and tools that I use to play a random video on boot up.
This is only applicable for Steam Deck running on Windows 10 / Windows 11.

## Pre-requisites - What is needed for this to run correctly?
Skip SWICD and Playnite if you have them installed already!
1. mpv - [click here for more details](https://mpv.io/). Download the Windows binary [here](https://sourceforge.net/projects/mpv-player-windows/files/)


## Optional Items -
1. ExplorerPatcher - [click here for more details](https://github.com/valinet/ExplorerPatcher). You will need this if you want the Taskbar to autohide so that it will be a seamless transition when playing the video.
2. Bat To Exe Converter - [click here for more details](https://www.f2ko.de/programme/bat-to-exe-converter/). Download [here](https://www.majorgeeks.com/files/details/bat_to_exe_converter.html). You will need this if you want to modify the batch file to your liking.
3. Windows 10 / Windows 11 Enterprise or Education - You will need this if you want to take advantage of Custom Login which supresses the "Welcome" message at startup.


## How to Use the Scripts
1. Download and extract the mpv archive in C:\mpv
2. Create a folder called videos located in C:\mpv\videos
3. Download your favorite boot screen videos from [steamdeckrepo](https://steamdeckrepo.com/) and save them in C:\mpv\videos
4. Edit install.bat and look for the heading initialize variables. Edit that to reflect the correct username / password that will be used for autologin.
5. Right-click the install.bat script and select Run-As Admin. This sets the needed registry entries and Windows features.
6. Confirm that this is how the directory structure looks like for C:\mpv
![image](https://user-images.githubusercontent.com/98122529/200135482-91019b4f-6fba-4bcc-8a04-9be160fe091d.png)
7. If everything looks good - reboot and enjoy the random boot video! 


## Optional - Autohide the taskbar
1. Install ExplorerPatcher.
2. Right click Taskbar and select Properties.
3. Put a check mark on Automatically Hide the Taskbar.
![image](https://user-images.githubusercontent.com/98122529/200134999-fe166b1d-b3d7-4256-a36a-45dea032596a.png)
