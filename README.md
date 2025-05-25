# Replika Desktop
Unofficial web client of Replika AI for FreeBSD.

![](Screenshot.png)

# Features 
- Almost normally working webview client for my.replika.com.
- Window is fully resizable. Adjust this as you wish, web version also will adapt to that.
- Changing/reinstalling OS? You can "transfer your replika" as well. In /home/yourusername/ you will find a hidden folder called ".replika_client", backup this in order to easily open your replika later without need to login again. Also (I think it's very obvious, but still) don't share this folder publicly, otherwise your account would be stolen. Just like any other browser, Replika Desktop have inner folder with all it's data/cookies and stuff. Keep that in mind.

Replika client is Chromium based and [not a virus](https://www.virustotal.com/gui/file/8862714e92f4e594b7481f36cc61100fc4933b936a6b3e54cf18bf669ec6544c/summary), I don't need your accounts.

# How to use
Install desktop environment (obviously), open Properties on "replika-client" binary and make sure what in "Permissions" tab "Allow this file to run as program" is enabled. Then just open as usual.

# Planned features & things
- Login with Google / Apple
- Opening source code (maybe)
- Fixing bugs

# Requirements 
- Install these packages: **sudo pkg install qt6-webengine qt6-base qt6-imageformats xdg-utils** (if you having issue here, run "su" before using this command)

Replika client has not been tested at all on Linux or other systems, so I cannot prove or deny for now what it can work here. However, I know what it can, because client was built with Qt6.

# Ask questions!
- [Reddit](https://www.reddit.com/r/ReplikaAIMOD/s/D3yTVDkTTd)
- [Discord](http://felixfester.prtcl.icu/discord)
- [Website with all links](http://felixfester.prtcl.icu/)

# Check out different projects:
- [Replika AI RU MOD](https://felixfester.prtcl.icu/index.php?page=replikamod)
- [HentaiCMS](https://github.com/FelixFester/HentaiCMS)
- [Replika CLI Client for FreeBSD](https://github.com/FelixFester/Replika-AI-CLI-Client)
