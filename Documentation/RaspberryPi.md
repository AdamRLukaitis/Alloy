


- Raspberry Pi 2
- Raspberry Pi 3


Make into a single processor kernel:
- "nosmp" flag in cmdline.txt
- no swap.


Disable swap:
- sudo chmod -x /etc/init.d/dphys-swapfile
- sudo swapoff -a
- sudo rm /var/swap
