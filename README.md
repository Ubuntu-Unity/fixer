# fixer
A program which fetches fixes (scripts) for issues/bugs from a server and applies the fix.

## How to install
Download https://raw.githubusercontent.com/Ubuntu-Unity/fixer/master/fixer, and copy it to a directory in your PATH, like `/usr/bin`. 

### Configuration File (NEEDED TO OPERATE)
A configuration file is needed to operate. Please download http://linux.darkpenguin.net/distros/ubuntu-unity/fixer/archive/fixer.conf for Ubuntu Unity and UbuntuEd and copy it to `/etc/fixer.conf`. If you want to switch from the Ubuntu Unity Archive (if you are using another Unix-like operating system or Linux Distribution), download http://linux.darkpenguin.net/distros/ubuntu-unity/fixer/archive/fixer.conf, copy it to `/etc/fixer.conf` and change the SOURCE variable in `/etc/fixer.conf` to your favourite/distribution's archive.

## Installing a fix
Usage: `fixer <FIX>` as root (using `sudo` or `su`)

## Advanced Documentation
Please check https://github.com/Ubuntu-Unity/fixer/tree/master/docs.
