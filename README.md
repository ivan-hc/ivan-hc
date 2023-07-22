*My name is Ivan, I'm italian and I like to play with Portable Linux Apps, in particular AppImage packages.*

-------------------------------------------------------

[Main projects](#main-projects)

[Creating AppImage packages](#creating-appimage-packages)
- [My Tools](#my-tools)
- [My AppImage packages](#my-appimage-packages)

[Scripts and utilities](#scripts-and-utilities)

[Side projects](#side-projects)

-------------------------------------------------------

## Main projects

*I wrote two bash scripts to install and manage the applications: [AM](https://github.com/ivan-hc/AM-Application-Manager) and [AppMan](https://github.com/ivan-hc/AppMan). Their dual existence is based on the needs of the end user.*

| [**"AM" Application Manager**](https://github.com/ivan-hc/AM-Application-Manager) |
| -- |
| <sub>***If you want to install system-wide applications on your GNU/Linux distribution in a way that is compatible with [Linux Standard Base](https://refspecs.linuxfoundation.org/lsb.shtml) (all third-party apps must be installed in dedicated directories under `/opt` and their launchers and binaries in `/usr/local/*` ...), just use ["AM" Application Manager](https://github.com/ivan-hc/AM-Application-Manager). This app manager requires root privileges only to install / remove applications, the main advantage of this type of installation is that the same applications will be available to all users of the system.***</sub>
[![Readme](https://img.shields.io/github/stars/ivan-hc/AM-Application-Manager?label=%E2%AD%90&style=for-the-badge)](https://github.com/ivan-hc/AM-Application-Manager/stargazers) [![Readme](https://img.shields.io/github/license/ivan-hc/AM-Application-Manager?label=&style=for-the-badge)](https://github.com/ivan-hc/AM-Application-Manager/blob/main/LICENSE)

| [**"AppMan"**](https://github.com/ivan-hc/AppMan)
| --
| <sub>***If you don't want to put your app manager in a specific path but want to use it portable and want to install / update / manage all your apps locally, download ["AppMan"](https://github.com/ivan-hc/AppMan) instead. With this script you will be able to decide where to install your applications (at the expense of a greater consumption of resources if the system is used by more users). AppMan is portable, all you have to do is write the name of a folder in your `$HOME` where you can install all the applications available in [the "AM" database](https://github.com/ivan-hc/AM-Application-Manager/tree/main/programs), and without root privileges.***</sub>
[![Readme](https://img.shields.io/github/stars/ivan-hc/AppMan?label=%E2%AD%90&style=for-the-badge)](https://github.com/ivan-hc/AppMan/stargazers) [![Readme](https://img.shields.io/github/license/ivan-hc/AppMan?label=&style=for-the-badge)](https://github.com/ivan-hc/AppMan/blob/main/LICENSE)

-------------------------------------------------------

## Creating AppImage packages
*Sometimes my Appimage packages are built from a base of precompiled packages, whether they are in .deb or .tar format it doesn't matter, as long as they know how to work by themselves.* 

*Unfortunately it's not always that simple, so we need to download more dependencies from external packages.*

-------------------------------------------------------

#### My Tools
*When a program requires multiple external libraries to work, I use two tools to generate my AppImage packages: AppImagen and ArchImage!*

| Tool | What it does | Stars |
| -- | -- | -- |
| [**AppImaGen**](https://github.com/ivan-hc/AppImaGen) | ***<sub>This is a script that builds AppImages from Ubuntu PPAs or Debian repositories. The final packages are GLIBC compatible for the chosen Debian release or the previous (not the latest, not the oldest) Ubuntu LTS.<sub>*** | ![](https://img.shields.io/github/stars/ivan-hc/AppImaGen?label=%E2%AD%90&style=for-the-badge)
| [**ArchImage**](https://github.com/ivan-hc/ArchImage) | ***<sub>This is another script that builds a kind of AppImages I've named "ArchImage", being them built on top of "[JuNest](https://github.com/fsquillace/junest)", the lightweight Arch Linux based distro that runs, without root privileges, on top of any other Linux distro. In this way the final package is compatible with all the GNU/Linux distributions.<sub>*** | ![](https://img.shields.io/github/stars/ivan-hc/ArchImage?label=%E2%AD%90&style=for-the-badge)

-------------------------------------------------------

#### My AppImage packages
*This is the list of all AppImage packages I build in my repositories for both "AM" and "AppMan".*

| Application | Source / Based on... | Stars |
| -- | -- | -- |
| [*Abiword*](https://github.com/ivan-hc/Abiword-appimage) | *JuNest, Arch Linux (ArchImage)* | ![](https://img.shields.io/github/stars/ivan-hc/Abiword-appimage?label=%E2%AD%90&style=for-the-badge)
| [*AnyDesk*](https://github.com/ivan-hc/Anydesk-appimage) | *Official .deb package* | ![](https://img.shields.io/github/stars/ivan-hc/Anydesk-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Asunder*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/asunder) | *Debian (Oldstable)* | ![](https://img.shields.io/github/stars/ivan-hc/Database-of-pkg2appimaged-packages?label=%E2%AD%90&style=for-the-badge)
| [*Audacious*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/audacious) | *Ubuntu (PPA)* | ![](https://img.shields.io/github/stars/ivan-hc/Database-of-pkg2appimaged-packages?label=%E2%AD%90&style=for-the-badge)
| [*Avidemux*](https://github.com/ivan-hc/Avidemux-unofficial-appimage) | *Debian (Testing, "deb-multimedia")* | ![](https://img.shields.io/github/stars/ivan-hc/Avidemux-unofficial-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Billard GL*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/billard-gl) | *Debian (Stable)* | ![](https://img.shields.io/github/stars/ivan-hc/Database-of-pkg2appimaged-packages?label=%E2%AD%90&style=for-the-badge)
| [*CAP Battleship*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/capbattleship) | *Official .deb package* | ![](https://img.shields.io/github/stars/ivan-hc/Database-of-pkg2appimaged-packages?label=%E2%AD%90&style=for-the-badge)
| [*Celestia*](https://github.com/ivan-hc/Celestia-appimage) | *AppImage, improved version* | ![](https://img.shields.io/github/stars/ivan-hc/Celestia-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Chrome Stable/Beta/Unstable*](https://github.com/ivan-hc/Chrome-appimage) | *Official .deb packages* | ![](https://img.shields.io/github/stars/ivan-hc/Chrome-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Chromium BSU*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/chromium-bsu) | *Debian (Stable)* | ![](https://img.shields.io/github/stars/ivan-hc/Database-of-pkg2appimaged-packages?label=%E2%AD%90&style=for-the-badge)
| [*Chromium*](https://github.com/ivan-hc/Chromium-Web-Browser-appimage) | *Debian (Oldstable)* | ![](https://img.shields.io/github/stars/ivan-hc/Chromium-Web-Browser-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Dropbox*](https://github.com/ivan-hc/Dropbox-appimage) | *Standalone build for GNU/Linux* | ![](https://img.shields.io/github/stars/ivan-hc/Dropbox-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Emacs*](https://github.com/ivan-hc/Emacs-appimage) | *Ubuntu (PPA)* | ![](https://img.shields.io/github/stars/ivan-hc/Emacs-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Extreme Tux Racer*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/extremetuxracer) | *Debian (Stable)* | ![](https://img.shields.io/github/stars/ivan-hc/Database-of-pkg2appimaged-packages?label=%E2%AD%90&style=for-the-badge)
| [*Gnumeric*](https://github.com/ivan-hc/Gnumeric-appimage) | *JuNest, Arch Linux (ArchImage)* | ![](https://img.shields.io/github/stars/ivan-hc/Gnumeric-appimage?label=%E2%AD%90&style=for-the-badge)
| [*GIMP Stable/Developer*](https://github.com/ivan-hc/GIMP-appimage) | *JuNest, Arch Linux (ArchImage)* | ![](https://img.shields.io/github/stars/ivan-hc/GIMP-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Handbrake*](https://github.com/ivan-hc/Handbrake-appimage) | *JuNest, Arch Linux (ArchImage)* | ![](https://img.shields.io/github/stars/ivan-hc/Handbrake-appimage?label=%E2%AD%90&style=for-the-badge)
| [*KDE-games*](https://github.com/ivan-hc/KDE-games-suite-appimage) | *Debian (Stable)* | ![](https://img.shields.io/github/stars/ivan-hc/KDE-games-suite-appimage?label=%E2%AD%90&style=for-the-badge)
| [*KDE-utils*](https://github.com/ivan-hc/KDE-utils-appimage) | *Debian (Stable)* | ![](https://img.shields.io/github/stars/ivan-hc/KDE-utils-appimage?label=%E2%AD%90&style=for-the-badge)
| [*kwave*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/kwave) | *Debian (Stable)* | ![](https://img.shields.io/github/stars/ivan-hc/Database-of-pkg2appimaged-packages?label=%E2%AD%90&style=for-the-badge)
| [*lxtask*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/lxtask) | *Debian (Oldstable)* | ![](https://img.shields.io/github/stars/ivan-hc/Database-of-pkg2appimaged-packages?label=%E2%AD%90&style=for-the-badge)
| [*Microsoft Edge Stable/Beta/Dev*](https://github.com/ivan-hc/MS-Edge-appimage) | *Official .deb packages* | ![](https://img.shields.io/github/stars/ivan-hc/MS-Edge-appimage?label=%E2%AD%90&style=for-the-badge)
| [*MPV*](https://github.com/ivan-hc/MPV-appimage) | *JuNest, Arch Linux (ArchImage)* | ![](https://img.shields.io/github/stars/ivan-hc/MPV-appimage?label=%E2%AD%90&style=for-the-badge)
| [*OBS-Studio*](https://github.com/ivan-hc/OBS-Studio-appimage) | *JuNest, Arch Linux (ArchImage)* | ![](https://img.shields.io/github/stars/ivan-hc/OBS-Studio-appimage?label=%E2%AD%90&style=for-the-badge)
| [*ocenaudio*](https://github.com/ivan-hc/ocenaudio-appimage) | *Official .deb package* | ![](https://img.shields.io/github/stars/ivan-hc/ocenaudio-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Opera Stable/Beta/Dev*](https://github.com/ivan-hc/Opera-appimage) | *Official .deb packages* | ![](https://img.shields.io/github/stars/ivan-hc/Opera-appimage?label=%E2%AD%90&style=for-the-badge)
| [*PowerShell*](https://github.com/ivan-hc/PowerShell-appimage) | *Standalone build for GNU/Linux* | ![](https://img.shields.io/github/stars/ivan-hc/PowerShell-appimage?label=%E2%AD%90&style=for-the-badge)
| [*qBittorrent*](https://github.com/ivan-hc/qbittorrent-appimage) | *Ubuntu (PPA)* | ![](https://img.shields.io/github/stars/ivan-hc/qbittorrent-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Sideload*](https://github.com/ivan-hc/Flatpak-installer-appimage) | *Official .deb package (ElementaryOS)* | ![](https://img.shields.io/github/stars/ivan-hc/Flatpak-installer-appimage?label=%E2%AD%90&style=for-the-badge)
| [*SimpleScreenRecorder*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/simplescreenrecorder) | *Ubuntu (PPA)*  | ![](https://img.shields.io/github/stars/ivan-hc/Database-of-pkg2appimaged-packages?label=%E2%AD%90&style=for-the-badge)
| [*Skype*](https://github.com/ivan-hc/Skype-appimage) | *Official .deb package* | ![](https://img.shields.io/github/stars/ivan-hc/Skype-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Spotify*](https://github.com/ivan-hc/Spotify-appimage) | *Official .deb package* | ![](https://img.shields.io/github/stars/ivan-hc/Spotify-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Steam*](https://github.com/ivan-hc/Steam-appimage) | *Official .deb package (experimental)* | ![](https://img.shields.io/github/stars/ivan-hc/Steam-appimage?label=%E2%AD%90&style=for-the-badge)
| [*SuperTuxKart*](https://github.com/ivan-hc/SuperTuxKart-appimage) | *Standalone build for GNU/Linux* | ![](https://img.shields.io/github/stars/ivan-hc/SuperTuxKart-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Vivaldi Stable/Snapshot*](https://github.com/ivan-hc/Vivaldi-appimage) | *Official .deb packages* | ![](https://img.shields.io/github/stars/ivan-hc/Vivaldi-appimage?label=%E2%AD%90&style=for-the-badge)
| [*VLC*](https://github.com/ivan-hc/VLC-appimage) | *JuNest, Arch Linux (ArchImage)* | ![](https://img.shields.io/github/stars/ivan-hc/VLC-appimage?label=%E2%AD%90&style=for-the-badge)
| [*WhatsApp Nativefier*](https://github.com/ivan-hc/whatsapp-nativefier-appimage) | *Standalone build for GNU/Linux* | ![](https://img.shields.io/github/stars/ivan-hc/whatsapp-nativefier-appimage?label=%E2%AD%90&style=for-the-badge)

-------------------------------------------------------

## Scripts and utilities
| Project | Stars |
| -- | -- |
| [*Firefox for Linux*](https://github.com/ivan-hc/Firefox-for-Linux-scripts)*, installation scripts* | ![](https://img.shields.io/github/stars/ivan-hc/Firefox-for-Linux-scripts?label=%E2%AD%90&style=for-the-badge)
| [*Flatpak installer*](https://github.com/ivan-hc/flatpak-install-action)*, a custom action* | ![](https://img.shields.io/github/stars/ivan-hc/flatpak-install-action?label=%E2%AD%90&style=for-the-badge)

## Side projects
| Project | Stars |
| -- | -- |
| [*Arch-deployer*](https://github.com/ivan-hc/Arch-deployer) *(deprecated)* | ![](https://img.shields.io/github/stars/ivan-hc/Arch-deployer?label=%E2%AD%90&style=for-the-badge)
