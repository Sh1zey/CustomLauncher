# Sh1zeyLauncher Script

I created the Sh1zeyLauncher application to be used in conjunction with this script, providing a streamlined way to start your stream with a single click.

## Example Script

@echo off

cd "C:\Program Files\obs-studio\bin\64bit" 

start obs64.exe

cd "C:\Users\Sh1zey\Streamer.bot-x64-0.2.2" 

start Streamer.bot.exe

cd "C:\Users\Sh1zey\Sh1zeyLauncher" 

start Sh1zeyLauncher.exe

start "" https://dashboard.twitch.tv/u/thewolfa/stream-manager

exit


# CustomLauncher
Game Selector

## Overview

This program allows users to select and launch games for streaming purposes.
It provides a simple graphical interface where users can choose from a list of available games and launch them with a click of a button.
Additionally, users can add new games to the list along with their executable paths or shortcuts.

## Features

- **Game Selection**: Users can choose from a dropdown menu containing available games.
- **Add New Game**: Users can add new games to the list along with their executable paths or shortcuts.
- **Launch Game**: Users can launch the selected game with a click of a button.
- **Persistent Storage**: The program stores the list of games and their paths in a text file, allowing for persistence across sessions.

## Installation

No installation is required. Simply run the program executable to launch the application.
Recommended: Run it with the script.

## Usage

1. Launch the program.
2. Choose a game from the dropdown menu.
3. Click the "Play!" button to launch the selected game.
4. To add a new game, click the "Add Game" button and follow the prompts to enter the game title and select its executable file or shortcut.
5. Close the program when finished.

## Dependencies

- **IWshRuntimeLibrary**: This library is used for creating and manipulating Windows shell shortcuts.
- **System.Windows.Forms**: This namespace provides classes for creating Windows-based applications that take full advantage of the rich user interface features available in the Windows operating system.

## Contributing

Contributions to this project are welcome. If you encounter any issues or have suggestions for improvements, please submit a pull request or open an issue on the GitHub repository.

## License

This program is licensed under the [MIT License](https://opensource.org/licenses/MIT).

