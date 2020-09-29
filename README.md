Install some desktop env, good example is lightweight xfce4:
sudo apt install xfce4

Install RDP server viewer:
sudo apt install xrdp

Start remote X server:
sudo /etc/init.d/xrdp start

And you can login cia RDP by IP.

If you want to list availible X desktops:
ls /usr/share/xsessions

If you want to change remote desktop just move all .desktop files to other location and leave the one you want to use.
