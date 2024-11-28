# active-directory-Brute Force Attack (using a 20 password attack)
active directory project one (home lab) 

* Vm's used will be Unbuntu server 22.05, WinServer 2023, Win10 Pro, and Kali
* IP used will be 192.168.10.7 on a NAT Network (give it a name) this NAT Net will be used across the project on the WinServer 2023 three users ID will be added to the Active directory

  * Linux (ip a) list your IP config. to configure the static IP on the Ubuntu server I used sudo nano /etc/netplan/ (your can hit tab to autofill) my system had an issuse at this point where the 00-installer-config-yaml didnt pull up what came up was the 50-cloud-init.yaml. Because of this I had to disable 50-cloud-init.yaml

* I had to do a google search in order to work this problem out after a quick 5 mintue search I was able to find and use this To disable cloud-init's network configuration capabilities, write a file
  * /etc/cloud/cloud.cfg.d/99-disable-network-config.cfg with the following:
  * network: {config: disabled}
* 
 
