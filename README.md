# Chrome Remote Desktop on Debian/Ubuntu Server

Get a remote connection to your cloud server! This utility script by default installs XFCE, Chrome and Chrome Remote Desktop.

Based on [this](https://cloud.google.com/solutions/chrome-desktop-remote-on-compute-engine) guide, made ready to install with one command and use xfce by default.

### Steps:
1. Install requirements (please check if the script is safe before you execute this command!)
```sh
wget -qO- https://raw.githubusercontent.com/vutangamz/chrome-remote-desktop/master/install.sh | sudo bash
```
2. Set up the connection - https://remotedesktop.google.com/headless
3. Connect to your server from https://remotedesktop.google.com/

You're done!
