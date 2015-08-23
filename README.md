# Mr.Anderson's Arch Reference (MAAR?)

## Purpose
Everytime I reinstall Arch I learn a little bit more and create more interesting artifacts.  This is where I am collecting them.  I use arch as my primary desktop/laptop with WMII so the usefullness of this for you might vary.

## Layout
I am trying to organize things out differently than I have in the past.  For each thing I feel is a 'component' of my standard deployment I have created a folder.  Each folder has the following layout:

* packages.txt: A list of packages that need to be installed, in practice this is turning out to not be very useful...
* notes.txt: Random stuff that I wanted to save related to the component
* files/: A collection of files added to the system, unless specified below it mirrors the file system location from /
* files/home-dir/standard: Any files or folders should be moved from here to your home directory without modification
* files/home-dir/hidden: Any files or folders should be moved from here to your home directory and prefixed with a '.'

More to come as I go ;)

## Systemd/user references:
* https://wiki.archlinux.org/index.php/Systemd/User#Xorg_as_a_systemd_user_service
* https://bitbucket.org/KaiSforza/systemd-user-units/src/07d6ec2916ce?at=master
* https://github.com/lemenkov/systemd-user-units

## TODO:
* Remove DISPLAY from systemd/user units.  Common target?
* Play with zathura for pdf
* Add xdg-open customizations to this repo
* Add emacs customizations to this repo
* Figure out system tray
* Add system notifications support (https://wiki.archlinux.org/index.php/Desktop_notifications)
* Customize rxvt (https://wiki.archlinux.org/index.php/Rxvt-unicode)
* Add iptable customizations to this repo
* Add dnsmasq customizations to this repo (https://wiki.archlinux.org/index.php/Systemd-networkd)
* Console improvements? (https://wiki.archlinux.org/index.php/General_recommendations)
* Num lock on boot (https://wiki.archlinux.org/index.php/Activating_Numlock_on_Bootup)  
