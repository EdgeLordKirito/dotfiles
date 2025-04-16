## My dotfiles

### Install

Install Nixos via the Plasma Installer Image

cd /etc/nixos

sudo nano configuration.nix

add neovim git and stow

sudo nixos-rebuild switch

clone this repo into your home directory

Install Krohnkite via The KDE SystemSettings in Window Management KWin Scripts

#### Import the Shortcuts
In Keyboard go to Shortcuts

Press Import

Custome Scheme
And Import both file from .config/plasmaExports

Reboot

sudo nixos-rebuild switch
