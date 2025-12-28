# dwm 6.5 – Custom build

Este repositorio contiene mi build personalizada de **dwm 6.5** (suckless),
con parches aplicados y configuraciones propias.

El objetivo es mantener:
- la versión base estable (`6.5`)
- los parches documentados
- una configuración clara y reproducible

---

## Versión

- **dwm**: 6.5
- **Base**: upstream suckless
- **Branch activa**: `dwm-6.5`

---

## Patches aplicados

Los parches originales se guardan en el directorio `patches/`.

### ✔ vanitygaps
- Permite agregar **gaps (espacios)** entre ventanas
- Soporta:
  - gaps internos / externos
  - activación/desactivación por keybinding
- Patch original: `dwm-vanitygaps-6.5.diff`

---

## Estructura del repositorio

```text
.
├── dwm.c
├── config.def.h
├── config.h
├── patches/
│   ├── dwm-vanitygaps-6.5.diff
│   └── README.md
└── README.md
