# j2-Technologies
J2-Technologies is a by i3-Technologies inspired Whiteboard application programmed in lua (love2d) and is pending a rewrite in a different language because of love2d's slow refreshrate and program cycles. It aims to copy i3-Technologies product with the addition of extra functionality.

# Features
The current features and functionalities are:
- literally just writing. Single colored pen (white) on black background.

# Installation
There are a bunch of ways in which the program can be executed:
### Windows installer
Use .exe installer for **Windows only**. The "installer" (quotations intended) literally extracts the zip archive into a directory of your choice. For version "v0.2ALPHA" and "v0.2.1ALPHA" **make sure to create a subfolder** as the installer doesn't do that automatically. Otherwise you're gonna have to move all extracted files after the installation - it's a mess.
Now You should be able to open the program.
### Universal installation
Use .love file. For this You will need to install the love2d programming language first. Go to [love2d Homepage](https://love2d.org/) and install it for your operating system. After installing it You will be able to double-click the .love file
### Zip Archive
Download the latest source-code zip archive and extract it to a directory of your choice. Now You can open it.

# How to use
You will be greeted with the following start screen:
![image](https://user-images.githubusercontent.com/91549607/147693647-95d5c063-f56c-45c5-a768-d5c24034fdf7.png)
Just wait a few seconds and the whiteboard (or blackboard) will appear.
The whiteboard looks as followed:
![image](https://user-images.githubusercontent.com/91549607/147693340-e14e65c6-b4a7-4325-93aa-2896694a29cf.png)
Here You can draw in white wuth your mouse or any digital pen, finger, etc.

# Updates
### What comes next?
Of course this is a wip (work in progress) and the project is still in its alpha stage but I have to work on other projects too so don't expect any updates soon
### Rewrite in different programming language
As mentioned above I will rewrite the program in a different programming language to be able to get more fps as when You draw a line in the latest release, the line is only dottet and not straight. The progarmming language has a refresh limit and even though fps are capped at 60, the refresh cycle isn't which doesn't allow me draw more points in the same amount of time.
