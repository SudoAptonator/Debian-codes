
# How to install Xfce4 on Raspberry pi
First you would like to open up your terminal ( Alt + T)
Then you would want to type this:
sudo apt install xserver-xorg xfce4 xfce4-goodies xfce4-indicator-plugin
This will install the xfce packages.
Then, when its finnished, type:
sudo systemctl get-default
Then type: sudo dpkg-reconfigure lightdm
This will reconfigure the lightdm
Then type: sudo update-alternatives --config x-session-manager
This will download the session manager
Then the last step: sudo update-alternatives --config x-window-manager
after that just sudo reboot and your good to go! Your Raspberry pi is now running on xfce and Debian

