---
tipo: proyecto
estado: terminado   # activo | pausado | terminado | descartado
repo: https://github.com/LuisGabriel112/loratrack
stack: Python (Django + Channels), Node.js (Fastify, MQTT, lora-packet), MongoDB/PostgreSQL/Redis, app mÃ³vil
actualizado: 2026-11-11
---

# loratrack

## Objetivo
[completar] â€” sin README. Por las dependencias parece rastreo de dispositivos LoRa con mapa (folium, tileserver-gl) y app mÃ³vil.

## Stack y arquitectura
- Frontend: Django + folium; app mÃ³vil (`App Movil Loravil/`)
- Backend: servidor Node (Fastify, WebSocket, MQTT, lora-packet) + Django Channels/Daphne
- DB: MongoDB (djongo), PostgreSQL, Redis
- Infra / deploy: tileserver-gl en Docker

## Estado actual
[completar]

## Pendientes
- [ ] Revisar `.env`, `venv/` y `node_modules/` versionados en el repo; rotar credenciales si el `.env` tiene secretos reales.

## Decisiones

## DiseÃ±o
- Design system: [[design-system-loratrack]]
- Wireframes: ![[]]

## Notas / bitÃ¡cora
- 2026-11-11: nota creada desde GitHub (manifiestos + estructura).
