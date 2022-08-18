# About
This repository contains custom commands regarding different topics (e.g. Git commands or networking commands).

The commands are meant to simplify 

Commands are made for __windows__. Will not work on Linux or MacOS. If you want to make this work for Linux and/or MacOS, you can use the existing commands as a base and rewrite them to Linux syntax.

# Getting started
Before you can make use of the commands, you need to add something in your windows configuration. You need to assign a directory (or multiple if you want) where windows can recognize these commands. Follow the following steps to let windows know where your custom commands are stored:
1:
2:
3:
4:

__This will make the specified directory the place where the .bat-files can be stored to be executed in the command line. You can copy paste all commands you want in this directory. You can also do this step for each directory where you want to store custom commands. There are no limitations in the amount of directories you can specify.__

# Available commands

## Git Commands

### gityolo
```
gityolo
```
Appends all current changes to the last commit you did. Convenient when you made some changes that should have been in the previous commit. 

## Networking Commands

### killprocess <port_number>
```
killprocess 7071
```
Kills the process on the specified port.