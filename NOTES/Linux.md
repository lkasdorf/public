#Linux

# useful Terminal Tools

 - ranger
     - File management
 - trash-cli
     - use trash in terminal (rm removes forever)
 - pfetch
     - like neofetch
 - System monitoring
	 - htop
	 - btop
	 - glances
 - ncdu
     - storage analyzer (nice!)
 - inxi -Fxz
	 - System information

# Guides and Tutorials

- [Creating a Searchable Desktop Icon for Appimage Software on Linux](https://medium.com/@itsmrcrabss/creating-a-searchable-desktop-icon-for-appimage-software-on-linux-82dc9f62ca51)
	- [Archive](https://web.archive.org/web/20231024140700/https://medium.com/@itsmrcrabss/creating-a-searchable-desktop-icon-for-appimage-software-on-linux-82dc9f62ca51)
 - [VIM Tutorial](https://www.freecodecamp.org/news/learn-linux-vim-basic-features-19134461ab85/#:~:text=Yes%2C%20Vim%20provides%20a%20simple,exit%20the%20explorer%20and%20vim.)
 - [Logitech Streamcam config](https://davejansen.com/logitech-streamcam-on-linux/)
    - [Archiv](https://web.archive.org/web/20230519220215/https://davejansen.com/logitech-streamcam-on-linux/)
- [Linux Full Guide - FOSSPOST](https://fosspost.org/linux-full-guide/)
- [Twingate Linux](https://www.twingate.com/docs/linux)
- [Learn Linux TV Tutorials](https://www.youtube.com/playlist?list=PLT98CRl2KxKHdOpQ-uI2QuNcQ0aEAe5bN)
	- Ausführliche Tutorials, verständlich erklärt
	- Hier gibts auch eine Reihe zu Vim

# Desktop Umgebung

- [# From Noob To Power User With Linux Mint Cinnamon](https://www.youtube.com/watch?v=TKX29fJ8U2Y)
	- Hier habe ich rofi kennengelernt. Das ist mal richtig cool. Poweruser Style.

## Fonts Linux

https://averagelinuxuser.com/microsoft-fonts-linux/

sudo apt install ttf-mscorefonts-installer
sudo apt install fonts-crosextra-carlito fonts-crosextra-caladea


# Terminal misc

## Display Hardware Information

[TOP 5 COMMANDS TO DISPLAY HARDWARE INFORMATION ON LINUX](https://freelinuxtutorials.com/top-5-commands-to-display-hardware-information-on-linux/)
Alle Informationen: inxi -Fxz

## Piping in Linux

[geeksforgeeks: Piping in Linux](https://www.geeksforgeeks.org/piping-in-unix-or-linux/)

# Network

## Wireshark

 - Wenn man das System package installiert, fehlen Berechtigungen
 - Folgendes muss ausgeführt werden nach der Installation von Wireshark

```
sudo dpkg-reconfigure wireshark-common
sudo chmod +x /usr/bin/dumpcap	
```
Was ist dumpcap?

# Editing

## Neovim

- [Install Nvim Tree](https://linovox.com/install-and-use-nvim-tree-in-neovim/)
- [Install Which Key](https://linovox.com/install-and-set-up-which-key-in-neovim-nvim/)
- [Install and use Packer](https://linovox.com/install-and-use-packer-in-neovim/)
 - [Vim Cheat Sheet](https://vim.rtorr.com/)
 - [Vim cheatsheet - devhints](https://devhints.io/vim)

# PDF Tools

## Viewer

- [Okular](https://okular.kde.org)
	- Brauchbarerer Viewer mit Annotationen und Markierungsfunktionen
 - Document Viewer (Linux Mint)

## Editors

- PDF24 Tools
- PDF Arranger
- PDF Chain
- PDF Mixtool
- Libreoffice Draw

# Apps

 - [AppImageLauncher](https://github.com/TheAssassin/AppImageLauncher/wiki/Install-on-Ubuntu-or-Debian#use-the-ppas)