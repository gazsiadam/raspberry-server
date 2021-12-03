# raspberry-server

	1. Install Raspberry OS full (not Lite)
	2. OpenMediaVault install
		• wget https://github.com/OpenMediaVault-Plugin-Developers/installScript/raw/master/install
		• chmod +x install
		• sudo ./install -n
			§ -n is for skipping network setup (wifi will still work after reboot)
		• https://dbtechreviews.com/2019/12/how-to-install-openmediavault-on-raspberry-pi-4/
		• Default login: admin/openmediavault
		• Change default port from 80 to 9000 (System/Workbench)
		• Install openmediavault-sharerootfs plugin
		• Create a shared folder
		• Enable NFS
		• Add Shared folder to NFS
		• Add shared folder to SMB/CIFS
	3. Ubiquiti controller
		a. https://www.ui.com/download-software/
		b. Install: wget "https://github.com/SmokingCrop/UniFi/raw/master/install-unifi-pihole-English.sh" -O install-unifi-pihole.sh && chmod +x install-unifi-pihole.sh && ./install-unifi-pihole.sh no-pihole
		c. Upgrade: wget "https://github.com/SmokingCrop/UniFi/raw/master/update-unifi-pihole-English.sh" -O update.sh && chmod +x update.sh && ./update.sh
		d. |
		e. |
		f. |
		g. |
		h. sudo apt install haveged -y
		i. Install Java 11 (Corretto) 
			i. https://docs.aws.amazon.com/corretto/latest/corretto-11-ug/generic-linux-install.html
			ii. Fix 'add-apt-repository' not found: https://itsfoss.com/add-apt-repository-command-not-found/
		

	1. Thermostat install
  
  
