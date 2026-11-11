---
tipo: proyecto
estado: activo   # activo | pausado | terminado | descartado
repo: https://github.com/LuisGabriel112/BitacoraASI
stack: Python, FastAPI, SQLAlchemy async, PostgreSQL (Supabase), SvelteKit (Svelte 5), Docker
actualizado: 2026-11-11
---

# BitacoraASI

## Objetivo
App interna de bitácora de soporte operativo (terminales, aduanas, naviera, control de accesos). Reemplaza el Excel semanal entregado al cliente portuario.

## Stack y arquitectura
- Frontend: SvelteKit + Svelte 5, design tokens propios
- Backend: FastAPI, SQLAlchemy async, integración con Trello
- DB: PostgreSQL en Supabase (migraciones en `supabase/migrations/`); Postgres local opcional vía profile `local-db`
- Infra / deploy: docker-compose (backend + frontend)

## Estado actual
[completar]

## Pendientes
- [ ] 

## Decisiones

## Diseño
- Design system: [[design-system-BitacoraASI]]
- Wireframes: ![[]]

## Notas / bitácora
- 2026-11-11: nota creada desde GitHub (README).
