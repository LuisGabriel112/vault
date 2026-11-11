---
tipo: proyecto
estado: pausado   # activo | pausado | terminado | descartado
repo: https://github.com/LuisGabriel112/LogiGate
stack: Python (FastAPI), SvelteKit, YOLOv11 + PaddleOCR (NCNN), PostgreSQL, Raspberry Pi 5
actualizado: 2026-11-11
---

# LogiGate

## Objetivo
Control de acceso para patios logísticos del Puerto de Veracruz con visión por computadora: detecta vehículos, lee placas (OCR) y registra entradas/salidas en tiempo real, offline-first. Landing: [[logiLanding]].

## Stack y arquitectura
- Frontend: SvelteKit (`logigate-front/`)
- Backend: FastAPI (`logigate-backend/`)
- DB: PostgreSQL
- Infra / deploy: edge en Raspberry Pi 5 + cámara PoE Hikvision; inferencia YOLOv11 + PaddleOCR vía NCNN

## Estado actual
[completar]

## Pendientes
- [ ] 

## Decisiones

## Diseño
- Design system: [[design-system-LogiGate]]
- Wireframes: ![[]]

## Notas / bitácora
- 2026-11-11: nota creada desde GitHub (README).
