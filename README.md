tretflixCLI (Sickrage+DelugeVPN Fork)
===========
CLI for the Tretflix vApp

This fork is intended to:

* Replace Sickbeard with SickRage
* Add Deluge-Web
* Include Docker Container support for Deluge-PIA-VPN https://github.com/jbogatay/docker-piavpn
* Add service homepage


Install (64bit Unbunt 14.04)
============================
* Create "sysadmin" user or change the user in the script file
* Create the following path: /opt/tretflix/.sys/cli
* Recursive chown the /opt/tretflix directory with the desire user:group (default: sysadmin:sysadmin)
* Clone: git clone {repo} /opt/tretflix/.sys/cli
* Logout and back into the shell
* tretflix config wizard

Warning
=======
This is a development fork.  Install this on a fresh 64bit Ubuntu VM (14.04 or newer) for testing and evaluation.
