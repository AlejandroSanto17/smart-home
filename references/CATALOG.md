# Catálogo de proyectos para Casa Inteligente

## 1. Núcleo

| Proyecto | Uso previsto |
|---|---|
| [home-assistant/core](https://github.com/home-assistant/core) | Cerebro principal de la casa. |
| [hacs/integration](https://github.com/hacs/integration) | Gestión de integraciones comunitarias. |
| [eclipse-mosquitto/mosquitto](https://github.com/eclipse-mosquitto/mosquitto) | Broker MQTT local. |
| [esphome/esphome](https://github.com/esphome/esphome) | ESP32/ESP8266 y sensores DIY. |
| [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | Red Zigbee sin hubs propietarios. |

## 2. Tuya y dispositivos existentes

| Proyecto | Uso previsto |
|---|---|
| [make-all/tuya-local](https://github.com/make-all/tuya-local) | Control local de dispositivos Tuya compatibles. |
| [rospogrigio/localtuya](https://github.com/rospogrigio/localtuya) | Alternativa/referencia de integración Tuya local. |

## 3. Energía, apagones e inversor

| Proyecto | Uso previsto |
|---|---|
| [networkupstools/nut](https://github.com/networkupstools/nut) | UPS/inversor compatible, estado de línea/batería. |
| [danielrosehill/Home-Assistant-Power-Outage-Automation](https://github.com/danielrosehill/Home-Assistant-Power-Outage-Automation) | Referencia para detectar apagones y retorno de energía. |
| [bramstroker/homeassistant-powercalc](https://github.com/bramstroker/homeassistant-powercalc) | Estimar consumo de dispositivos sin medidor propio. |
| [davidusb-geek/emhass](https://github.com/davidusb-geek/emhass) | Optimización futura de energía, batería y solar. |
| [StephanJoubert/home_assistant_solarman](https://github.com/StephanJoubert/home_assistant_solarman) | Referencia para inversores que utilicen Solarman. |
| [davidrapan/ha-solarman](https://github.com/davidrapan/ha-solarman) | Alternativa Solarman a evaluar si el inversor resulta compatible. |

## 4. Presencia y localización

| Proyecto | Uso previsto |
|---|---|
| [agittins/bermuda](https://github.com/agittins/bermuda) | Presencia/localización BLE por habitaciones. |
| [ESPresense/ESPresense](https://github.com/ESPresense/ESPresense) | Posicionamiento interior basado en ESP32 + MQTT. |
| [r-mccarty/esphome-presence-engine](https://github.com/r-mccarty/esphome-presence-engine) | Presencia mmWave/ESPHome como referencia. |

## 5. Cámaras y seguridad

| Proyecto | Uso previsto |
|---|---|
| [blakeblackshear/frigate](https://github.com/blakeblackshear/frigate) | NVR local con detección de objetos/personas. |
| [AlexxIT/go2rtc](https://github.com/AlexxIT/go2rtc) | Streaming RTSP/WebRTC y baja latencia. |

## 6. Voz y audio

| Proyecto | Uso previsto |
|---|---|
| [OHF-Voice/piper1-gpl](https://github.com/OHF-Voice/piper1-gpl) | Text-to-speech local. |
| [ndom91/local-voice](https://github.com/ndom91/local-voice) | Referencia Docker para Whisper/Piper/Wyoming. |
| [atripathy86/wyoming-whisper-piper-openwakeword](https://github.com/atripathy86/wyoming-whisper-piper-openwakeword) | Referencia para voz local + wake word. |
| [music-assistant/server](https://github.com/music-assistant/server) | Música y altavoces integrados con Home Assistant. |

## 7. Agua, cisterna y tinaco

| Proyecto | Uso previsto |
|---|---|
| [kane5432/ESP32-Water-Level-Sensor](https://github.com/kane5432/ESP32-Water-Level-Sensor) | Medición de nivel de agua con ESP32. |

## 8. Iluminación

| Proyecto | Uso previsto |
|---|---|
| [wled/WLED](https://github.com/wled/WLED) | Tiras LED y escenas controladas localmente. |

## 9. RF, infrarrojo y sensores económicos

| Proyecto | Uso previsto |
|---|---|
| [1technophile/OpenMQTTGateway](https://github.com/1technophile/OpenMQTTGateway) | Puente MQTT para 433/315/868 MHz, IR, BLE y otros. |
| [merbanan/rtl_433](https://github.com/merbanan/rtl_433) | Decodificación de sensores RF de bajo costo. |

## 10. Red y servidor

| Proyecto | Uso previsto |
|---|---|
| [louislam/uptime-kuma](https://github.com/louislam/uptime-kuma) | Monitoreo de Home Assistant, MQTT, Internet y servicios. |
| [AdguardTeam/AdGuardHome](https://github.com/AdguardTeam/AdGuardHome) | DNS local y bloqueo de anuncios/rastreadores. |
| [offen/docker-volume-backup](https://github.com/offen/docker-volume-backup) | Backups de volúmenes Docker. |

## 11. Dashboard

| Proyecto | Uso previsto |
|---|---|
| [piitaya/lovelace-mushroom](https://github.com/piitaya/lovelace-mushroom) | Tarjetas y dashboard moderno de Home Assistant. |
| [dwainscheeren/dwains-dashboard-next](https://github.com/dwainscheeren/dwains-dashboard-next) | Dashboard automático como alternativa/referencia. |

## 12. Automatización de electrodomésticos

| Proyecto | Uso previsto |
|---|---|
| [wroadd/ha-appliance-tracker](https://github.com/wroadd/ha-appliance-tracker) | Detectar ciclos de lavadora/secadora/lavavajillas por consumo. |

## 13. Stacks completos y configuraciones de referencia

| Proyecto | Uso previsto |
|---|---|
| [nsteps/smart-home](https://github.com/nsteps/smart-home) | Arquitectura base: HA + MQTT + Zigbee2MQTT + monitoreo. |
| [Marvin1912/smart-home-infrastructure](https://github.com/Marvin1912/smart-home-infrastructure) | Docker Compose con HA, Grafana, InfluxDB y PostgreSQL. |
| [gcgarner/IOTstack](https://github.com/gcgarner/IOTstack) | Stack IoT Docker de referencia. |
| [frenck/home-assistant-config](https://github.com/frenck/home-assistant-config) | Configuración avanzada de HA para estudiar patrones. |
| [robinbohnen/home-assistant](https://github.com/robinbohnen/home-assistant) | Configuración organizada de Home Assistant por áreas/funciones. |

## Criterios antes de integrar

1. Proyecto activo o suficientemente estable.
2. Compatible con nuestro Ubuntu Server/Docker.
3. Preferencia por funcionamiento local.
4. Sin dependencia innecesaria de nubes externas.
5. No poner en riesgo Lúmina ni sus contenedores.
6. Backups antes de cambios importantes.
7. Secretos únicamente fuera de Git o mediante mecanismos seguros.
8. Evaluar consumo de CPU/RAM antes de Frigate, Whisper u otros servicios pesados.
