# proxmox_nextcloudpi
Proxmox Custom NextCloudPi

Based on the solution from https://github.com/tteck/Proxmox  
Custom solution as the v1.50.5 disables root access  
https://github.com/nextcloud/nextcloudpi


To create a new Proxmox NextCloudPi LXC, run the following in the Proxmox Shell.  
``
bash -c "$(wget -qLO - https://github.com/negulescus/proxmox_nextcloudpi/raw/main/nextcloudpi-v5.sh)"
``  
⚡ Default Settings: 4GB RAM - 16GB Storage - 4vCPU ⚡
NextCloudPi Interface: (https)IP/
