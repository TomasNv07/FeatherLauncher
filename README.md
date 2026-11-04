# Feather Player

Feather Player is a Windows desktop app for browsing and watching your personal video clips. It uses the mpv player for playback and runs quietly in the system tray when you close the window.


<img width="1161" height="701" alt="Feather Player main window" src="https://github.com/user-attachments/assets/11eb2f13-4c64-48c4-8468-8ebcf6d2908a" />


## Features

- Plays your video clips using mpv
- Runs in the system tray, so it stays out of your way
- Optional start with Windows
- Only one copy of the app runs at a time

## Download and install

1. Go to the [Releases](../../releases) page.
2. Download the latest `FeatherPlayer_Setup_1.0.0.exe` file from the Assets section.
3. Run the installer and follow the steps.
4. Start Feather Player from the Start menu.

By default the app installs for your user account only, so it does not need administrator rights. During setup you can choose to create a desktop shortcut.

## Requirements

- Windows 10 or Windows 11, 64-bit
- No other software needs to be installed. The mpv player is included.

## Windows SmartScreen warning

The installer is not code-signed, so Windows may show a "Windows protected your PC" message the first time you run it. This is normal for small independent projects. To continue, click "More info", then "Run anyway".

If you prefer, you can check the file with your antivirus before running it.

## Updating

Download the newer installer from the Releases page and run it. It installs over the old version and closes the running copy if needed. If you are coming from FeatherLauncher, install over it the same way. Your settings and clip data are carried over.

## Uninstalling

Open Windows Settings, go to Apps, find Feather Player, and choose Uninstall.

## Feedback and bugs

Found a problem or have an idea? Open an issue on the [Issues](../../issues) tab and describe what happened and what version you are using.

## Credits

- [mpv](https://mpv.io) is used for video playback and is included with the installer. mpv is a separate project with its own license. See the mpv website for details.

## License

See the [LICENSE](LICENSE) file for terms.
