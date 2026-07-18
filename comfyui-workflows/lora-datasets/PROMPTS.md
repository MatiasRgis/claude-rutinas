# LoRA Dataset Workflows — Platform Prompt Map

`CLOTHES` is a **global outfit** appended to every scene prompt (`style + prompt + clothes`). Use it to lock one specific look for the dataset. Scene prompts may override for special shots.

| Platform | Workflow file | Root folder | Character name | CLOTHES |
|---|---|---|---|---|
| instagram | `CCC4_SMPL_dataset_instagram.json` | `CCC_instagram` | `v3v3_ig` | `wearing a specific Instagram outfit: high-waisted light-wash jeans, cream silk camisole, gold hoop earrings, clean white sneakers` |
| onlyfans | `CCC4_SMPL_dataset_onlyfans.json` | `CCC_onlyfans` | `v3v3_of` | `wearing a specific OnlyFans outfit: sheer black lace bra and matching panties, open silk robe slipping off one shoulder` |
| pornpics | `CCC4_SMPL_dataset_pornpics.json` | `CCC_pornpics` | `v3v3_pp` | `nude` |

## INSTAGRAM

**STYLE:** A beautiful 35-year-old woman, slim with blue eyes, natural and small breasts, soft glam makeup, healthy glowing skin, influencer aesthetic

**CLOTHES (global):** wearing a specific Instagram outfit: high-waisted light-wash jeans, cream silk camisole, gold hoop earrings, clean white sneakers

### `T-POSE`

```
Show this exact character in a full body pose in front of a soft neutral light-gray studio background. The character is standing full body in a frontal A-pose, looking into the camera with a neutral expression and closed mouth. A full body view from head to feet. Force the character into an A-pose. Clean Instagram catalog lighting.

Camera full body portrait
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `SIDE-WALK`

```
Show this character walking confidently from the right side of the image to the left side on a sunlit city sidewalk, medium-full shot. Natural stride, relaxed arms, soft street bokeh, lifestyle street style photography.

FULL BODY PORTRAIT SIDE VIEW
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `BACK-VIEW`

```
Turn the character around to create a back view. Relaxed pose, arms hanging down. Show this exact character in a full body pose from the back in a bright minimal studio.

The background is soft neutral white-gray.

FULL BODY BACK VIEW OF THE CHARACTER
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `CLOSE-FRONT`

```
Extreme close-up of the character's frontal face against a clean soft white background, neutral soft smile barely closed lips, frontal view. The head fills the entire frame, face visible in detail. Soft beauty lighting from camera left. No hands visible. Symmetrical front view looking directly into the camera.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `CLOSE-PROFILE`

```
Extreme close-up, side profile portrait of the character against a clean soft white background. Neutral relaxed pose. The head and shoulders fill the entire frame. The character faces left in a 90-degree profile, so only one side of the face is visible. Soft daylight beauty lighting.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `BACKLIT-YOGA`

```
A medium close-up: hard golden sunlight from behind creates a glowing rim light and soft lens haze. The character is in a calm yoga meditation pose with eyes closed on a bright apartment balcony. Warm Instagram golden-hour color grade.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `CLOSE-ANGRY`

```
A close-up against a modern concrete wall: make the character show an intense, fierce expression with a slightly open mouth mid-sentence, as if calling someone out. Strong side light. Fashion editorial attitude, not cartoonish.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `CLOSE-SAD`

```
A close-up in front of a rainy cafe window with soft reflections: make the character have a quiet melancholic expression, eyes slightly glassy, lips closed. Moody blue-gray Instagram cinematic grade.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `CLOSE-SMILE`

```
A close-up in a sunny wildflower meadow with distant alpine mountains: make the character smile with an open mouth, joyful and natural. Strong sunlight lights one side of the face, the other side is softer. Authentic lifestyle smile, teeth visible.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `GOLDEN-HOUR`

```
Wide lifestyle shot: the character stands on a rooftop terrace at golden hour, city skyline soft behind her. She holds a disposable camera at chest height and looks off-camera with a soft smile. Warm rim light, filmic Instagram color. Medium-wide shot, full outfit visible.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `BALCONY-BRUNCH`

