# Unity Cursor Integration

This package is a modified version of Unity's [VS Code package](https://github.com/Unity-Technologies/com.unity.ide.vscode) that enables using [Cursor](https://cursor.com) as an IDE for Unity development.

## Disclaimer

This package is not officially affiliated with Unity Technologies or Anysphere (Cursor). It is a modification of Unity's VS Code integration package to support Cursor as an alternative IDE.

## Features

- Enables Cursor as a Unity IDE
- Maintains compatibility with Cursor's debugging features

## Requirements

- Unity 2019.4 or newer (Technically, it has been tested on 2019.4.40 and on Unity 6000.0.47)
- Cursor IDE 

## Installation

1. Install Cursor IDE from [cursor.com](https://cursor.com)
2. Install required Cursor extensions:
   - C#
   - C# Dev Kit 
   - Unity

3. Add this package to your Unity project:
   - Via Package Manager: Add package from git URL
   - Use URL: `https://github.com/pulni4kiya/unity-cursor-ide.git`

4. In Unity, go to Edit > Preferences > External Tools
   - Select 'Cursor' as External Script Editor

5. First time setup:
   - You may need to regenerate project files (via Preferences > External Tools)
   - Wait for Cursor to finish loading C#/.NET packages on first use
   - IntelliSense and code completion will be fully functional after initial load

## Random Notes

- You may read more about Cursor's features on [Cursor's website](https://cursor.com/), but the main ones are:
    - Use the right side panel to write code requests, which helps create initial implementations
    - Select any code and press Ctrl+K to ask for specific modifications
    - Get helpful code suggestions that you can quickly accept with Tab
- You can add Cursor rules via Settings > Rules to specify your coding style and preferences
- You may want to exclude meta and asset files from Cursor indexing via File > Preferences > VS Code Settings > Search for Files: Exclude


