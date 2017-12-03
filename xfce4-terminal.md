# xfce4 terminal

## Installation

    sudo apt install xfce4-terminal

## Set up hotkey for dropdown mode

Edit file: `~/.config/openbox/lubuntu-rc.xml` and set the hotkey (ex: `F1`) for dropdown mode:
```xml
<keybind key="F1">
  <action name="Execute">
    <command>xfce4-terminal --drop-down</command>
  </action>
</keybind>
```
