---
parent: "[[infrastructure]]"
---
# Системные изменения и пакеты
## Cypher
- gpg
- LUKS
- sudo-rs
## SDK
- rustup
- git
- dotnet 7
- base-devel
## Other
- fastfetch
- grub theme (98th stroke)
- fish
- helix
- dpkg
# Пакеты-приложения
## Cypher
- KeePassXC
- seahorse
- authy (aur)
- timeshift
## Web
- ton-torrent
- ton-proxy
- syncthing
- qbittorrent
## SDK
- Jetbrains toolbox
    - Rider
    - GoLand
    - RustRover
    - WebStorm
    - Android Studio
    - PyCharm
- VSMC
```
[Desktop Entry]
Type=Application
Name=VSMC
Exec=/usr/lib/jvm/java-21-openjdk/bin/java -jar /home/user/Documents/vsmodelcreator/vsmodelcreator.jar
X-Shortcut-App=true
```
## Media
- LibreOffice
- VLC
- Audacious
- Krita
- GIMP
- OBS
- Helvum
- Obsidian
- Steam
# Конфигурации
- ls -alshS
- fish.conf:
```bash
alias sshserv="ssh -l serveruser -i /home/user/Documents/keys/id_rsa example.com"
    set GPG_TTY $(tty)
    export GPG_TTY
    export VINTAGE_STORY="/home/user/vintagestory"
```
- pipewire sampling rate:
```json
default.clock.allowed-rates = [ 44100 48000 88200 96000 176400 192000 ]
```
- syncthing autostart:
```yaml
[Desktop Entry]
Type=Application
Name=SyncThing
Exec=/usr/bin/syncthing
Icon=/home/user/Pictures/logos/syncthing.png
X-Shortcut-App=true
```
- [Grub Theme](https://github.com/vinceliuice/grub2-themes.git)
- /etc/pacman.conf:
```
Color
ILoveCandy
```
# GNOME
## Extensions
- `[QSTweak]` Quick Setting Tweaker
- AppIndicator and KStatusNotifierItem Support
- Arch Linux Updates Indicator (в настройках поменять gnome-terminal на kgx)
- Blur my Shell
- Gnome 4x UI Improvements
- Pano - Clipboard Manager
- Burn My Windows
- Custom Accent Colors
- Unblank lock screen
- User Themes
- Custom Hot Corners - Extended
## Packages
- baobab
- evince
- gnome-calculator
- gnome-calendar
- gnome-characters
- gnome-clocks
- gnome-console
- gnome-control-center
- gnome-disk-utility
- gnome-font-viewer
- gnome-keyring
- gnome-logs
- gnome-session
- gnome-settings-daemon
- gnome-shell
- gnome-shell-extensions
- gnome-system-monitor
- gnome-text-editor
- gnome-weather
- grilo-plugins
- loupe
- nautilus
- rigel
- snapshot
- sushi
- tecla
- tracker3-miners
- xdg-desktop-portal-gnome
- xdg-user-dirs-gtk
# Firefox
## Pins
- [Arch Linux](https://archlinux.org/)
- [GitHub of Vendetti](https://github.com/Andy4Vendetta)
- Media:
    - [Yandex Music](https://music.yandex.com/home)
    - [YouTube](https://www.youtube.com/)
- Social:
    - [Gmail](https://mail.google.com/mail/u/0/#inbox)
    - [Telegram](https://web.telegram.org/a/)
    - [Discord](https://discord.com/channels/@me)
## Extensions
- GNOME Shell integration
- Greasemonkey
- Privacy Badger
- SponsorBlock
- MyTonWallet
- uBlock
## Containers
- Google
- Telegram
- Discord
- Github
- Info (ArchLinux, Wiki)