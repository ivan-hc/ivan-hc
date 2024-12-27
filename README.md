# Hi there! I'm **Ivan** :it:
*I like to play with Portable Linux Apps, in particular **AppImage packages**.*

***I'm just an enthusiast** who likes to write scripts for GNU/Linux, for fun.*

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=ivan-hc&show_icons=true&theme=highcontrast)

*I started writing small scripts for personal use, in my free time... and then sharing them here, on Github.*

[Main project](#main-project)

[Creating AppImage packages](#creating-appimage-packages)
- [My Tools](#my-tools)
- [My AppImage packages](#my-appimage-packages)
- [My 32-bit AppImage packages](#my-32-bit-appimage-packages)

[Scripts and utilities](#scripts-and-utilities)

[Side projects](#side-projects)

------------------------------------------------------------------------

## Main project

------------------------------------------------------------------------

<div align="center">

### *"*AM*" Application Manager* 
#### *Package manager, database & solutions for all AppImages and portable apps for GNU/Linux!*

|[<img src="https://github.com/user-attachments/assets/3a521b60-4098-4ad0-8906-779f9e19e7e3">](https://github.com/ivan-hc/AM) | [<img src="https://github.com/user-attachments/assets/ae654830-5071-4603-b265-8c2b773ad760">](https://github.com/ivan-hc/AM) |
| - | - |

[![Readme](https://img.shields.io/github/stars/ivan-hc/AM?label=%E2%AD%90&style=for-the-badge)](https://github.com/ivan-hc/AM/stargazers) [![Readme](https://img.shields.io/github/license/ivan-hc/AM?label=&style=for-the-badge)](https://github.com/ivan-hc/AM/blob/main/LICENSE)

</div>

*"AM"/"AppMan" is a set of scripts and modules for installing, updating, and managing AppImage packages and other portable formats, in the same way that APT manages DEBs packages, DNF the RPMs, and so on... using a large database of Shell scripts inspired by the Arch User Repository, each dedicated to an app or set of applications.*

*The engine of "AM"/"AppMan" is the "APP-MANAGER" script which, depending on how you install or rename it, allows you to install apps system-wide (for a single system administrator) or locally (for each user).*

*"AM"/"AppMan" aims to be the default package manager for all AppImage packages, giving them a home to stay.*

*You can consult the entire **list of managed apps** at [**portable-linux-apps.github.io/apps**](https://portable-linux-apps.github.io/apps).*

## *Go to *https://github.com/ivan-hc/AM* for more!*

------------------------------------------------------------------------

## Creating AppImage packages
*Sometimes my Appimage packages are built from a base of precompiled packages, whether they are in .deb or .tar format it doesn't matter, as long as they know how to work by themselves.* 

*Unfortunately it's not always that simple, so we need to download more dependencies from external packages.*

------------------------------------------------------------------------

#### My Tools
*When a program requires multiple external libraries to work, I use three tools to generate my AppImage packages*: 
- *[**ArchImage**](https://github.com/ivan-hc/ArchImage) is a script that builds AppImages containing a portable Arch Linux container, named "[JuNest](https://github.com/fsquillace/junest)". The final AppImage package is compatible with all the GNU/Linux distributions*
- *[**AppImaGen**](https://github.com/ivan-hc/AppImaGen) is a script that builds AppImages from Ubuntu PPAs or Debian repositories. The final packages are GLIBC compatible for the chosen Debian release or the previous (not the latest, not the oldest) Ubuntu LTS. This method is closest to those commonly used among AppImage packagers*
- *[**Snap2AppImage**](https://github.com/ivan-hc/Snap2AppImage) is an experimental script to convert Snap packages to portable AppImages, good for standalone programs and Electron-based apps available on the Canonical/Ubuntu's Snapstore*

*To recap, in order of "efficiency":*
| Name | AppImages base | Efficiency (%) | Stars |
| -- | -- | -- | -- |
| [**ArchImage**](https://github.com/ivan-hc/ArchImage) | *Arch Linux* | **90%** | ![](https://img.shields.io/github/stars/ivan-hc/ArchImage?label=%E2%AD%90&style=for-the-badge)
| [**AppImaGen**](https://github.com/ivan-hc/AppImaGen) | *Ubuntu LTS or Debian* | **50%** | ![](https://img.shields.io/github/stars/ivan-hc/AppImaGen?label=%E2%AD%90&style=for-the-badge)
| [**Snap2AppImage**](https://github.com/ivan-hc/Snap2AppImage) | *Snap packages* | **10%** | ![](https://img.shields.io/github/stars/ivan-hc/Snap2AppImage?label=%E2%AD%90&style=for-the-badge)

*Also I use "[Conty](https://github.com/Kron4ek/Conty)" sometime, if an AppImage is realy hard to create (see [Bottles](https://github.com/ivan-hc/Bottles-appimage))*

------------------------------------------------------------------------

#### My AppImage packages
*This is the list of all AppImage packages I build in my repositories for both "AM" and "AppMan".*

| Application | Source / Based on... | Stars |
| -- | -- | -- |
| [*Abiword*](https://github.com/ivan-hc/Abiword-appimage) | *JuNest, Arch Linux (ArchImage)* | ![](https://img.shields.io/github/stars/ivan-hc/Abiword-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Aisleriot*](https://github.com/ivan-hc/Aisleriot-appimage) | *JuNest, Arch Linux (ArchImage)* | ![](https://img.shields.io/github/stars/ivan-hc/Aisleriot-appimage?label=%E2%AD%90&style=for-the-badge)
| [*AnyDesk*](https://github.com/ivan-hc/Anydesk-appimage) | *Official .deb package* | ![](https://img.shields.io/github/stars/ivan-hc/Anydesk-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Avidemux*](https://github.com/ivan-hc/Avidemux-unofficial-appimage) | *Debian (Testing, "deb-multimedia")* | ![](https://img.shields.io/github/stars/ivan-hc/Avidemux-unofficial-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Bottles*](https://github.com/ivan-hc/Bottles-appimage) | *Arch Linux (Conty)* | ![](https://img.shields.io/github/stars/ivan-hc/Bottles-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Celestia "Enanched"*](https://github.com/ivan-hc/Celestia-appimage) | *AppImage with additional maps* | ![](https://img.shields.io/github/stars/ivan-hc/Celestia-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Chrome Stable/Beta/Unstable*](https://github.com/ivan-hc/Chrome-appimage) | *Official .deb packages* | ![](https://img.shields.io/github/stars/ivan-hc/Chrome-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Chromium Stable/Candidate/Beta/Edge*](https://github.com/ivan-hc/Chromium-Web-Browser-appimage) | *Snap packages* | ![](https://img.shields.io/github/stars/ivan-hc/Chromium-Web-Browser-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Dropbox*](https://github.com/ivan-hc/Dropbox-appimage) | *Standalone build for GNU/Linux* | ![](https://img.shields.io/github/stars/ivan-hc/Dropbox-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Emacs*](https://github.com/ivan-hc/Emacs-appimage) | *JuNest, Arch Linux (ArchImage)* | ![](https://img.shields.io/github/stars/ivan-hc/Emacs-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Evince*](https://github.com/ivan-hc/Evince-appimage) | *JuNest, Arch Linux (ArchImage)* | ![](https://img.shields.io/github/stars/ivan-hc/Evince-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Gedit*](https://github.com/ivan-hc/Gedit-appimage) | *JuNest, Arch Linux (ArchImage)* | ![](https://img.shields.io/github/stars/ivan-hc/Gedit-appimage?label=%E2%AD%90&style=for-the-badge)
| [*GIMP Stable/Developer/Git/Hybrid*](https://github.com/ivan-hc/GIMP-appimage) | *JuNest, Arch Linux (ArchImage)* | ![](https://img.shields.io/github/stars/ivan-hc/GIMP-appimage?label=%E2%AD%90&style=for-the-badge)
| [*GNOME Boxes*](https://github.com/ivan-hc/Boxes-appimage) | *JuNest, Arch Linux (ArchImage)* | ![](https://img.shields.io/github/stars/ivan-hc/Boxes-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Gnome-calculator*](https://github.com/ivan-hc/Gnome-calculator-appimage) | *JuNest, Arch Linux (ArchImage)* | ![](https://img.shields.io/github/stars/ivan-hc/Gnome-calculator-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Gnome-Tweaks (EXPERIMENTAL)*](https://github.com/ivan-hc/Gnome-tweaks-appimage) | *JuNest, Arch Linux (ArchImage)* | ![](https://img.shields.io/github/stars/ivan-hc/Gnome-tweaks-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Gnumeric*](https://github.com/ivan-hc/Gnumeric-appimage) | *JuNest, Arch Linux (ArchImage)* | ![](https://img.shields.io/github/stars/ivan-hc/Gnumeric-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Handbrake*](https://github.com/ivan-hc/Handbrake-appimage) | *JuNest, Arch Linux (ArchImage)* | ![](https://img.shields.io/github/stars/ivan-hc/Handbrake-appimage?label=%E2%AD%90&style=for-the-badge)
| [*KDE-games*](https://github.com/ivan-hc/KDE-games-suite-appimage) | *JuNest, Arch Linux (ArchImage)* | ![](https://img.shields.io/github/stars/ivan-hc/KDE-games-suite-appimage?label=%E2%AD%90&style=for-the-badge)
| [*KDE-utils*](https://github.com/ivan-hc/KDE-utils-appimage) | *JuNest, Arch Linux (ArchImage)* | ![](https://img.shields.io/github/stars/ivan-hc/KDE-utils-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Microsoft Edge Stable/Beta/Dev*](https://github.com/ivan-hc/MS-Edge-appimage) | *Official .deb packages* | ![](https://img.shields.io/github/stars/ivan-hc/MS-Edge-appimage?label=%E2%AD%90&style=for-the-badge)
| [*MPV*](https://github.com/ivan-hc/MPV-appimage) | *JuNest, Arch Linux (ArchImage)* | ![](https://img.shields.io/github/stars/ivan-hc/MPV-appimage?label=%E2%AD%90&style=for-the-badge)
| [*OBS-Studio*](https://github.com/ivan-hc/OBS-Studio-appimage) | *JuNest, Arch Linux (ArchImage)* | ![](https://img.shields.io/github/stars/ivan-hc/OBS-Studio-appimage?label=%E2%AD%90&style=for-the-badge)
| [*ocenaudio*](https://github.com/ivan-hc/ocenaudio-appimage) | *Official .deb package* | ![](https://img.shields.io/github/stars/ivan-hc/ocenaudio-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Opera Stable/Beta/Dev*](https://github.com/ivan-hc/Opera-appimage) | *Official .deb packages* | ![](https://img.shields.io/github/stars/ivan-hc/Opera-appimage?label=%E2%AD%90&style=for-the-badge)
| [*PowerShell*](https://github.com/ivan-hc/PowerShell-appimage) | *Standalone build for GNU/Linux* | ![](https://img.shields.io/github/stars/ivan-hc/PowerShell-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Rhythmbox*](https://github.com/ivan-hc/Rhythmbox-appimage) | *JuNest, Arch Linux (ArchImage)* | ![](https://img.shields.io/github/stars/ivan-hc/Rhythmbox-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Sideload*](https://github.com/ivan-hc/Flatpak-installer-appimage) | *Official .deb package (ElementaryOS)* | ![](https://img.shields.io/github/stars/ivan-hc/Flatpak-installer-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Skype*](https://github.com/ivan-hc/Skype-appimage) | *Snap package* | ![](https://img.shields.io/github/stars/ivan-hc/Skype-appimage?label=%E2%AD%90&style=for-the-badge)
| [*SpaceCadet Pinball (AUR)*](https://github.com/ivan-hc/Spacecadetpinball-git-appimage) | *JuNest, Arch Linux (ArchImage)* | ![](https://img.shields.io/github/stars/ivan-hc/Spacecadetpinball-git-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Spotify*](https://github.com/ivan-hc/Spotify-appimage) | *Official .deb package* | ![](https://img.shields.io/github/stars/ivan-hc/Spotify-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Steam*](https://github.com/ivan-hc/Steam-appimage) | *Arch Linux (Conty)* | ![](https://img.shields.io/github/stars/ivan-hc/Steam-appimage?label=%E2%AD%90&style=for-the-badge)
| [*SuperTuxKart*](https://github.com/ivan-hc/SuperTuxKart-appimage) | *Standalone build for GNU/Linux* | ![](https://img.shields.io/github/stars/ivan-hc/SuperTuxKart-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Torcs*](https://github.com/ivan-hc/Torcs-appimage) | *JuNest, Arch Linux (ArchImage)* | ![](https://img.shields.io/github/stars/ivan-hc/Torcs-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Transmission-gtk*](https://github.com/ivan-hc/Transmission-gtk-appimage) | *JuNest, Arch Linux (ArchImage)* | ![](https://img.shields.io/github/stars/ivan-hc/Transmission-gtk-appimage?label=%E2%AD%90&style=for-the-badge)
| [*VirtualBox KVM*](https://github.com/ivan-hc/VirtualBox-appimage) | *JuNest, Arch Linux (ArchImage)* | ![](https://img.shields.io/github/stars/ivan-hc/VirtualBox-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Vivaldi Stable/Snapshot*](https://github.com/ivan-hc/Vivaldi-appimage) | *Official .deb packages* | ![](https://img.shields.io/github/stars/ivan-hc/Vivaldi-appimage?label=%E2%AD%90&style=for-the-badge)
| [*VLC Stable/Git*](https://github.com/ivan-hc/VLC-appimage) | *JuNest, Arch Linux (ArchImage)* | ![](https://img.shields.io/github/stars/ivan-hc/VLC-appimage?label=%E2%AD%90&style=for-the-badge)
| [*WhatsApp Nativefier*](https://github.com/ivan-hc/whatsapp-nativefier-appimage) | *Standalone build for GNU/Linux* | ![](https://img.shields.io/github/stars/ivan-hc/whatsapp-nativefier-appimage?label=%E2%AD%90&style=for-the-badge)
| [*WPS Office*](https://github.com/ivan-hc/WPS-Office-appimage) | *Official .deb package* | ![](https://img.shields.io/github/stars/ivan-hc/WPS-Office-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Yandex Browser Stable/Beta/Corporate*](https://github.com/ivan-hc/Yandex-Browser-appimage) | *Official .deb packages* | ![](https://img.shields.io/github/stars/ivan-hc/Yandex-Browser-appimage?label=%E2%AD%90&style=for-the-badge)
| [*Database of pkg2appimaged packages**](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages) | *Various sources* | ![](https://img.shields.io/github/stars/ivan-hc/Database-of-pkg2appimaged-packages?label=%E2%AD%90&style=for-the-badge)

**NOTE, the last one in the table above is a database containing small random apps and games that you may need. The AppImages contained in this repository are:*

| Application | Source / Based on... |
| -- | -- |
| [*Asunder*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/asunder) | *JuNest, Arch Linux (ArchImage)*
| [*Audacious*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/audacious) | *PPA / Ubuntu 18.04*
| [*Baobab3*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/baobab3) | *Debian 11*
| [*Billard GL*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/billard-gl) | *Debian 11*
| [*CAP Battleship*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/capbattleship) | *Official .deb package*
| [*Chromium BSU*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/chromium-bsu) | *Debian 11*
| [*Extreme Tux Racer*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/extremetuxracer) | *Debian 12*
| [*GearLever*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/gearlever) | *JuNest, Arch Linux (ArchImage)*
| [*GNOME System Monitor3*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/gnome-system-monitor3) | *Debian 11*
| [*kwave*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/kwave) | *JuNest, Arch Linux (ArchImage)*
| [*lxtask*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/lxtask) | *Debian 11*
| [*MATE System Monitor*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/mate-system-monitor) | *Debian 11*
| [*SimpleScreenRecorder*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/simplescreenrecorder) | *PPA / Ubuntu 16.04*
| [*VisiPics*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/visipics) | *WINE*
| [*Webcamoid*](https://github.com/ivan-hc/Database-of-pkg2appimaged-packages/releases/tag/webcamoid) | *JuNest, Arch Linux (ArchImage)*

*All of these applications have been built since September 2021, and (if my time will be enough) I will build even more AppImages. Just browse my repositories to find other experimental projects I'm working on. My main workflow is based on the [**ArchImage**](https://github.com/ivan-hc/ArchImage) method since summer 2023, and I believe I will continue to work this way until a better solution than this is discovered.*

*I hope you enjoy them!*

------------------------------------------------------------------------

#### My 32-bit AppImage packages
*32-bit GNU/Linux distributions are increasingly rarely used, but this does not mean they should be excluded. If you use Debian Stable for i386 (recommended) or higher, I have created a specific repository for those applications, all manageable through AM and AppMan.*

| Application | Source / Based on... | Stars |
| -- | -- | -- |
| [*32-bit AppImage packages database*](https://github.com/ivan-hc/32-bit-AppImage-packages-database/releases) | *Various .deb sources* | ![](https://img.shields.io/github/stars/ivan-hc/32-bit-AppImage-packages-database?label=%E2%AD%90&style=for-the-badge)

*The 32-bit AppImages contained in this repository are:*

| Application | Source / Based on... |
| -- | -- |
| [*Chromium*](https://github.com/ivan-hc/32-bit-AppImage-packages-database/releases/tag/chromium) | *Debian (Oldstable)*
| [*GIMP*](https://github.com/ivan-hc/32-bit-AppImage-packages-database/releases/tag/gimp) | *Debian (Stable)*
| [*KDE-games*](https://github.com/ivan-hc/32-bit-AppImage-packages-database/releases/tag/kdegames) | *Debian (Stable)*
| [*VLC*](https://github.com/ivan-hc/32-bit-AppImage-packages-database/releases/tag/vlc) | *Debian (Stable)*

*I have not included them in the main repositories of their 64-bit counterparts to avoid confusion.*

------------------------------------------------------------------------

## Scripts and utilities
| Project | Stars |
| -- | -- |
| [*Firefox for Linux*](https://github.com/ivan-hc/Firefox-for-Linux-scripts)*, installation scripts* | ![](https://img.shields.io/github/stars/ivan-hc/Firefox-for-Linux-scripts?label=%E2%AD%90&style=for-the-badge)
| [*Flatpak installer*](https://github.com/ivan-hc/flatpak-install-action)*, a custom action* | ![](https://img.shields.io/github/stars/ivan-hc/flatpak-install-action?label=%E2%AD%90&style=for-the-badge)

## Side projects
| Project | Stars |
| -- | -- |
| [*Arch-deployer*](https://github.com/ivan-hc/Arch-deployer) *(deprecated)* | ![](https://img.shields.io/github/stars/ivan-hc/Arch-deployer?label=%E2%AD%90&style=for-the-badge)

-------------------------------------------------------

##### *If you find what I do useful, let me know with a star ⭐ in the repository you like best, or with a donation on [PayPal](http://paypal.me/IvanAlexHC) and [Ko-fi](https://ko-fi.com/IvanAlexHC). Thanks in advance!*

| [***Install "AM"***](https://github.com/ivan-hc/AM) | [***My AppImage catalog***](https://portable-linux-apps.github.io) | [***Support me on ko-fi.com***](https://ko-fi.com/IvanAlexHC) | [***Support me on PayPal.me***](https://paypal.me/IvanAlexHC) |
| - | - | - | - |

------------------------------------------------------------------------
