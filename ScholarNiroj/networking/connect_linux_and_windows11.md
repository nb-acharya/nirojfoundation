# Networking

### How to transfer

method 1
samba (smb): share a linux folder, windows sees it like a network drive
ssh/sftp: use winscp or filezilla on windows to connect to linux
ftp: set up ftp server on linux, connect from windows
python http server: quick one-liner: python3 -m http.server 8080 on linux, then download via browser on windows


install samba on linux:

sudo apt update
sudo apt install samba -y


mkdir ~/shared

edit the config file

sudo nano /etc/samba/smb.conf

Add this at the bottom of the file:
[MyShare]
   path = /home/yourusername/shared
   browseable = yes
   read only = no
   guest ok = yes

   Replace yourusername with your actual Linux username, and MyShare with whatever share name you like.


   sudo systemctl restart smbd
sudo systemctl restart nmbd


#### ip link show

enp7s0 is your ethernet interface and it's UP — the cable is working physically.


sudo ip addr add 192.168.1.10/24 dev enp7s0