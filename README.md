# change-primary-screen
An executable for Windows to change the primary screen some games do not have the support for changing screens this exe will change the primary screen so you can play on the other screen.
# How To Use
Just Download [ChangePrimaryScreen.exe](ChangePrimaryScreen.exe) and run the exe, you can save it in C:\Program Files (x86)\ChangePrimaryScreen to keep things tidy.

it is recommended to create a shortcut for the exe to change screen while you are in the game.

this tool works by changing the primary screen to the next available screen and if the max is reached it will round robbin, example if your main screen is 1 then 2 will be the main screen if you run again your primary will be 1, and so on, this tool is most suited for dual screens but you can use it for more than 2 screens you just have to run the command more than once.

# Files Structure
[source](source) has the source files the exe was made with.
[ChangePrimaryScreen.exe](ChangePrimaryScreen.exe) is the exe that runs the command.

# Tools 
The script uses [MultMonitorTool](https://www.nirsoft.net/utils/multi_monitor_tool.html) which is a tool to manipulate and reconfigure multiple screen setups the bat file uses the /SetNextPrimary to change the primary screen to the next available screen.
