# ESPHome-Configs
ESPHome Configs Yaml Files



```
substitutions:
  name: bedroom-lamp
  friendly_name: Bedroom Lamp
  
  sub_pm_sel_pin:   GPIO12
  sub_pm_cf_pin:    GPIO5
  sub_pm_cf1_pin:   GPIO14
  sub_button_pin:   GPIO13
  sub_blue_led_pin: GPIO2
  sub_red_led_pin:  GPIO0
  sub_relay_pin:    GPIO4

packages:
  kauf.plf10: github://dougie23fresh/ESPHome-Configs/kauf-plug.yaml

wifi:
  ssid: !secret wifi_ssid
  password: !secret wifi_password
```
