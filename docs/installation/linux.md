# Installation on GNU+Linux
There are multiple ways to install shaweelTimer on [GNU](https://gnu.org/home.en.html)+[Linux](https://kernel.org). Ranging from distro-specific to completely universal.

Navigation:  
[Jump to Debian](#debian)  
[Jump to Fedora](#fedora)  
[Jump to the AUR](#the-arch-user-repository)  
## Debian
For [Debian](https://www.debian.org) and its [derivatives](https://www.debian.org/derivatives/) you can install shaweelTimer by downloading a .deb file from the [latest release](https://github.com/shaweel/shaweelTimer/releases/latest) and installing it with `sudo apt install ./shaweelTimer.deb`

## Fedora
For [Fedora](https://fedoraproject.org) and its [derivatives](https://fedoraproject.org/wiki/Derived_distributions) you can install shaweelTimer by downloading a .rpm file from the [latest release](https://github.com/shaweel/shaweelTimer/releases/latest) and installing it with `sudo dnf install ./shaweelTimer.rpm`

## The Arch User Repository
For [Arch Linux](https://archlinux.org) and its [derivatives](https://wiki.archlinux.org/title/Arch-based_distributions) you can install shaweelTimer using [The Arch User Repository](https://aur.archlinux.org).

To install shaweelTimer, install the `shaweelTimer` package either with an [AUR helper](https://wiki.archlinux.org/title/AUR_helpers) like `yay` or `paru`  
`yay -S shaweelTimer` or  `paru -S shaweelTimer`  
or manually installing the package using `git` and `makepkg`  
`git clone https://aur.archlinux.org/shaweelTimer.git`  
`cd shaweelTimer`  
`makepkg -si`
