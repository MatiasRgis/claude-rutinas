# CCC 4.0 Simple — Datasets por plataforma (LoRA)

Tres workflows de ComfyUI basados en **Custom Character Creator 4.0 Simple** (Mickmumpitz).

## Como verificar que cargaste el archivo correcto

El titulo grande del canvas debe decir:

- `INSTAGRAM DATASET — CCC 4.0`
- `ONLYFANS DATASET — CCC 4.0 (EXPLICIT OK)`
- `PORNPICS DATASET — CCC 4.0 (NUDE EXPLICIT)`

Branch: `cursor/platform-lora-datasets-51ac`  
Carpeta: `comfyui-workflows/lora-datasets/`

## CLOTHES (importante)

El campo **CLOTHES está vacío a propósito**.

En CCC, `CLOTHES` se concatena a *todas* las escenas. Si lo llenas, **todas las imagenes salen con la misma ropa** y bajas la variedad del LoRA.

- Deja `CLOTHES` vacio para diversidad.
- La ropa / estado de desnudez va **dentro de cada prompt de escena** (cada pass es distinta).
- Solo rellena `CLOTHES` si quieres entrenar un atuendo fijo a proposito.

## Archivos

| Plataforma | Workflow | Root | Name |
|---|---|---|---|
| Instagram | `CCC4_SMPL_dataset_instagram.json` | `CCC_instagram` | `v3v3_ig` |
| OnlyFans | `CCC4_SMPL_dataset_onlyfans.json` | `CCC_onlyfans` | `v3v3_of` |
| PornPics | `CCC4_SMPL_dataset_pornpics.json` | `CCC_pornpics` | `v3v3_pp` |

Mapa de prompts: [`PROMPTS.md`](./PROMPTS.md)

## Contenido por plataforma

### Instagram
Lifestyle SFW con **ropa distinta por escena** (jeans, trench, yoga set, swimsuit, blazer, running gear, etc.).

### OnlyFans
Intimo + **explicito**: lenceria variada, striptease, panties aside, mostrando el inicio de la vagina, etc. Ropa/estado distinto por escena.

### PornPics
Sets explicitos mayormente nude, con pequena variedad (heels, boots, waist chain, barefoot).

## Identidad LoRA

Se mantienen passes de identidad: T-POSE, SIDE/BACK, CLOSE-FRONT/PROFILE, expresiones e iluminacion.
