# Promesómetro — Patria Milagro 🇨🇴

Veeduría ciudadana independiente del programa de gobierno de Abelardo de la Espriella (2026–2030).

## ¿Qué es?

PWA de seguimiento de las promesas del programa *Patria Milagro*, actualizable semana a semana por el administrador editando el array `PROMESAS` en el JS del archivo principal.

## Estados posibles

| Estado | Significado |
|---|---|
| ✅ `cumplida` | Promesa ejecutada y verificable |
| 🔄 `proceso` | En trámite, con acciones concretas |
| ❌ `incumplida` | Plazo vencido sin cumplimiento |
| ⏳ `pendiente` | Sin acciones concretas aún |

## Archivos

- `promesometro.html` — App principal (renombrar a `index.html` en GitHub Pages)
- `sw.js` — Service Worker para funcionamiento offline
- `manifest.json` — Manifest PWA (instalable en celular)

## Cómo actualizar

1. Abre `promesometro.html`
2. Busca el array `const PROMESAS = [...]`
3. Cambia el campo `estado` de cada promesa
4. Actualiza el campo `detalle` con la información nueva
5. Actualiza el campo `fecha`
6. Sube a GitHub Pages

## Despliegue

Repositorio: `haroldco45/promesometro`  
URL: `https://haroldco45.github.io/promesometro/`

---

**Desarrollada por Vibras Positivas HM — Derechos de Autor Reservados**
