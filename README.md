OS yg support MANTULLLLLLLLLLLLLLLLLLLLLLLLLLLLL FIX
Debian 9 & 10
Ubuntu 18.04 & 20.04

1. Update Repositori VPS dan Upgrade agar Tidak Crash Saat Installasi

sudo su

apt update && apt upgrade -y && update-grub && sleep 2 && reboot

2. Masukkan Perintah Dibawah Untuk Mulai Installasi

sudo su

sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl && wget https://raw.githubusercontent.com/scbdc/my.id/main/setup.sh && chmod +x setup.sh && screen -S setup ./setup.sh
