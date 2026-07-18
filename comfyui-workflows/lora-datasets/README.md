# CCC 4.0 Simple — Datasets por plataforma (LoRA)

Tres workflows de ComfyUI basados en **Custom Character Creator 4.0 Simple** (Mickmumpitz), con prompts y vestuario ajustados a cada plataforma. El objetivo es generar material **consistente en identidad** y **diverso en escena** para entrenar LoRAs.

## Archivos

| Plataforma | Workflow | Carpeta dataset | Nombre personaje |
|---|---|---|---|
| Instagram | `CCC4_SMPL_dataset_instagram.json` | `CCC_instagram` | `v3v3_ig` |
| OnlyFans | `CCC4_SMPL_dataset_onlyfans.json` | `CCC_onlyfans` | `v3v3_of` |
| PornPics | `CCC4_SMPL_dataset_pornpics.json` | `CCC_pornpics` | `v3v3_pp` |

Mapa completo de prompts: [`PROMPTS.md`](./PROMPTS.md)

## Cómo usar

1. Carga el `.json` en ComfyUI (mismos custom nodes/modelos que CCC 4.0 Simple).
2. Pon tu **imagen de referencia** en INPUTS.
3. **`STYLE`** = descripción del personaje. **`CLOTHES`** = atuendo global opcional (se concatena a *todos* los prompts). Úsalo cuando quieras lockear un outfit específico para el dataset (típicamente Instagram / OnlyFans). En PornPics va `nude`.
4. Algunas escenas pueden *override* el outfit (ej. traje de baño en IG, striptease explícito en OF).
5. Cambia `NAME (CHARACTER)` si entrenas varios personajes; deja el `ROOT FOLDER` para no mezclar datasets.
6. Genera las passes y etiqueta después con tu workflow de tagging habitual.

## Qué cambia entre plataformas

### Instagram (`v3v3_ig`)
- Estética lifestyle / influencer, **SFW**.
- `CLOTHES`: outfit IG específico (jeans + camisole, etc.).
- Escenas: brunch, rooftop, resort, fitness, travel.
- Ideal para un LoRA “público” o feed.

### OnlyFans (`v3v3_of`)
- Estética íntima de creadora + **contenido explícito**.
- `CLOTHES`: lencería/bata como base; varias escenas la quitan (striptease, panties aside, mostrando el inicio de la vagina, etc.).
- Escenas: cama, bañera, suite, couch tease, undressing.
- Ideal para un LoRA de contenido suscripción (tease → explícito).

### PornPics (`v3v3_pp`)
- Fotografía adulta explícita; `CLOTHES`: `nude`.
- Poses de glamour hard, outdoor nude, cama, ducha, coche.
- Ideal para un LoRA explícito de galería.

## Qué se mantiene igual (importante para LoRA)

En los tres workflows se conservan las passes de **identidad y geometría**:

- `T-POSE` / `SIDE-WALK` / `BACK-VIEW`
- `CLOSE-FRONT` / `CLOSE-PROFILE`
- Variaciones de expresión (`CLOSE-SMILE`, `CLOSE-SAD`, `CLOSE-ANGRY`)
- Cobertura de iluminación / ángulos

Cada prompt incluye un bloque de **identity lock** para no derivar cara/cuerpo respecto a la referencia.

## Recomendación de entrenamiento

- Entrena **un LoRA por plataforma** si quieres estilos muy distintos, **o**
- Mezcla los tres datasets (con captions claros) si quieres un LoRA versátil con el mismo rostrocuerpo.
- Mantén la misma referencia base en los tres runs para máxima consistencia facial.
- Tras generar, usa tu pipeline de tagging; no está incluido en estos graphs (variant Simple).

## Origen

Derivado de `260713_MICKMUMPITZ_CCC_4-0_SMPL_2084.json`. Solo se retargetearon prompts, `STYLE`, `CLOTHES`, nombres de escena y rutas de salida; la cadena de modelos/nodos es la misma.
