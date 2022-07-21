# 🎬 CraftCtl

> ❗️ **Note:** This project is currently **incomplete**.

A collection of scripts to aid in managing your Minecraft servers and proxies.

## Showcase

To-do. :)

Check out [cli.md][6] to see what the script's interface will look like!

## Features Overview

### 🔧 Configurable

The script has a dedicated configuration area at the top where you can easily customize the various features.

In addition, you are free to modify the code beneath it to extend the script to your liking.

### 📺 Main Menu

The script has a 'Main Menu' area where you can run various tools. It's also very easy for you to add your own
tools in if you wish to do so.

### 🏁 Aikar's Flags

[Aikar][5] has poured research into finding a [brilliant set of launch flags][4].
I have added Aikar's flags into the script. The script will utilize different flags depending upon how you have
configured it: a configuration which allocates 12GB+ of memory will utilize Aikar's alternate 'high-memory' flags.

### 📥 Auto-Updater

If you've got [MCServerUpdater][1] installed alongside the script (in the same directory), the script will run it
(configurable, toggleable, etc.) so that your server software can stay up-to-date whenever you choose to restart it.

### ♻️ Auto-Restart

The script features auto-restarting, which has a countdown delay so that you have plenty of time to
exit the script in case you intended on shutting the server down without restarting it shortly thereafter.

### 🏷 (Windows) Server Name as Title
The script sets the command prompt window title to the name of the server instance.
The purpose of this is so you can immediately see which command prompt represents which server, brilliant for when 
you're running multiple instances (such as a Minecraft server network).

## 📜 Instructions

Clone this repository using `git clone`, or 'Download ZIP' from the GitHub repository.

### GNU/Linux Systems

> A very basic understanding of using your OS's terminal is assumed. 

- Clone the repository: `git clone https://github.com/lokka30/CraftCtl`
- Copy `ctl.sh` from `CraftCtl/scripts/bash/` into your server's directory
- Delete the downloaded `CraftCtl` directory if you wish, it's no longer required
- Set execute permission: `sudo chmod +x ctl.command && sudo chmod +x ctl.sh`

### macOS Systems

> A very basic understanding of using your OS's terminal is assumed.

- Clone the repository: `git clone https://github.com/lokka30/CraftCtl`
- Copy `ctl.command` **and** `ctl.sh` from `CraftCtl/scripts/bash/` into your server's directory
- Delete the downloaded `CraftCtl` directory if you wish, it's no longer required
- Set execute permission: `sudo chmod +x ctl.command && sudo chmod +x ctl.sh`

### Windows Systems

- Hit the "Download ZIP" button in the source code area on this GitHub repository.
- Extract the downloaded ZIP file.
- Copy `ctl.bat` from `CraftCtl/scripts/batch/` into your server's directory
- Delete the extracted `CraftCtl` directory if you wish, it's no longer required

## Support

No support is provided for this software. However, bug reports and feature requests are warmly welcome. For this,
feel free to use the [issue tracker][2], or the [ArcanePlugins Discord Guild][3].

## License

This software uses the MIT License - see `LICENSE.md`.



[1]: https://www.spigotmc.org/resources/mcserverupdater.98003/updates
[2]: https://github.com/lokka30/CraftCtl/issues
[3]: https://discord.io/arcaneplugins
[4]: https://aikar.co/mcflags.html
[5]: https://aikar.co/
[6]: https://github.com/lokka30/CraftCtl/blob/master/misc/brainstorming/cli.md
