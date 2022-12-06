# ESP Home scripts

### Upload irrigation script using ESPHome CLI:
sudo docker run --rm -v "${PWD}":/config --device=/dev/ttyUSB0 -it esphome/esphome run irrigation.yaml

# Remote to HA via VS Code
Install Remote-SSH in VS Code. F1 and select Remote-SSH: Connect to host...  (192.168.1.180)
configuration.yaml file will be in config folder that you mounted when installing HA Container (/home/documents)
If failed to save changes, do following: sudo chown <username> -R <path to edit>
e.g. sudo chown hennie -R /home/documents