```
The character sits at a small balcony table with avocado toast and an iced matcha, laughing mid-conversation. Morning sunlight creates crisp shadows on light wood. Wide-enough shot to show upper body and table setting. Fresh brunch influencer vibe.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `RESORT-POOL`

```
Override clothes for this shot only: tasteful one-piece swimsuit. The character lounges on the edge of a luxury resort infinity pool, legs in the water, hair wet and slicked back. Bright midday sun, turquoise water, palm reflections. Full body visible, vacation Instagram aesthetic. No nudity.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `FARMERS-MARKET`

```
Wide shot at a sunny farmers market: the character holds a paper bag of oranges and bites into a fresh pastry. Soft crowd bokeh, colorful produce stalls, casual weekend energy. Natural candid pose.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `BOUTIQUE`

```
Medium shot inside a bright fashion boutique: the character stands before a tall mirror holding a garment hanger, checking the fit. Clean marble floor, soft boutique lighting, elevated street-style mood. Looking slightly toward the mirror, not the camera.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `CAFE-LATTE`

```
Close-up of the character's hands wrapping around a ceramic latte cup with latte art. Steam rises. Her upper body soft in the background of a sunlit specialty cafe. Hands and cup dominate the frame. Lifestyle detail shot.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `MIRROR-SELFIE`

```
Front-facing mirror selfie aesthetic in a bright bedroom: the character holds a phone at chest height (phone mostly out of frame or edge-visible), soft natural window light, tidy white bedding behind her. Flattering medium shot, cute confident expression. Tasteful and clothed.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `AIRPORT-TRAVEL`

```
Medium-wide shot in a bright modern airport terminal: the character walks with a small carry-on suitcase, passport in one hand, looking up at departure boards. Large glass windows, travel lifestyle photography, clean daylight.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `SOFA-EDITORIAL`

```
A full body wide shot: the character reclines on a modern cream sofa in an airy loft, head resting on her hand in a soft model pose. Soft backlight from sheer white curtains, gentle haze. Editorial lifestyle, full body visible on the sofa.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `SURPRISED-ANGLE`

```
A high angle wide shot looking down at the character on a sunny plaza. Make her look pleasantly surprised, mouth open in a natural laugh. Completely change the perspective to a clear high angle. Bright Instagram daytime grade.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `CITY-LOOKUP`

```
A full body wide shot of the character looking up into a bright sky between glass office towers. Hands on hips, confident posture. Dramatic but clean daylight. FULL BODY VISIBLE, SHOES VISIBLE. Urban aspirational Instagram look.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `ROOFTOP-PARTY`

```
Medium shot on a stylish rooftop party at dusk: the character holds a sparkling drink, city lights blooming behind her. Soft string lights, candid social smile. Tasteful nightlife, not club smut.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `FITNESS-RUN`

```
Override clothes for this shot only: fitted athletic sportswear. Medium close-up of the character mid-run on a waterfront boardwalk at sunrise. Dynamic running pose, wind in hair, pink-orange sky. Fitness influencer energy, focused expression.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `CONVERTIBLE-NIGHT`

```
Wide night shot: the character leans casually against a sleek convertible parked under warm streetlights. Clean reflections on the car body, confident relaxed pose, full body visible. Cinematic city nightlife, glamorous but SFW.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `TRAVEL-CANYON`

```
Back view of the character overlooking a national park canyon at late afternoon. Arms raised above her head in a triumphant stretch. Vast landscape, travel content energy.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

## ONLYFANS

**STYLE:** A beautiful 35-year-old woman, slim with blue eyes, natural and small breasts, soft skin, intimate bedroom creator aesthetic, flirty and personal

