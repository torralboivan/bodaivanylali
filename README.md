[README.md](https://github.com/user-attachments/files/31910669/README.md)
# Boda Iván & Lali — Casa Lumm, Palomino, 27/11/2026

Web estática de la boda. Una sola página, sin dependencias que instalar.

## Archivos

| Archivo | Para qué sirve |
|---|---|
| `index.html` | **La web entera.** Textos, estilos y código, todo aquí dentro |
| `staticwebapp.config.json` | Configuración de Azure Static Web Apps (caché y rutas). No hace falta tocarlo |

## Cómo cambiar algo

1. Abre `index.html` aquí en GitHub y pulsa el lápiz (*Edit this file*).
2. Cambia el texto que hay **entre** las etiquetas, o sea entre un `>` y el siguiente `<`.
3. Abajo del todo, *Commit changes*.
4. En la pestaña **Actions** verás el despliegue. Cuando salga el check verde (1–2 min), la web ya está actualizada.

Busca estas marcas dentro del archivo para lo que más se cambia:

- `[EDITAR-GRUPO]` — enlace de invitación del grupo de WhatsApp
- `[EDITAR-PINTEREST]` — enlace del tablero de Pinterest
- `[EDITAR-WHATSAPP]` — número al que escribe el botón final
- `[EDITAR-FECHA]` — hora de la ceremonia (cuenta atrás)

## Bilingüe

El español es el texto del HTML. El inglés está al final del archivo, en el bloque `var EN = { ... }`.
Cada frase tiene una clave (`data-i18n="d2p"`); si cambias la versión española, cambia la línea con esa
misma clave en el bloque `EN`.

## Deshacer un cambio

Pestaña **Commits** → abre el commit que rompió algo → botón `...` → *Revert*. Vuelve a desplegarse solo.
