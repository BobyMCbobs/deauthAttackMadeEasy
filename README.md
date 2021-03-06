# easy-deauth

#### Release version: 1.2

##### Description
Send deauth packages to your favourite devices on your private WiFi network!
As this ultimately relies on aircrack-ng, all of the work for this program is in the programs from that package.
easy-deauth just scripts it, to make it more straight forward and easier.
(Previously named deauthAttackMadeEasy)

##### Features  
- Finds network interfaces and best guesses which are wireless.
- Automatic configuration of network interface to work with airmon-ng.

##### Packaging
Debian:  
	Binary: `make deb-pkg`  
	Source: `make deb-src`  
CentOS/Fedora specs: support/specs/CentOS-Fedora  
openSUSE specs: [openSUSE Software](https://software.opensuse.org/package/easy-deauth)
Arch Linux: [AUR](https://aur.archlinux.org/packages/easy-deauth)  
Zip archive: `make build-zip`  

##### Installation
Non-package installation: `make install`  

##### Dependencies  
Ubuntu/Debian/Raspbian: aircrack-ng
Arch Linux: aircrack-ng
Fedora/CentOS: aircrack-ng (CentOS: Nux repo)
openSUSE: aircrack-ng (Packman repo)

##### Usage
Standard use: `getnewip`  
Help: `getnewip -h`  

##### Notes
- This has been testing on GNU/Linux distributions: Arch Linux, Debian (9.x), openSUSE (Leap 15), and Ubuntu (16.04, 18.04).
- Building a debian package requires 'build-essential' and 'devscripts'.
- Main repository is on [GitLab](https://gitlab.com/BobyMCbobs/easy-deauth). There is a [GitHub](https://github.com/BobyMCbobs/easy-deauth) mirror.
