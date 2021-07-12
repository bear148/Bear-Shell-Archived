## What IS CMD-OS?
CMD-OS is a command-line based operating system developed by [Michael](https://github.com/BizzyPythonBear).

## Why should I use CMD-OS?
I do not expect CMD-OS to be used for real life applications, as it requires python 3 to be ran, and it's not like an ACTUAL OS, where it has assembly and runs independently. This can be ran as a hub to do all your things though. In the future, I will more than likely be adding things like running commands as root, cd'ing into directories, and lots more. As of right now, it basically has the bare minimum to be used as, technically an os. With the new addition of the ls, and pwd command, you can now navigate even inside of the terminal.

## Compatibility
As of now, CMD-OS is compatible with Windows and Linux. No plans have been made to make Macintosh compatibility.

## Prerequisites
To use CMD-OS, you'll need to install:
- Python 3.*
- Tkinter (pip3 install tk)
- Curses (Go to [here](https://www.lfd.uci.edu/~gohlke/pythonlibs/#curses) to install it.)
-	[This](https://stackoverflow.com/questions/32417379/what-is-needed-for-curses-in-python-3-4-on-windows7) goes into more depth on how to install it.
- 	If you are on linux, curses is included with python and wont need to be installed.

## Upcoming Ideas
I have many plans for this OS. Right now, the biggest thing is the cd command, as it will allow you to stay inside of the OS without having to leave to navigate to other folders.

Some other ideas:
- ~~Sudo~~
- Cosmetics
- Flavors?

By cosmetics I mean when typing a number in the menu for example, if the number is the same as one of the numbers on the screen, it will be green, but if it is one of the numbers that aren't listed in the menu, it will show as red.

By flavors I mean making new flavors of BearOS, like Ubuntu is a flavor of Debian, and such.

## Newest Updates
In the most recent update, version 1.2.8, I added the cd command.

- cd: Allows a user to access a directory from the terminal, for example, if a user was in their documents directory, they could cd into the desktop directory and access files inside of the desktop directory from the terminal.
- I added the current directory to the command prompt so you always know where you are.
- CD, LS, PWD, PYTHON3, commands will all work with windows. (Basically you are able to run the same commands on linux as you can in windows and they'd run the same)

I also found that sudo will not be needed. I was testing out cd'ing into directories like /usr/share and C:\Windows\System32 and everything worked fine. No permission errors, no nothing. Though, I believe if a user tries to save a file to a directory like one of those they will receive an error, because you need <u>write</u> permissions. I will work on this in the future though.

## Older Updates
- Ver 1.2.7
- Ver 1.2.6
- Ver 1.2.5
- Ver 1.2.4
- Ver 1.2.3
- Ver 1.2.2
- Ver 1.2.1
- Ver 0.2.1
- Ver 0.0.1

To see previous updates, you can go [here](https://github.com/BizzyPythonBear/CMD-OS/blob/main/prev.txt), or you can run the os and when in the menu, and go to the update log. (Hit 7 and then Enter)

## Current Commands 
The current commands that can be used in the included terminal are as listed:
- root
- python3
- ls (When the prompt asks for the directory you want to look through, you can type 'ls' to view the contents of the current directory)
- pwd
- clear
- exit
- userinfo
- cd

## Additional Resources Used:
(Text Editor, and Soon, Web Browser)
BorkUtils: Created by [Michael](https://github.com/BizzyPythonBear)

Everything else has been created by me, terminal, menu, etc.

## Guide for Developers
If you're a dev looking to play around with this the developer mode passwords are:
- 559907: Opens up to dev menu
- 559908: Goes right to dev console

## Extras
Disclaimer: Updates come out randomly and aren't scheduled.

Updates will also be a little slow, as I suck at organizing my code, so it takes a while for me to find code, update and change things, but I will definitely still be pushing updates out as fast as possible.

If you'd like to contact me, shoot me a DM on discord at ```MicBearr#5816```