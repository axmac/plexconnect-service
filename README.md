# About

Simple service wrapper for PlexConnect. Tested in Ubuntu 15.10.

# Installation

Install PlexConnect from https://github.com/iBaa/PlexConnect.

Copy the files in `default`, `init` and `init.d` to the corresponding `/etc/?` folders.

Set the location of PlexConnect in `/etc/default/plexconnect` if it isn't `/usr/local/lib/PlexConnect`.

Install the service:

        sudo update-rc.d plexconnect defaults

Start the service:

        sudo service plexconnect start

# Logs

PlexConnect logs are written to the log location specified in `PLEXCONNECT_HOME/Settings.cfg`.

E.g. to log to `/var/log/PlexConnect.log`, set `logpath` in `Settings.cfg`:

        logpath = /var/log


