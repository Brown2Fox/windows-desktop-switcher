# Windows Desktop Switcher
An AutoHotKey script for Windows that lets a user manage (switch, create, delete, review) a virtual desktops with one hand. This script creates 'better' hotkeys for switching virtual desktops in windows 10.

### Quick note
If you're looking for something more robust & need more than this script, check out:
https://github.com/sdias/win-10-virtual-desktop-enhancer

## NOTE 
Note that this overrides CapsLock for the key combinations below. CapsLock will be disabled.

## Installation
Install AutoHotKey, then run the desktop_switcher.ahk script (open with AutoHotKey if prompted). I would recommend putting it in your startup folder and it'll be invoked on login. 

If you don't want install AutoHotKey, you can run executable [file](https://github.com/Brown2Fox/windows-desktop-switcher/releases) directly. You can also put it in startup folder for automatically starting.

## Hotkeys
        <CapsLock> + <Num>      - Switches to virtual desktop "num"
        <CapsLock> + C          - Create a new virtual desktop
        <CapsLock> + D          - Delete the current virtual desktop
        <CapsLock> + A or P     - Switch to virtual desktop on left
        <CapsLock> + S or N     - Switch to virtual desktop on right
        <CapsLock> + <Tab>      - Shows up desktops overview

To change the key mappings, modify the bottom of the script and reload. Be sure to read about the [symbols AutoHotKey uses](https://autohotkey.com/docs/Hotkeys.htm) for key mapping.

