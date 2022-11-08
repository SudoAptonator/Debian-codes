
# How to install Xfce4 on Raspberry pi
First you would like to open up your terminal ( Alt + T)
Then you would want to type this:
<pre>sudo apt install xserver-xorg xfce4 xfce4-goodies xfce4-indicator-plugin</pre>
This will install the xfce packages.
Then, when its finnished, type:
<pre>sudo systemctl get-default</pre>
Then type: <pre>sudo dpkg-reconfigure lightdm</pre>
This will reconfigure the lightdm
Then type: <pre>sudo update-alternatives --config x-session-manager</pre>
(select anything that says xfce on it)
This will download the session manager
Then the last step: <pre>sudo update-alternatives --config x-window-manager</pre>
after that just <pre>sudo reboot</pre> and your good to go! Your Raspberry pi is now running on xfce and Debian

