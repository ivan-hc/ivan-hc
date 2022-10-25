*My name is Ivan, I'm italian and I like to play with Portable Linux Apps, in particular AppImage packages.*

-------------------------------------------------------

- [Main projects](#main-projects)
- [My AppImage packages](#my-appimage-packages)
- [Scripts and utilities](#scripts-and-utilities)

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

| Application | Description | Stars |
| -- | -- | -- |
| [*Asunder*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/asunder) | <sub>*an Audio CD-Ripper built from Debian Oldstable* | ![](https://img.shields.io/github/stars/ivan-hc/Database-of-pkg2appimaged-packages?color=000000&label=%20)
| [*Audacious*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/audacious) | *an Audio player built from PPA* | ![](https://img.shields.io/github/stars/ivan-hc/Database-of-pkg2appimaged-packages?color=000000&label=%20)
| [*Avidemux Unofficial*](https://github.com/ivan-hc/Avidemux-unofficial-appimage) | *a custom build (ie for my personal use) that supports dark themes (not available in my App Managers, where it is also available the official AppImage)* | ![](https://img.shields.io/github/stars/ivan-hc/Avidemux-unofficial-appimage?color=000000&label=%20)
| [*Billard GL*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/billard-gl) | *a GPL 3D OpenGL Billard Simulator built from Debian Oldstable* | ![](https://img.shields.io/github/stars/ivan-hc/Database-of-pkg2appimaged-packages?color=000000&label=%20)
| [*CAP: Pirate Battleship*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/capbattleship) | *a pirate-themed battleship game built from the official .deb package* | ![](https://img.shields.io/github/stars/ivan-hc/Database-of-pkg2appimaged-packages?color=000000&label=%20)
| [*Celestia Enanched*](https://github.com/ivan-hc/Celestia-appimage) | *a multiplatform free space simulator with additional maps for Planets and Moons (not available in my App Managers, where there are already used both Stable and Development versions from the official forum)* | ![](https://img.shields.io/github/stars/ivan-hc/Celestia-appimage?color=000000&label=%20)
| [*Chromium BSU*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/chromium-bsu) | *an arcade-style, top-scrolling space shooter* | ![](https://img.shields.io/github/stars/ivan-hc/Database-of-pkg2appimaged-packages?color=000000&label=%20)
| [*Chromium Web Browser*](https://github.com/ivan-hc/Chromium-Web-Browser-appimage) | *(Stable) built from PPA* | ![](https://img.shields.io/github/stars/ivan-hc/Chromium-Web-Browser-appimage?color=000000&label=%20)
| [*Extreme Tux Racer*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/extremetuxracer) | *3D racing game featuring Tux, the Linux penguin* | ![](https://img.shields.io/github/stars/ivan-hc/Database-of-pkg2appimaged-packages?color=000000&label=%20)
| [*GIMP*](https://github.com/ivan-hc/GIMP-appimage) | *(Stable and Development editions) built from PPA* | ![](https://img.shields.io/github/stars/ivan-hc/GIMP-appimage?color=000000&label=%20)
| [*Handbrake*](https://github.com/ivan-hc/Handbrake-appimage) | *an Audio & Video transcoder built from PPA* | ![](https://img.shields.io/github/stars/ivan-hc/Handbrake-appimage?color=000000&label=%20)
| [*KDE-games-suite*](https://github.com/ivan-hc/KDE-games-suite-appimage) | *all the KDE games in one AppImage built from Debian Stable* | ![](https://img.shields.io/github/stars/ivan-hc/KDE-games-suite-appimage?color=000000&label=%20)
| [*KDE-utils*](https://github.com/ivan-hc/KDE-utils-appimage) | *the full suite of KDE utilities in one AppImage built from Debian Stable* | ![](https://img.shields.io/github/stars/ivan-hc/KDE-utils-appimage?color=000000&label=%20)
| [*lxtask*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/lxtask) | *the default Task Manager of LXDE/LXQT* | ![](https://img.shields.io/github/stars/ivan-hc/Database-of-pkg2appimaged-packages?color=000000&label=%20)
| [*Microsoft Edge*](https://github.com/ivan-hc/MS-Edge-appimage) | *(Unofficial Stable/Beta/Development editions) built from the official debs* | ![](https://img.shields.io/github/stars/ivan-hc/MS-Edge-appimage?color=000000&label=%20)
| [*MPV*](https://github.com/ivan-hc/MPV-appimage) | *a versatile lightweight Video Player* | ![](https://img.shields.io/github/stars/ivan-hc/MPV-appimage?color=000000&label=%20)
| [*ocenaudio*](https://github.com/ivan-hc/ocenaudio-appimage) | *one of the best multiplatform Audio editors* | ![](https://img.shields.io/github/stars/ivan-hc/ocenaudio-appimage?color=000000&label=%20)
| [*qBittorrent*](https://github.com/ivan-hc/qbittorrent-appimage) | *(Unofficial Lite Edition) built from the official PPA* | ![](https://img.shields.io/github/stars/ivan-hc/qbittorrent-appimage?color=000000&label=%20)
| [*Sideload*](https://github.com/ivan-hc/Flatpak-installer-appimage) | *the Flatpak installer from elementaryOS (not available in my App Managers)* | ![](https://img.shields.io/github/stars/ivan-hc/Flatpak-installer-appimage?color=000000&label=%20)
| [*Spotify Unofficial*](https://github.com/ivan-hc/Spotify-appimage) | *built from the official .deb package* | ![](https://img.shields.io/github/stars/ivan-hc/Spotify-appimage?color=000000&label=%20)
| [*Steam*](https://github.com/ivan-hc/Steam-appimage) | *a first experimental attempt to convert Steam into a portable AppImage package* | ![](https://img.shields.io/github/stars/ivan-hc/Steam-appimage?color=000000&label=%20)
| [*SuperTuxKart*](https://github.com/ivan-hc/SuperTuxKart-appimage) | *the crazy kart racing game built from the official release* | ![](https://img.shields.io/github/stars/ivan-hc/SuperTuxKart-appimage?color=000000&label=%20)
| [*VLC*](https://github.com/ivan-hc/VLC-appimage) | *the best Video and Media player ever, built from PPA.* | ![](https://img.shields.io/github/stars/ivan-hc/VLC-appimage?color=000000&label=%20)

-------------------------------------------------------

### Scripts and utilities
| Application | Description | Stars |
| -- | -- | -- |
| [*Arch-deployer*](https://github.com/ivan-hc/Arch-deployer) | *ascript to bulk download an Arch Linux package with all its dependencies to be converted in AppImage* | ![](https://img.shields.io/github/stars/ivan-hc/Arch-deployer?color=000000&label=%20)
| [*Firefox-for-Linux-scripts*](https://github.com/ivan-hc/Firefox-for-Linux-scripts) | *easily install and remove official Firefox Stable, Beta, DevEdition, Nightly and ESR versions on GNU / Linux using my scripts* | ![](https://img.shields.io/github/stars/ivan-hc/Firefox-for-Linux-scripts?color=000000&label=%20)
| [*Flatpak-install-action*](https://github.com/ivan-hc/flatpak-install-action) | *a custom action to install applications from flathub by pressing the "install" button in Firefox via bash* | ![](https://img.shields.io/github/stars/ivan-hc/flatpak-install-action?color=000000&label=%20)
