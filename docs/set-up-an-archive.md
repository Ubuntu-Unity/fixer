# Set up a `fixer` archive

## Step 1: Installing the webserver

You will need to install a web server like apache2 or nginx and configure it. You can skip this step if you have already installed a webserver or are using shared hosting.

To install and configure apache2 on Ubuntu, go to https://www.digitalocean.com/community/tutorials/how-to-install-the-apache-web-server-on-ubuntu-20-04.

## Step 3: Create the archive folder.

Create the folder `archive` in the webroot.

## Step 4: Upload the fixes (*.fix)

Upload the `.fix` files to the `archive` folder.

## Create `FIXES.list` (optional, but recommended)

We recommend you create `FIXES.list` in the `archive` folder. You can list the fixes that can be installed using `fixer` in. For example: http://linux.darkpenguin.net/distros/ubuntu-unity/fixer/archive/FIXES.list for http://linux.darkpenguin.net/distros/ubuntu-unity/fixer/archive/.

## Create `fixer.conf` (optional, but recommended)

We recommend you create `fixer.conf` in the `archive` folder, so that the archive users can easily download and copy the file to /etc/fixer.conf to set up your archive on their computer. For example: http://linux.darkpenguin.net/distros/ubuntu-unity/fixer/archive/fixer.conf for http://linux.darkpenguin.net/distros/ubuntu-unity/fixer/archive/.
