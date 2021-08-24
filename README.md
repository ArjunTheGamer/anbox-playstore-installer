# anbox-playstore-installer
Thank geeks-r-us for the scripts. I have just fixed his scripts.

Before running this script run this 2 commands:
```
sudo mkdir /etc/systemd/system/anbox-container-manager.service.d/

sudo chmod a+w /etc/systemd/system/anbox-container-manager.service.d/
```

If you are getting this error:
```
Failed to restart anbox-container-manager.service: Unit anbox-container-manager.service is masked.
```
Then run the following command:
```
sudo systemctl unmask anbox-container-manager.service
```