**CLOTHES (global):** wearing a specific OnlyFans outfit: sheer black lace bra and matching panties, open silk robe slipping off one shoulder

### `T-POSE`

```
Show this exact character in a full body pose in front of a warm neutral bedroom wall. The character is standing full body in a frontal A-pose, looking into the camera with a soft flirty neutral expression and closed mouth. Full body from head to feet. Force an A-pose for dataset consistency. Soft intimate lamp lighting.

Camera full body portrait
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `SIDE-WALK`

```
Show this character walking slowly and seductively from right to left across a softly lit private loft, medium-full shot. Natural hip sway, relaxed arms, intimate creator-home atmosphere.

FULL BODY PORTRAIT SIDE VIEW
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `BACK-VIEW`

```
Turn the character around to create a back view. Relaxed pose, arms hanging down. Full body back view in a dim cozy bedroom. Soft practical lights.

The background is a warm neutral wall.

FULL BODY BACK VIEW OF THE CHARACTER
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `CLOSE-FRONT`

```
Extreme close-up of the character's frontal face against a soft bedroom background blur, intimate eye contact, lips slightly parted in a teasing almost-smile. Head fills the frame. Warm practical lighting. No hands visible.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `CLOSE-PROFILE`

```
Extreme close-up, side profile of the character against a dim warm wall. Neutral relaxed sensual expression. Head and shoulders fill the frame, 90-degree left profile. Soft lamp light grazing the cheekbone.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `BACKLIT-ROBE`

```
Medium close-up: strong backlight from a bright window turns the character into a soft silhouette with glowing edges. Open robe, eyes closed, quiet and sensual. Bedroom morning mood.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `CLOSE-ANGRY`

```
Close-up: make the character show a playful jealous pout turning into a fierce flirty glare, mouth slightly open. Soft pink bedroom lighting. Expressive and personal, not horror.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `CLOSE-SAD`

```
Close-up on the character sitting against headboard pillows at night: vulnerable soft sad eyes, closed mouth, phone light faintly coloring her face. Intimate late-night creator mood.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `CLOSE-SMILE`

```
Close-up: make the character smile with an open mouth, warm and inviting, as if greeting a subscriber. Soft window light on one cheek, gentle shadow on the other. Personal and affectionate.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `WINDOW-SILHOUETTE`

```
Medium shot: the character stands before floor-to-ceiling windows at dusk, city glow outside. Semi-sheer robe, body softly backlit, one hand on the glass, looking back over her shoulder toward camera. Intimate silhouette tease.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `KITCHEN-ROBE`

```
The character sits on a kitchen counter in an oversized open robe, holding a mug, legs dangling, morning light from the side. Casual domestic tease, smiling softly at camera. Medium-wide shot.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `OUTDOOR-SUNBED`

```
Override clothes for this shot: tiny string bikini being pulled aside. The character reclines on a private villa sunbed, skin glistening with oil, and uses her fingers to pull the bikini bottom to the side, revealing the top of her vagina and pubic area. Hot sunlight, explicit vacation OnlyFans content, looking at camera.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `COUCH-TEASE`

```
Wide-enough living room shot: the character lounges on a couch, panties slid down to mid-thigh, robe open, one knee up. She casually shows the beginning of her vagina to the camera with a knowing smile. Soft lamp light, private apartment, explicit tease.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `DESK-LINGERIE`

```
Medium shot: the character sits on a home-office desk edge in lingerie and heels, leaning toward the camera. With one hand she pulls her panties aside just enough to expose the start of her pussy lips. Laptop open beside her. Explicit creator-at-work aesthetic.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `MORNING-COFFEE`

```
Close-up of the character's hands holding a steaming mug against her chest, open robe, soft cleavage. Morning bedroom bokeh behind her. Intimate detail shot, warm tones.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `BED-EXPLICIT`

```
Frontal shot of the character on rumpled white sheets, bra off, panties pulled down around her knees. She spreads her thighs slightly and shows the beginning of her vagina to camera, soft teasing eye contact. Moody evening lamps. Explicit OnlyFans bed content.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `BATHTUB-STEAM`

