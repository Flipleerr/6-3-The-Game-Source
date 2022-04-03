# 6/3 The Game

This is the source code for 6/3 The Game, which is currently in development. 
This game is written in Python and is designed for Windows computers.
Please refer to this README guide to navigate through branches, find out how to compile from source, and get info about the engine the game is running on.

# Compilation Guide
To compile the game, you have to have the following Pyhton packages:

- Pygame
- Pyinstaller
- A Windows, Mac or Linux system

With that in mind, this is the compilation process.

# Windows

To compile the game, you will need Visual Studio Code. Download VS Code from https://code.visualstudio.com/.
Compile this the same way you would do with any other Python application through the terminal.
Once compiled, zip the folder that the .exe file is contained in, and you're free to distribute!

# macOS

Because of the way that Pyinstaller works, to compile a version, for say, Windows, you'll need a Windows system to compile, for well, Windows! (that's a lot of Windows)
Same logic applies for macOS. Again, compile the app through the terminal, zip the .app file and you're ready to go!

# Linux

Once again, download VS Code, use Pyinstaller, compile, zip and you're done!

# Branch navigation

Due to the game being actvively in development, the Source Code will be split into a few branches:
- Master (definitive, all important and big changes will be merged into this branch)
- Dev (Almost done, may encounter bugs, compile at your own risk. Will be more frequently updated than master branch)
- Experimental (extremely buggy, early in development, DO NOT COMPILE AS THE RELEASE CAN BE UNSTABLE!!!)

For now: that's all you need to know about the rep branches.

# Flexible Python Platformer Engine

Flexible Python Platformer Engine (acronymed as FPPE, pronounced _f-pee_) is the engine that the game runs on.
It's being developed alongside the game, and will be seperated into its own project within the reopsitory.
The engine is designed to be modular, accesible and easy to use, while being versatile, making it perfect for multiple uses with just minor changes to the code.
It is still very unfinished and for now will ship into the experimental branch until it's possible to seperate into two projects.
