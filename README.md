## NOTES:

### Home Assistant

#### Bluetooth

See: https://www.home-assistant.io/integrations/bluetooth/#additional-details-for-container

See: https://github.com/bus1/dbus-broker/wiki
```
sudo apt install dbus-broker
sudo systemctl enable dbus-broker.service
```

_/etc/bluetooth/main.conf_
```
# Enables D-Bus experimental interfaces
# Possible values: true or false
Experimental = true
```
