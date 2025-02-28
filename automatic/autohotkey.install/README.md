# <img src="https://cdn.jsdelivr.net/gh/chocolatey-community/chocolatey-packages-template@a29fa0531b6152c89cbad2843f0542102d85f375/icons/autohotkey.png" width="48" height="48"/> [autohotkey.install](https://chocolatey.org/packages/autohotkey.install)

AutoHotkey is a free, open source macro-creation and automation software utility that allows users to automate repetitive tasks. It is driven by a custom scripting language that is aimed specifically at providing keyboard shortcuts, otherwise known as hotkeys.

## Features

- Automate almost anything by sending keystrokes and mouse clicks
- Write a mouse or keyboard macro by hand or a macro recorder
- Remap keys and buttons on your keyboard, joystick, and mouse
- Create hotkeys for keyboard, joystick, and mouse
- Essentially any key, button or combination can become a hotkey
- Expand abbreviations as you type them
- Retrieve and change the clipboard's contents
- Convert any AHK script into an executable file that can be run on computers where AutoHotkey is not installed
- Create custom data-entry forms, user interfaces and menu bars
- Automate data entry jobs by reading data from text files, XML, CSV, Excel and various database formats
- Read signals from hand-held remote controls via the WinLIRC client script
- Supports Component Object Model (COM)
- Supports advanced programming constructs such as arrays, objects, hashtables, variadic functions etc.
- DLL calls and Windows Messages
- Perl Compatible Regular Expressions (PCRE)
- Interactive debugging features
- Much more ...

## Package Parameters

- `/DefaultVer` - Can be `U64` (UNICODE 64-bit),`U32` (UNICODE 32-bit) or `A32` (ANSI 32-bit). By default UNICODE version will be installed of adequate architecture depending on your machine and/or OS.

Example: `choco install autohotkey.install --params='/DefaultVer:A32'`
