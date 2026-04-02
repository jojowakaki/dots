# Dots
Dot files

## Requirements

1. niri
2. waybar
3. dunst (notification)
4. rofi
5. swayimg
6. foot terminal
7. ranger
8. vim
9. mpv
10. qutebrowser
11. zathura (pdf reader)
12. yay (read .bashrc aliases, you can modify them to use pacman if not using yay)
13. read config/niri/requirements.md for additinal requirements.

## Steps
1. Copy config vim and bashrc to $HOME
2. change the filename config vim bashrc to .config .vim and .bashrc
3. On Vim run :PlugInstall
4. Go to .vim/Plugged/Youcompleteme and run install.py (python required of course) or ymcd doesn't work

This doesnot cover gtk kvantum and qutebrowser themes and fonts, those need to be downloaded and applied separately
- Fonts used: Iosevka nord, Mononoki nerd, and JetBrains Mono nerd
- gtk-theme = nordic
- icon theme = qogir-dark
- cursor theem = Qogir
- kvantum theme = nordic

Optionally requires, kvantum, qt6ct and lxappearance
included rofi-bluetooth which can access bluetooth function from rofi. Optionally create a .dekstop file for it, however it works as scripts are callable.
