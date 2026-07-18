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
3. Ajusta `STYLE` / `CLOTHES` si quieres, pero cada workflow ya trae defaults de plataforma.
4. Cambia `NAME (CHARACTER)` si entrenas varios personajes; deja el `ROOT FOLDER` para no mezclar datasets.
5. Genera las passes y etiqueta después con tu workflow de tagging habitual.

## Qué cambia entre plataformas

### Instagram (`v3v3_ig`)
- Estética lifestyle / influencer, **SFW**.
- Moda casual chic, brunch, rooftop, resort, fitness, travel.
- Ideal para un LoRA “público” o feed.

### OnlyFans (`v3v3_of`)
- Estética íntima de creadora: lencería, bata, cama, bañera, suite.
- Teasing / boudoir, tono personal y privado.
- Ideal para un LoRA de contenido suscripción.

### PornPics (`v3v3_pp`)
- Fotografía adulta explícita: desnudo de estudio y sets eróticos.
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
