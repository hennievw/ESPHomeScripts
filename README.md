# ESPHomeScripts

### Upload irrigation script using ESPHome CLI:
sudo docker run --rm -v "${PWD}":/config --device=/dev/ttyUSB0 -it esphome/esphome run irrigation.yaml
