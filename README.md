# holy-kebabs-os
Sistema de Operacion para restuarantes

## Contenido

- `index.html` — **Holy Ops**, app de operaciones: checklists por sucursal y turno, reportes del día y panel de administración. Funciona con Firebase (Auth + Realtime Database) o en **modo local** con datos de ejemplo guardados en el navegador.
- `docs/recetario-y-costeo.md` — recetario y costeo de platillos, semielaborados, bebidas e insumos base.

## Correr en local

```bash
python3 -m http.server 8000
open -a Safari "http://localhost:8000/?local=1"
```

`?local=1` fuerza el modo local (sin Firebase). Para usar Firebase, pega tu `firebaseConfig` al inicio del script de `index.html`.
