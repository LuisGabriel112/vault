---
tipo: proyecto
estado: activo   # activo | pausado | terminado | descartado
repo: https://github.com/LuisGabriel112/cotizaya
stack: TypeScript, Next.js, React, Tailwind, Supabase, Mercado Pago, react-pdf, Vitest, Playwright
actualizado: 2026-11-11
---

# cotizaya

## Objetivo
PWA de cotizaciones para dueños de talleres de aluminio y vidrio en Veracruz: medir en obra, calcular el precio y mandar la cotización (enlace o PDF) por WhatsApp. Fuente: PRODUCT.md (el repo no tiene README).

## Stack y arquitectura
- Frontend: Next.js + React, Tailwind, PWA
- Backend: Next.js (server), Supabase (`@supabase/ssr`), Mercado Pago, PDF con `@react-pdf/renderer`
- DB: Supabase (Postgres)
- Infra / deploy: carpeta `deploy/`, GitHub Actions; tests con Vitest + Playwright

## Estado actual
[completar]

## Pendientes
- [ ] 

## Decisiones

## Diseño
- Design system: [[design-system-cotizaya]]
- Wireframes: ![[]]

## Notas / bitácora
- 2026-11-11: nota creada desde GitHub (PRODUCT.md + package.json).