```
Medium shot: the character in a steamy bathtub, water low enough that her bare breasts and the top of her vagina are visible above the waterline, wet hair, arms on the tub edge, looking at camera through soft steam. Explicit intimate bath content.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `STRIPTEASE`

```
Striptease sequence pose: low angle full-body shot. The character is mid-undress — bra unclasped and falling, panties being slid down her hips with both hands, revealing bare breasts and the start of her vagina. Looking down at the camera with a dominant teasing smile. Soft practical lights, private apartment. Explicit.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `BED-OVERHEAD`

```
High angle shot looking down at the character lying on a bed, surprised playful expression with open mouth. Lingerie half-off: one breast bare, panties tugged to the side exposing the beginning of her vagina. Sheets messy. Clear overhead perspective. Explicit.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `BALCONY-NIGHT`

```
Full body night balcony shot: the character looks upward, hands on the railing, city lights below. Sheer robe open, panties pulled down slightly so the top of her vagina is visible. Dramatic cool/warm mixed lighting. FULL BODY VISIBLE. Explicit tease.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `HOTEL-SUITE`

```
Medium shot in a luxury hotel suite: the character sits on the edge of a wide bed holding champagne. She is undressing — robe off, bra discarded beside her, panties hooked by a thumb and dragged down to show the start of her pussy. Neon city color through curtains. Explicit seductive pose.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `SHOWER-EXPLICIT`

```
Medium close-up through fogged shower glass: the character rinses her hair under the shower, fully nude and wet, one leg lifted so the beginning of her vagina is faintly visible through droplets and steam. Explicit intimate bathroom lighting.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `CAR-BACKSEAT`

```
Wide night shot: the character lounges across a car back seat with the door open, coat open, lingerie half-removed. Legs parted just enough to show the top of her vagina, streetlights and wet asphalt reflections. Risky explicit private content, cinematic.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `MIRROR-BOUDOIR`

```
Back-to-mirror boudoir: the character faces a large mirror, looking at her reflection while pulling her panties down from behind, bare ass and a hint of her vagina visible between her thighs. Warm vanity lights, arms busy with the undress. Explicit self-admiration.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

## PORNPICS

**STYLE:** A beautiful 35-year-old woman, slim with blue eyes, natural and small breasts, smooth skin, erotic photography model, explicit adult glamour

**CLOTHES (global):** nude

### `T-POSE`

```
Show this exact character fully nude in a full body frontal A-pose on a seamless white photography backdrop. Neutral expression, closed mouth, looking into camera. Full body from head to feet visible for dataset consistency. Clean studio softboxes.

Camera full body portrait
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `SIDE-WALK`

```
Show this nude character walking relaxed from right to left in a white cyclorama studio, medium-full shot. Natural gait, arms relaxed, explicit side view of body for adult dataset coverage.

FULL BODY PORTRAIT SIDE VIEW
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `BACK-VIEW`

```
Turn the nude character around for a full body back view. Relaxed pose, arms hanging down, buttocks and back clearly visible. Neutral white seamless background.

FULL BODY BACK VIEW OF THE CHARACTER
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `CLOSE-FRONT`

```
Extreme close-up of the character's frontal face against plain white, neutral expression, frontal view. Head fills the frame for facial identity lock. Soft even studio light. No hands. Looking into camera.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `CLOSE-PROFILE`

```
Extreme close-up side profile of the character's head and bare shoulders against plain white. 90-degree left profile, neutral expression. Head and shoulders fill the frame. Clean studio light.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `BACKLIT-NUDE`

```
Medium close-up nude portrait with hard backlight and deep facial shadow. Eyes closed, chin slightly lifted, erotic stillness. Rim light outlines breasts and collarbones.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `CLOSE-ANGRY`

