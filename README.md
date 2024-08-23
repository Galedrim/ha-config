
# Galedrim's Home Assistant config files
Using [HASS-Agent](https://github.com/LAB02-Research/HASS.Agent) on Windows PC and HA on Amazon Fire Tablet.

![image](https://github.com/user-attachments/assets/4fd6f345-74e0-46e8-831b-b98d45905d4b)

## Key Features

- **Xiaomi Roborock Vacuum**: Flashed firmware with [Valetudo](https://valetudo.cloud/pages/installation/roborock.html) communicates via the [MQTT Protocol](https://domopi.eu/faire-communiquer-votre-aspirateur-robot-xiaomi-roborock-en-mqtt) 
- **Google Mini**: Integrated with [YouTube Music Player](https://github.com/KoljaWindeler/ytube_music_player) to manage morning alarm
- **Withings Sleep Analyzer**: Trigger the sleep mode
- **Home Assistant**: Uses the [Lovelace JSON to YAML converter](https://github.com/basnijholt/home-assistant-config?tab=readme-ov-file#lovelace-) for version control

## Device Inventory

### Switches 🔌

| Device         | Quantity |
|----------------|----------|
| TP-Link HS110  | 1        |
| Switchbot Bot  | 1        |

### Sensors 🌡

| Device                      | Quantity |
|-----------------------------|----------|
| Xiaomi Mi Flora             | 1        |
| Switchbot Meter Plus        | 1        |
| Switchbot Motion Sensor     | 1        |
| Switchbot Contact Sensor    | 1        |

### Lights 💡

| Device                          | Quantity |
|---------------------------------|----------|
| Philips Hue E27 White and Color | 2        |
| Philips Hue LED Strip 2m        | 1        |
| Philips Hue E14 White Ambiance  | 1        |

### Hubs 🌍

| Device                   | Quantity |
|--------------------------|----------|
| Switchbot Hub Mini       | 1        |
| Philips Hue Bridge       | 1        |

### Vacuum 🧹

| Device                        | Quantity |
|-------------------------------|----------|
| Xiaomi Mi Roborock V1         | 1        |

### Equipment 🖥

| Device                        | Quantity |
|-------------------------------|----------|
| iPhone 13                     | 1        |
| Withings Sleep Analyzer       | 1        |
| Google Mini                   | 1        |
| Philips Ambilight TV          | 1        |
| Raspberry Pi 3 (1GB RAM)      | 1        |

## Add-ons (Supervised Install Only)

- [Advanced SSH & Web Terminal](https://github.com/hassio-addons/addon-ssh)
- [Cloudflared](https://github.com/brenner-tobias/addon-cloudflared)
- [Home Assistant Google Drive Backup](https://github.com/sabeechen/hassio-google-drive-backup)
- [Mosquitto Broker](https://github.com/home-assistant/addons/tree/master/mosquitto)
- [Samba Share](https://github.com/home-assistant/addons/tree/master/samba)

## HACS Integrations

- [Clock Weather Card](https://github.com/pkissling/clock-weather-card)
- [Mini Graph Card](https://github.com/kalkih/mini-graph-card)
- [Mushroom](https://github.com/piitaya/lovelace-mushroom)
- [YouTube Music Player](https://github.com/KoljaWindeler/ytube_music_player)
