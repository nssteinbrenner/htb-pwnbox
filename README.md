# htb-pwnbox

Base files to get the look/feel of HTB's pwnbox

## Install
Copy the contents of `applications` to `/usr/share/applications`

Copy the contents of `backgrounds` to `/usr/share/backgrounds`

Copy the contents of `icons` to `/usr/share/icons`

Copy the contents of `themes` to `/usr/share/themes`

Copy the contents of `opt` to `/opt`

Copy the contents of `skel` to `/etc/skel` (if you want to apply this to your user, copy it to your user's home directory)

Load the dconf configuration file `htb-user-desktop.conf` with `dconf load / < htb-user-desktop.conf` as your desired user.

NOTE: This assumes you have all the packages installed that HTB's pwnbox has. Some of the above relies on this. For example. `applications` has an entry for Plank, which is not installed by default. Some of these have icons in /opt that are installed with the package themselves, for example Postman.
