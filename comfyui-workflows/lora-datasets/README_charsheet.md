# Character Sheet — 12 Views

Workflow reducido CCC 4.0 Simple para armar una **hoja de personaje / turnaround** LoRA.

## Archivo

`CCC4_SMPL_charsheet_12view.json`

## Qué genera (12 passes)

### Rostro — close-up, fondo blanco
| Pass | Vista |
|---|---|
| `FACE-FRONT` | Frontal |
| `FACE-LEFT` | Perfil izquierdo 90° |
| `FACE-RIGHT` | Perfil derecho 90° |
| `FACE-BACK` | Trasera (nuca / pelo) |
| `FACE-34-LEFT` | 3/4 izquierda |
| `FACE-34-RIGHT` | 3/4 derecha |

### Cuerpo — full body desnudo, fondo blanco, pose natural relajada
| Pass | Vista |
|---|---|
| `BODY-FRONT` | Frontal |
| `BODY-LEFT` | Perfil izquierdo 90° |
| `BODY-RIGHT` | Perfil derecho 90° |
| `BODY-BACK` | Trasera |
| `BODY-34-LEFT` | 3/4 izquierda |
| `BODY-34-RIGHT` | 3/4 derecha |

## Uso

1. Cargar en ComfyUI (mismos models/nodes que CCC 4.0 Simple).
2. Imagen de referencia + **STYLE**.
3. **CLOTHES vacío**.
4. `NAME (CHARACTER)` por personaje. Root: `CCC_charsheet`.

Titulo al abrir: `CHARACTER SHEET — 12 VIEWS (6 FACE + 6 BODY NUDE)`.
