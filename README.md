# Ryuk
An automated installer for Cuckoo Malware Sandbox on Ubuntu 16.04

This tool makes a lot of assumptions:

* This is a clean install of Ubuntu 16.04 Xenial
* You don't mind it auto-configuring servies:
  * uWSGI
  * nginx
* You don't mind it installing boatloads of dependencies Cuckoo and various Python modules need.
* The user Cuckoo will run under is ~cuckoo~
* You will be running it as a user other than ~cuckoo~ and have sudo access.
* You have already done the basic tweaks Cuckoo recommends for Linux installs.
  * If you haven't done this yet, you can read a quick and dirty summary on the topic in this [post](https://packetdamage.com/going-cuckoo-linux-installation/).

If you are good with all of that, then knock yourself out.

## Usage
```
chmod +x setup
./setup
```

Good luck!
