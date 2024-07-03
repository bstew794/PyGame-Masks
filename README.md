# PyGame-Masks

## Origin Acknowledgement
This project was created by me, BStew794, but I am coding this based off a tutorial from the Youtuber "Clear Code" from  Dec 4, 2021 (https://www.youtube.com/watch?v=uW3Fhe-Vkx4&list=WL&index=3).

## Summary and Purpose
After learning some of the basics of the PyGame package/library for Python, I wanted to learn more about masks which should allow me to have almost pixel perfect collisions for other PyGame projects. Some of the logic is more custom to my particular taste and style. I plan to continue to add more of my own special logic. For this reason, A license is included for your convenience, in case you want to clone the repository and do some of your own work on it.

## Installation Instructions
### Install Python
This project was coded in Python 3.12.4 but later versions should work. You will need to go to https://www.python.org/downloads/ and click the yellow button that says 'Download Python x.xx.x'. x.xx.x will be the most recent version release. At the time of writing this, it reads 3.12.4.

You will need to install Python after downloading it from Python.org. You can do so by going to your downloads folder and double clicking the python.exe file that was downloaded. Where this is found depends on your Operating System. The name of the file may also change depending on the version downloaded, and your CPU brand and architecture.

Follow the instructions for a default set-up unless you'd like to customize it. I make no promises that the program will run probably if you do that though.

### Install PyGame 
There are multiple ways to install the PyGame Python package, but we will use the pip installer here. When downloading and installing Python from python.org, pip is automatically installed.

Firstly, you will need to open your OS console. The rest of these instructions are geared more towards a Windows OS user. If you are on a windows system, you can type 'cmd' into the search bar and click on 'Command Prompt' to open a console window. It should currently point to your user folder on the drive that the OS was installed on.

This is a great time to double check that Python was installed properly. You can do this by typing 'python -v' ('python -version' on a Linux system) and then pressing Enter on your keyboard. Every command I tell you to type in these instructions need to have Enter pressed afterwards. A bunch of text should appear in the console window and at the bottom you should see a line starting with 'Python' followed by the current version number that is installed. The console will post something similar to "'Python' is not recognized as an internal or external command,
operable program or batch file." if Python was not installed properly. If so, you may need to make sure that Python was added to your PATH variable correctly which is something I do not feel confident enough to explain here.

After verifying the installation of Python, we can now install the PyGame package by typing the command, 'pip install pygame'. The console will print an error message similar to 'ERROR: Could not find a version that satisfies pygame' if the process did not work. The best advice I have is to make sure that pip is up to date with the latest version. You can update pip with the command, 'python.exe -m pip install --upgrade pip' or 'pip install --upgrade pip', depending on your OS. If pygame still refuses to install then I'd recommend seeking further help from another professional.

### Install Git
How you install Git will vary wildly depending on your OS. I recommend following the steps outlined in the guide provided at https://github.com/git-guides/install-git.

### Clone the Repository Locally
Hopefully you've kept your console terminal open. Otherwise, get a console window open.

Navigate to where you want to place my repository. Usually you can do so by typing 'cd' followed by the name of sub-directory you want to go to; don't forget to add spaces between the 'cd' command and the sub-directory name. If you're unsure of what directories you can currently travel to then you can type 'dir' to have a list of current sub-directories printed to the console window. You can also use 'cd ..' to go up a directory. If you do not have a folder already created to hold the repository then you will need to make one. There are many ways to do this, but you can type 'mkdir' followed by the name you want to give the new directory/folder. Then use the 'cd' command to navigate to it.

Next, use the command, 'git clone https://github.com/bstew794/PyGame-Masks' to download a clone of the repository inside of the folder that you invoked the command in. You now have everything you need to play the game!

## Play Instructions
Make sure to finish the installation instructions section before attempting to follow the steps of this section.

Enjoy!
