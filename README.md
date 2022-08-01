sudo mv update /usr/local/bin
sudo chown root:root /usr/local/bin

load script at boot:

sudo crontab -e

and append to the file:

@reboot /usr/local/bin/update
