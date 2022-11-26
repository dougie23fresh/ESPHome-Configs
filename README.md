# ESPHome-Configs
ESPHome Configs Yaml Files



```
substitutions:
  name: bedroom-lamp
  friendly_name: Bedroom Lamp

packages:
  kauf.plf10: github://dougie23fresh/ESPHome-Configs/kauf-plug.yaml

wifi:
  ssid: !secret wifi_ssid
  password: !secret wifi_password
```