```
Close-up nude portrait: furious intense expression, mouth open mid-moan/shout hybrid, brows knitted. White seamless background. Strong contrast lighting. Keep face identity locked.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `CLOSE-SAD`

```
Close-up nude portrait with a vulnerable sad expression against a dark moody backdrop. Soft tears-at-the-brink look, closed mouth. Adult fine-art erotic mood.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `CLOSE-SMILE`

```
Close-up nude portrait: open-mouth smile, playful erotic confidence. Half the face in hard sunlight, half in shadow, outdoor-studio hybrid feel. Teeth visible.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `STUDIO-NUDE`

```
Full body erotic studio shot: the nude character stands in a classic hand-on-hip glamour pose on seamless paper, three-point lighting, explicit frontal nudity including breasts and vagina, confident eye contact. PornPics-style clean set photo.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `CHAISE-NUDE`

```
The nude character reclines on a velvet chaise lounge, one knee bent, arm behind her head, explicit body display including vagina. Soft window light and warm interior. Full body erotic furniture pose.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `BEACH-NUDE`

```
The nude character sits on a beach rock at the waterline, fully nude and wet, vagina visible, waves splashing behind her. Sunlit explicit outdoor nudity, looking at camera. Adult beach set photography.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `OUTDOOR-NUDE`

```
Wide erotic outdoor shot: the nude character sits on a secluded park bench in dappled light, legs crossed then slightly parted, openly nude with vagina visible. Soft nature bokeh. Explicit candid adult photography look.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `DESK-NUDE`

```
Medium erotic shot: the nude character sits on a marble office desk, legs parted slightly showing her vagina, looking toward camera. City skyline through windows at midday. Explicit desk glamour set.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `HANDS-BODY`

```
Close-up detail of the nude character's hands sliding over her own waist, hip and the top of her vagina, skin and body filling most of the frame, face softly out of focus in background. Explicit body-detail dataset shot.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `BED-EXPLICIT`

```
Frontal high angle of the nude character lying relaxed on a hotel bed, eyes closed, one arm above her head, explicit breasts and vagina visible. Dark moody evening lighting. Classic adult bed set.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `SHOWER-NUDE`

```
Medium shot of the nude character in a modern glass shower, water streaming over her body, one hand on the glass, vagina visible, erotic wet look, steamy bathroom. Explicit shower set photography.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `ARCHED-POSE`

```
Full body low-angle erotic pose: the nude character arches on all fours on a clean floor looking back toward camera, vagina and ass visible. Dramatic upward perspective, studio lighting. Explicit arched pose.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `SPREAD-ANGLE`

```
High angle wide shot of the nude character on the floor looking up surprised with an open mouth, legs open enough to show her vagina. Explicit body layout clearly visible from above. Strong perspective change for dataset variety.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `STANDING-NUDE`

```
Full body wide shot of the nude character standing outdoors looking up into open sky, hands on hips, vagina visible, dramatic clouds. Explicit standing nude, feet visible. FULL BODY VISIBLE.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `NEON-NUDE`

```
Medium erotic shot: the nude character leans against a neon-lit private lounge wall holding a drink, colored gels on skin, dark background, breasts and vagina visible. Explicit adult nightlife set.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `WETLOOK-NUDE`

```
Medium close-up of the nude character in a dynamic wetlook pose after rain at an abandoned industrial site at dusk, body glistening, vagina visible, last red glow on the horizon. Explicit, cinematic, dangerous mood.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `HOOD-CAR-NUDE`

```
Wide night erotic shot: the nude character leans back on a car hood, legs open, vagina visible, city lights and clean reflections on the paint. Explicit automotive glamour set.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```

### `OUTDOOR-BACK`

```
Back view of the nude character overlooking a canyon, arms raised high above her head, explicit rear nude with vagina hint between thighs against vast landscape. Late-day warm light. Adult outdoor back pose.
Show this exact character from the reference image. Match style, skin tone, hairstyle, facial structure and body proportions exactly. Do not change the character's identity. Keep the character perfectly consistent.
```
