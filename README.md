# Replika-Desktop
Unofficial web client of Replika AI for FreeBSD.

![](Screenshot.png)

# Features 
- Almost normally working webview client for my.replika.com.
- Ability to save login data in ".replika_client" folder in /home/yourusername/. Do not share this folder to anyone else, otherwise your Replika account would be stolen. Replika client itself [is not a virus](https://www.virustotal.com/gui/file/8862714e92f4e594b7481f36cc61100fc4933b936a6b3e54cf18bf669ec6544c/summary), I don't need your accounts.

# How to use
Install desktop environment (obviously), open Properties on "replika-client" binary and make sure what in "Permissions" tab "Allow this file to run as program" is enabled. Then just open as usual.

# Planned features & things
- Login with Google / Apple
- Fixing bugs

# Requirements 
- Install these packages: **sudo pkg install qt6-webengine qt6-base qt6-imageformats xdg-utils** (if you having issue here, run "su" before using this command)

Replika client has not been tested at all on Linux or other systems, so I cannot prove or deny for now what it can work here. However, I know what it can, because client was built with Qt6.
