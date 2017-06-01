```
Haven't used these scripts in about a year, things may be outdated.
```

# Quick Install
* Installs Crew(package manager) with python3.4, vim with Vundle, and Crouton
```sh
wget -q -O - https://raw.githubusercontent.com/nickmartin607/chromebookSetup/master/install | bash
```



# Misc Scripts

## mount_rootfs_rw
* Mounts the root filesystem as R/W

*Intended to be used on a Toshiba Chromebook 2 (CB35-3340)*

## install_crosh
* Overrides default crosh shell, skips straight to bash shell.
* Displays a header first, contained within *custom_crosh*
* **Requires rootFS to be mounted R/W**
* **Must be ran from root account, not using sudo.**

## powman
* Manages common power manager functions
```
USAGE: sudo powman [options]
Options:
    -d, --disable   Disable Chromebook power managment features
    -e, --enable    Enable Chromebook power managment features
    -s, --status    Check the power management status
```
