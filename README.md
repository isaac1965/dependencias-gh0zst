# dependencias-gh0zst
```sh
paru -S zsh neovim base-devel git reflector bat bspwm brightnessctl clipcat dunst eza feh fzf thunar tumbler gvfs-mtp firefox geany imagemagick jq jgmenu kitty libwebp maim mpc mpd mpv ncmpcpp npm pamixer pacman-contrib papirus-icon-theme picom playerctl polybar lxsession-gtk3 python-gobject redshift rofi rustup sxhkd tmux xclip xdg-user-dirs xdo xdotool xsettingsd xorg-xdpyinfo xorg-xkill xorg-xprop xorg-xrandr xorg-xsetroot xorg-xwininfo yazi zsh zsh-autosuggestions zsh-history-substring-search zsh-syntax-highlighting ttf-inconsolata ttf-jetbrains-mono  ttf-jetbrains-mono-nerd ttf-terminus-nerd ttf-ubuntu-mono-nerd webp-pixbuf-loader eww-git i3lock-color simple-mtpfs fzf-tab-git xqp xwinwrap-0.9-bin bluez bluez-utils pulseaudio pulseaudio-alsa pavucontrol
```
themes
```sh
paru -S ghostzk-gtk-themes gh0stzk-qogirr gh0stzk-icons-beautyline gh0stzk-icons-candy gh0stzk-icons-catppuccin-mocha gh0stzk-icons-dracula gh0stzk-icons-glassy gh0stzk-icons-gruvbox-plus-dark gh0stzk-icons-hack gh0stzk-icons-luv gh0stzk-icons-sweet-rainbow gh0stzk-icons-tokio-night gh0stzk-icons-vimix-white gh0stzk-icons-zafiro gh0stzk-icons-zafiro-purple
```
pacman.conf
```sh
[gh0stzk-dotfiles]
SigLevel = Optional TrustAll
Server = http://gh0stzk.github.io/pkgs/x86_64
```
/etc/X11/xorg.conf.d/40-libinput.conf

```sh
Section "InputClass"
  Identifier "touchpad"
  Driver "libinput"
  MatchIsTouchpad" "on"
  Option "Tapping" "on"
  Option "TappingButtonMap" "lrm"
EndSection
```
