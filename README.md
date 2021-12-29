# j2-Technologies
J2-Technologies is a by i3-Technologies inspired Whiteboard application programmed in lua (love2d) and is pending a rewrite in a different language because of love2d's slow refreshrate and program cycles. It aims to copy i3-Technologies product with the addition of extra functionality.

# Features
The current features and functionalities are:
- literally just writing. Single colored pen (white) on black background.

# How to use
There are a bunch of ways in which the program can be executed:
### Windows installer
Use .exe installer for **Windows only**. The "installer" (quotations intended) literally extracts the zip archive into a directory of your choice. For version "v0.2ALPHA" and "v0.2.1ALPHA" **make sure to create a subfolder** as the installer doesn't do that automatically. Otherwise you're gonna have to move all extracted files after the installation - it's a mess.
Now You should be able to open the program.
### Universal installation
Use .love file. For this You will need to install the love2d programming language first. Go to [love2d Homepage](https://love2d.org/) and install it for your operating system. After installing it You will be able to double-click the .love file
### Zip Archive
Download the latest source-code zip archive and extract it to a directory of your choice. Now You can open it.

# Updates
### What comes next?
Of course this is a wip (work in progress) and the project is still in its alpha stage but I have to work on other projects too so don't expect any updates soon
### Rewrite in different programming language
As mentioned above I will rewrite the program in a different programming language to be able to get more fps as when You draw a line in the latest release, the line is only dottet and not straight. The progarmming language has a refresh limit and even though fps are capped at 60, the refresh cycle isn't which doesn't allow me draw more points in the same amount of time.
