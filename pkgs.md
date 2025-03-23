# Snapshot = BaseInstall (with /boot)

## PACSTRAP
- base
- linux
- linux-firmware
- btrfs-progs
- intel-ucode

## PACMAN
- opendoas
- neovim
- fish
- networkmanager
- sbctl
- zram-generator
- snapper
- bluez

## SERVICES
- NetworkManager.service
- fstrim.timer
- bluetooth.service

## ZRAM
- /dev/zram0
- /dev/zram1
- /dev/zram2
- /dev/zram3
- /dev/zram4
- /dev/zram5

## OBSIDIAN
`00-06;08-12;15;17;85;87;96`

----------

# Snapshot = GnomeInstall (without /boot)

## PACMAN
- gnome (all)

## SERVICES
- gdm.service

## OBSIDIAN
`76;`

----------

# Snapshot =

## PACMAN
- power-profiles-daemon
- usbguard
- fwupd
- system-config-printer
- man-db
- man-pages
- rclone
- wl-clipboard
- firewalld
- intel-media-driver
- libva-utils (para ver si usa el iHD que es mas nuevo que el i915 para del driver vapi)
- vulkan-intel
- nvidia
- nvidia-settings
- git
- tree
- ripgrep --Para plugin neovim
- gcc
- lsd
- vdpauinfo
- make --Para plugin neovim
- fzf --Para plugin neovim
- wezterm
- fakeroot --Para aur
- debugedit --Para aur
- cups
- efibootmgr

## AUR
- ttf-maple-beta

## SERVICES
- firewalld.service
- cups.socket

## FLATPAK
- org.telegram.desktop
- com.github.tchx84.Flatseal
- md.obsidian.Obsidian
- com.spotify.Client
- com.github.flxzt.rnote
- com.bitwarden.desktop
- org.localsend.localsend_app
- org.onlyoffice.desktopeditors
- org.gnome.Papers
- com.github.jeromerobert.pdfarranger
- app.zen_browser.zen
- com.github.finefindus.eyedropper
- de.haeckerfelix.Fragments
- com.microsoft.Edge
- org.gnome.Boxes
- com.usebottles.bottles

## FONTS
- ttf-iosevka-nerd
- ttf-victor-mono-nerd
