# wpa-password-writer
Writes the SSID and password to the wpa_supplicant.conf file

It is recommend that you'll add a space before running the script so command doesn't save in the history with the password. To do this, you'll need to add change HISTCONTROL to be equal to HISTCONTROL=ignorespace in the ~/.bashrc file. When you enter your password, make sure that you're password is inside singel quotes.

Example:
====================================
$ ./wpa.sh ssid_name 'ssid_password'
