*My name is Ivan, I'm italian and I like to play with Portable Linux Apps, in particular AppImage packages.*

-------------------------------------------------------

- [Main projects](#main-projects)
- [My AppImage packages](#my-appimage-packages)
- [Scripts and utilities](#scripts-and-utilities)
- [Side projects](#side-projects)

-------------------------------------------------------

### Main projects

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

### My AppImage packages
*This is the list of all AppImage packages I build in my repositories for both "AM" and "AppMan":*

| Application | Stars |
| -- | -- |
| [*AnyDesk*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/anydesk), a remote desktop client | ![](https://img.shields.io/github/stars/ivan-hc/Database-of-pkg2appimaged-packages?label=%E2%AD%90&style=for-the-badge)
| [*Asunder*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/asunder), an Audio CD-Ripper | ![](https://img.shields.io/github/stars/ivan-hc/Database-of-pkg2appimaged-packages?label=%E2%AD%90&style=for-the-badge)
| [*Audacious*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/audacious), an Audio player built from PPA | ![](https://img.shields.io/github/stars/ivan-hc/Database-of-pkg2appimaged-packages?label=%E2%AD%90&style=for-the-badge)
| [*Avidemux*](https://github.com/ivan-hc/Avidemux-unofficial-appimage), a custom build | ![](https://img.shields.io/github/stars/ivan-hc/Avidemux-unofficial-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Billard GL*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/billard-gl), GPL 3D OpenGL Billard | ![](https://img.shields.io/github/stars/ivan-hc/Database-of-pkg2appimaged-packages?label=%E2%AD%90&style=for-the-badge)
| [*CAP: Pirate Battleship*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/capbattleship), pirate-themed battleship game | ![](https://img.shields.io/github/stars/ivan-hc/Database-of-pkg2appimaged-packages?label=%E2%AD%90&style=for-the-badge)
| [*Celestia*](https://github.com/ivan-hc/Celestia-appimage), space simulator with additional maps | ![](https://img.shields.io/github/stars/ivan-hc/Celestia-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Chromium BSU*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/chromium-bsu), arcade-style space shooter | ![](https://img.shields.io/github/stars/ivan-hc/Database-of-pkg2appimaged-packages?label=%E2%AD%90&style=for-the-badge)
| [*Chromium*](https://github.com/ivan-hc/Chromium-Web-Browser-appimage), Web Browser built from PPA | ![](https://img.shields.io/github/stars/ivan-hc/Chromium-Web-Browser-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Extreme Tux Racer*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/extremetuxracer), 3D racing game | ![](https://img.shields.io/github/stars/ivan-hc/Database-of-pkg2appimaged-packages?label=%E2%AD%90&style=for-the-badge)
| [*GIMP*](https://github.com/ivan-hc/GIMP-appimage), image manipulation program (Stable/Dev) | ![](https://img.shields.io/github/stars/ivan-hc/GIMP-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Handbrake*](https://github.com/ivan-hc/Handbrake-appimage), Audio/Video transcoder | ![](https://img.shields.io/github/stars/ivan-hc/Handbrake-appimage?label=%E2%AD%90&style=for-the-badge)
| [*KDE-games*](https://github.com/ivan-hc/KDE-games-suite-appimage), the whole KDE games suite | ![](https://img.shields.io/github/stars/ivan-hc/KDE-games-suite-appimage?label=%E2%AD%90&style=for-the-badge)
| [*KDE-utils*](https://github.com/ivan-hc/KDE-utils-appimage), the full suite of KDE utilities | ![](https://img.shields.io/github/stars/ivan-hc/KDE-utils-appimage?label=%E2%AD%90&style=for-the-badge)
| [*kwave*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/kwave), sound editor for KDE | ![](https://img.shields.io/github/stars/ivan-hc/Database-of-pkg2appimaged-packages?label=%E2%AD%90&style=for-the-badge)
| [*lxtask*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/lxtask), the Task Manager of LXDE/LXQT | ![](https://img.shields.io/github/stars/ivan-hc/Database-of-pkg2appimaged-packages?label=%E2%AD%90&style=for-the-badge)
| [*Microsoft Edge*](https://github.com/ivan-hc/MS-Edge-appimage), Web Browser built from debs | ![](https://img.shields.io/github/stars/ivan-hc/MS-Edge-appimage?label=%E2%AD%90&style=for-the-badge)
| [*MPV*](https://github.com/ivan-hc/MPV-appimage), a versatile Video Player | ![](https://img.shields.io/github/stars/ivan-hc/MPV-appimage?label=%E2%AD%90&style=for-the-badge)
| [*ocenaudio*](https://github.com/ivan-hc/ocenaudio-appimage), Audio editor | ![](https://img.shields.io/github/stars/ivan-hc/ocenaudio-appimage?label=%E2%AD%90&style=for-the-badge)
| [*qBittorrent*](https://github.com/ivan-hc/qbittorrent-appimage), bittorrent client (lite version) | ![](https://img.shields.io/github/stars/ivan-hc/qbittorrent-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Sideload*](https://github.com/ivan-hc/Flatpak-installer-appimage), Flatpak installer from elementaryOS | ![](https://img.shields.io/github/stars/ivan-hc/Flatpak-installer-appimage?label=%E2%AD%90&style=for-the-badge)
| [*SimpleScreenRecorder*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/simplescreenrecorder), screen recorder | ![](https://img.shields.io/github/stars/ivan-hc/Database-of-pkg2appimaged-packages?label=%E2%AD%90&style=for-the-badge)
| [*Spotify*](https://github.com/ivan-hc/Spotify-appimage), unofficial client | ![](https://img.shields.io/github/stars/ivan-hc/Spotify-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Steam*](https://github.com/ivan-hc/Steam-appimage), experimental AppImage | ![](https://img.shields.io/github/stars/ivan-hc/Steam-appimage?label=%E2%AD%90&style=for-the-badge)
| [*SuperTuxKart*](https://github.com/ivan-hc/SuperTuxKart-appimage), the crazy kart racing game | ![](https://img.shields.io/github/stars/ivan-hc/SuperTuxKart-appimage?label=%E2%AD%90&style=for-the-badge)
| [*VLC*](https://github.com/ivan-hc/VLC-appimage), Video & Media player | ![](https://img.shields.io/github/stars/ivan-hc/VLC-appimage?label=%E2%AD%90&style=for-the-badge)

-------------------------------------------------------

### Scripts and utilities
| Project | Description | Stars |
| -- | -- | -- |
| [*Firefox-for-Linux-scripts*](https://github.com/ivan-hc/Firefox-for-Linux-scripts) | <sub>*easily install and remove official Firefox Stable, Beta, DevEdition, Nightly and ESR versions on GNU / Linux using my scripts* | ![](https://img.shields.io/github/stars/ivan-hc/Firefox-for-Linux-scripts?label=%E2%AD%90&style=for-the-badge)
| [*Flatpak-install-action*](https://github.com/ivan-hc/flatpak-install-action) | <sub>*a custom action to install applications from flathub by pressing the "install" button in Firefox via bash* | ![](https://img.shields.io/github/stars/ivan-hc/flatpak-install-action?label=%E2%AD%90&style=for-the-badge)

### Side projects
| Project | Description | Stars |
| -- | -- | -- |
| [*Arch-deployer*](https://github.com/ivan-hc/Arch-deployer) | <sub>*a script to bulk download an Arch Linux package with all its dependencies to be converted in AppImage* | ![](https://img.shields.io/github/stars/ivan-hc/Arch-deployer?label=%E2%AD%90&style=for-the-badge)
