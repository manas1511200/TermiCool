TermiCool


Make your arch terminal fun again.


A comprehensive setup script to supercharge your Arch Linux terminal with Shortcuts, useful tools, and personalized enhancements. This script automatically installs essential packages like lolcat, neofetch, and more while adding practical aliases for navigation, system monitoring, Git, and development. It also includes motivational quotes and visual tweaks to make your terminal experience productive and enjoyable.
![Screenshot From 2024-12-31 09-14-00](https://github.com/user-attachments/assets/e2ee8ae5-2bf7-48ef-9db7-4fba5c1b1192)

Features:
    Custom Shortcuts for faster command-line navigation.

Enhancements for Arch Linux package management with pacman shortcuts.
    Motivational quotes and system info displayed on terminal startup.
    Fun additions like neofetch and lolcat for a vibrant terminal experience.
    Supports structured, XDG-compliant configuration file for quotes.

How to Install


Prerequisites

Ensure you’re running Arch Linux and have the sudo privilege.
```shell

[ -d "TermiCool" ] && rm -rf "TermiCool"
git clone https://github.com/manas1511200/TermiCool.git
cd TermiCool
chmod +x setup.sh
./setup.sh
source ~/.bashrc

```
To see the keys that have been added just type:
```shell
keys
```
If you want to revert back to your normal system:
```shell
cp ~/.bashrc.backup ~/.bashrc
source ~/.bashrc

```

If you want to load the system default of the OS
```shell
cp /etc/skel/.bashrc ~/
```
If you wnat to do the same again just type
```shell
reload
```


YOU can also edit the .bashrc file to change the configurations, add alias and many other things




