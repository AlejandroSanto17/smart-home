# Orden futuro de implementación

Este documento no instala nada todavía. Sirve para evitar improvisación cuando retomemos Casa Inteligente.

## Fase 0 — Seguridad y aislamiento

- Mantener Lúmina y Casa Inteligente en proyectos Docker separados.
- Definir redes Docker independientes.
- Mantener acceso remoto por ZeroTier.
- Configurar estrategia de backups.
- Prohibir secretos en Git.
- Validar firewall y puertos antes de exponer servicios.

## Fase 1 — Base funcional

- Home Assistant Container.
- Mosquitto MQTT.
- HACS.
- Uptime Kuma.
- Integrar dispositivos que ya tenemos.
- Automatización básica de apagón/regreso de energía.

## Fase 2 — Dispositivos locales

- Tuya Local para equipos compatibles.
- ESPHome.
- Primer ESP32 como Bluetooth Proxy/sensor.
- Zigbee2MQTT cuando exista coordinador Zigbee.

## Fase 3 — Energía

- Identificar exactamente el inversor.
- NUT o integración específica si el hardware lo permite.
- PowerCalc.
- Dashboard de red comercial, inversor, batería y consumo.
- Historial de apagones y duración.

## Fase 4 — Presencia inteligente

- Bermuda o ESPresense.
- Sensores mmWave.
- Automatizaciones de iluminación/ventilación basadas en presencia real.

## Fase 5 — Agua

- Nivel de cisterna/tinaco con ESP32.
- Alertas.
- Control de bomba con protecciones e interlocks, solo cuando el hardware eléctrico sea adecuado.

## Fase 6 — Cámaras

- go2rtc.
- Frigate.
- Detección local de personas/vehículos.
- Eventos y notificaciones en Home Assistant.

## Fase 7 — Voz y multimedia

- Whisper/Piper/Wyoming.
- Wake word local.
- Music Assistant.
- Satélites de voz solo después de validar rendimiento del servidor.

## Fase 8 — Red y servicios de casa

- AdGuard Home.
- Métricas más completas.
- Grafana/Prometheus/InfluxDB solo si aportan valor real.

## Fase 9 — Optimización avanzada

- Solar/batería.
- EMHASS.
- Matter/Thread cuando exista necesidad y hardware compatible.
- OpenMQTTGateway/rtl_433 para dispositivos RF.
- Automatización de electrodomésticos por consumo.

## Principio rector

La casa debe seguir funcionando localmente aunque falle Internet. La nube puede complementar, pero no debe convertirse en el punto único de fallo.
