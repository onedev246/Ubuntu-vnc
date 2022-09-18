# Ubuntu-vnc

- apt update
- apt install proot-distro && proot-distro install ubuntu && proot-distro login ubuntu && apt purge gvfs gvfs-daemons gvfs-libs gvfs-common && apt install mate && apt install tightvncserver && apt install mate-terminal
# root
- adduser Rafa
- apt install sudo nano
- nano /etc/sudoers
- Rafa ALL=(ALL:ALL) ALL
- su rafa
- CD
- echo $HOME
- nano
- export USER=Rafa
- export HOME=/home/Rafa

- vncserver -geometry 1280x720
- name /usr/local/bin/vncstart
- nano 
- vncserver -kill :1
- Name /usr/local/bin/vncstop
- vncstart
- vncstop
- nano .vnc/xstartup
- startmate
- vncstart
# vnc viewer
+
- Localhost:1
- Ubuntu
- Connect
 # thank you
