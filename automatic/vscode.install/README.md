# <img src="https://cdn.jsdelivr.net/gh/chocolatey-community/chocolatey-packages-template@a29fa0531b6152c89cbad2843f0542102d85f375/icons/vscode.png" width="48" height="48"/> [vscode.install](https://chocolatey.org/packages/vscode)

Build and debug modern web and cloud applications. Code is free and available on your favorite platform - Linux, Mac OSX, and Windows.

## Features

* **Meet IntelliSense:** Go beyond syntax highlighting and autocomplete with IntelliSense, which provides smart completions based on variable types, function definitions, and imported modules.
* **Print statement debugging is a thing of the past:** Debug code right from the editor. Launch or attach to your running apps and debug with break points, call stacks, and an interactive console.
* **Git commands built-in:** Working with Git has never been easier. Review diffs, stage files, and make commits right from the editor. Push and pull from any hosted Git service.
* **Extensible and customizable:** Want even more features? Install extensions to add new languages, themes, debuggers, and to connect to additional services. Extensions run in separate processes, ensuring they won't slow down your editor.

## Package parameters

* `/NoDesktopIcon` - Don't add a desktop icon.
* `/NoQuicklaunchIcon` - Don't add an icon to the QuickLaunch area.
* `/NoContextMenuFiles` - Don't add an _Open with Code_ entry to the context menu for files.
* `/NoContextMenuFolders` - Dont't add an _Open with Code_ entry to the context menu for folders.
* `/DontAssociateWithFiles` - Dont't associate Visual Studio Code with supported files.
* `/DontAddToPath` - Don't add Visual Studio Code to the system PATH.

Example: `choco install vscode.install --params "/NoDesktopIcon /DontAddToPath"`

## Notes

* The package uses default install options except that it adds context menu entries and Visual Studio Code isn't started after installation.
* For disabling the auto-update functionality see the [Visual Studio Code Auto Update Deactivation package](https://chocolatey.org/packages/visualstudiocode-disableautoupdate).

![screenshot](https://cdn.jsdelivr.net/gh/chocolatey-community/chocolatey-coreteampackages@6dc510f16b69a2134e901f2576e991c462a18e9b/automatic/vscode/screenshot.png)
