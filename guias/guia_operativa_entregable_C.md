# Guía operativa — Entregable C

Este archivo te dice exactamente qué copiar/pegar en cada herramienta para las 6 escenas seleccionadas del Entregable C.

## Escenas seleccionadas
- H1: S01 y S08
- H2: S01 y S08
- H3: S01 y S07

## Reglas generales
- Mantén **las mismas escenas** en las tres herramientas core.
- Guarda **1 imagen final por escena y herramienta**.
- Si una herramienta no permite `seed` o `negative prompt`, deja `N/A` en bitácora.
- No hagas upscales ni edición avanzada en esta primera ronda.

## 1) ChatGPT Images — qué escribir exactamente
Usa un chat nuevo solo para imágenes. Pega el prompt completo de cada escena. Al final añade la instrucción de formato: `Generate 1 horizontal image, aspect ratio ... , no visible text.`

### ChatGPT — H1_S01 — Ronda en el pasillo de mantenimiento

Cinematic realistic sci-fi; cool lighting; blue/gray tones; high detail; moderate contrast. Scene S01 from 'La Estación de Niebla'. Mara checks a panel in a metallic corridor covered by a thin technical fog. Characters: Mara. Visual goal: Introduce Mara, the environment, and the atmosphere of anomaly. Location: Maintenance corridor. Time: Orbital night. Shot: Wide shot / short tracking move. Keep consistency anchors: Mara: short black hair with a silver streak, dark gray technical uniform with cyan lines, left bracelet. ARCO: translucent blue hologram. Generate 1 horizontal image, aspect ratio 16:9. No visible text. Avoid: no visible text unless requested, deformed hands, incorrect anatomy, duplicate elements, glitches, excessive noise, low resolution, strong blur, inconsistent faces, dominant warm colors.

### ChatGPT — H1_S08 — La estructura oculta

Cinematic realistic sci-fi; cool lighting; blue/gray tones; high detail; moderate contrast. Scene S08 from 'La Estación de Niebla'. From a large window, Mara observes the megastructure connected to the station, previously hidden behind the fog. Characters: Mara, ARCO. Visual goal: Close with a revelation and open the next phase. Location: Exterior observation deck. Time: After the lockdown. Shot: Extreme wide shot / backlighting. Keep consistency anchors: Mara: short black hair with a silver streak, dark gray technical uniform with cyan lines, left bracelet. ARCO: translucent blue hologram. Generate 1 horizontal image, aspect ratio 16:9. No visible text. Avoid: no visible text unless requested, deformed hands, incorrect anatomy, duplicate elements, glitches, excessive noise, low resolution, strong blur, inconsistent faces, dominant warm colors.

### ChatGPT — H2_S01 — Brillar más alto

Soft storybook illustration; warm palette; watercolor textures; clear expressions; clean composition. Scene S01 from 'La Luciérnaga y el Río'. Lumi intensifies her light in the middle of the night forest while the others watch her. Characters: Lumi. Visual goal: Introduce Lumi and her desire to stand out. Location: Forest clearing. Time: Night. Shot: Child-friendly wide shot / centered composition. Keep consistency anchors: Lumi: amber-gold firefly with a small leaf-green scarf, translucent wings, large eyes. Group: 2-3 warm-toned fireflies. River: wise non-literal reflection. Generate 1 horizontal image, aspect ratio 4:3. No visible text. Avoid: harsh realism, horror, violence, grotesque insect anatomy, text, noise, cluttered background, extreme saturation, aggressive expressions.

### ChatGPT — H2_S08 — El camino iluminado

Soft storybook illustration; warm palette; watercolor textures; clear expressions; clean composition. Scene S08 from 'La Luciérnaga y el Río'. Many small lights form a bright, harmonious path into the forest. Characters: Lumi. Visual goal: Close with a clear visual moral. Location: Main path. Time: Late night. Shot: Poetic extreme wide shot. Keep consistency anchors: Lumi: amber-gold firefly with a small leaf-green scarf, translucent wings, large eyes. Group: 2-3 warm-toned fireflies. River: wise non-literal reflection. Generate 1 horizontal image, aspect ratio 4:3. No visible text. Avoid: harsh realism, horror, violence, grotesque insect anatomy, text, noise, cluttered background, extreme saturation, aggressive expressions.

### ChatGPT — H3_S01 — El mapa despierta

Colorful semi-realistic adventure; sunset light; dynamic compositions; a sense of wind and movement. Scene S01 from 'El Mapa del Viento'. A gust opens the map in the town square and reveals a shifting route. Characters: Nico, Sara. Visual goal: Present the artifact and the inciting event of the adventure. Location: Town square. Time: Afternoon. Shot: Wide shot with central action. Keep consistency anchors: Nico: light brown jacket, green backpack, compass. Sara: dark teal scarf, cream notebook. Map: ancient parchment with blue-green lines activated by the wind. Generate 1 horizontal image, aspect ratio 16:9. No visible text. Avoid: explicit violence, unwanted text, incorrect anatomy, duplicate elements, blur, flat lighting, inconsistent wardrobe, generic map without magical glowing lines.

### ChatGPT — H3_S07 — La biblioteca perdida

Colorful semi-realistic adventure; sunset light; dynamic compositions; a sense of wind and movement. Scene S07 from 'El Mapa del Viento'. Inside, the books and golden dust create a silent yet living atmosphere. Characters: Nico, Sara. Visual goal: Reveal the treasure and slow the pace with wonder. Location: Inside the library. Time: Timeless interior. Shot: Wide shot with depth. Keep consistency anchors: Nico: light brown jacket, green backpack, compass. Sara: dark teal scarf, cream notebook. Map: ancient parchment with blue-green lines activated by the wind. Generate 1 horizontal image, aspect ratio 16:9. No visible text. Avoid: explicit violence, unwanted text, incorrect anatomy, duplicate elements, blur, flat lighting, inconsistent wardrobe, generic map without magical glowing lines.

## 2) Leonardo Free (Phoenix) — qué escribir exactamente
Configura: modelo `Phoenix`, prompt enhance `OFF` si existe, ratio según escena, seed según historia, 4 variaciones. Usa el prompt en inglés y el negative prompt en su campo separado.

### Leonardo — H1_S01 — Ronda en el pasillo de mantenimiento
- **Prompt:** Cinematic realistic sci-fi; cool lighting; blue/gray tones; high detail; moderate contrast. Scene S01 from 'La Estación de Niebla'. Mara checks a panel in a metallic corridor covered by a thin technical fog. Characters: Mara. Visual goal: Introduce Mara, the environment, and the atmosphere of anomaly. Location: Maintenance corridor. Time: Orbital night. Shot: Wide shot / short tracking move. Keep consistency anchors: Mara: short black hair with a silver streak, dark gray technical uniform with cyan lines, left bracelet. ARCO: translucent blue hologram.
- **Negative prompt:** no visible text unless requested, deformed hands, incorrect anatomy, duplicate elements, glitches, excessive noise, low resolution, strong blur, inconsistent faces, dominant warm colors
- **Aspect ratio:** 16:9
- **Seed:** 1101
- **Variaciones:** 4

### Leonardo — H1_S08 — La estructura oculta
- **Prompt:** Cinematic realistic sci-fi; cool lighting; blue/gray tones; high detail; moderate contrast. Scene S08 from 'La Estación de Niebla'. From a large window, Mara observes the megastructure connected to the station, previously hidden behind the fog. Characters: Mara, ARCO. Visual goal: Close with a revelation and open the next phase. Location: Exterior observation deck. Time: After the lockdown. Shot: Extreme wide shot / backlighting. Keep consistency anchors: Mara: short black hair with a silver streak, dark gray technical uniform with cyan lines, left bracelet. ARCO: translucent blue hologram.
- **Negative prompt:** no visible text unless requested, deformed hands, incorrect anatomy, duplicate elements, glitches, excessive noise, low resolution, strong blur, inconsistent faces, dominant warm colors
- **Aspect ratio:** 16:9
- **Seed:** 1101
- **Variaciones:** 4

### Leonardo — H2_S01 — Brillar más alto
- **Prompt:** Soft storybook illustration; warm palette; watercolor textures; clear expressions; clean composition. Scene S01 from 'La Luciérnaga y el Río'. Lumi intensifies her light in the middle of the night forest while the others watch her. Characters: Lumi. Visual goal: Introduce Lumi and her desire to stand out. Location: Forest clearing. Time: Night. Shot: Child-friendly wide shot / centered composition. Keep consistency anchors: Lumi: amber-gold firefly with a small leaf-green scarf, translucent wings, large eyes. Group: 2-3 warm-toned fireflies. River: wise non-literal reflection.
- **Negative prompt:** harsh realism, horror, violence, grotesque insect anatomy, text, noise, cluttered background, extreme saturation, aggressive expressions
- **Aspect ratio:** 4:3
- **Seed:** 2202
- **Variaciones:** 4

### Leonardo — H2_S08 — El camino iluminado
- **Prompt:** Soft storybook illustration; warm palette; watercolor textures; clear expressions; clean composition. Scene S08 from 'La Luciérnaga y el Río'. Many small lights form a bright, harmonious path into the forest. Characters: Lumi. Visual goal: Close with a clear visual moral. Location: Main path. Time: Late night. Shot: Poetic extreme wide shot. Keep consistency anchors: Lumi: amber-gold firefly with a small leaf-green scarf, translucent wings, large eyes. Group: 2-3 warm-toned fireflies. River: wise non-literal reflection.
- **Negative prompt:** harsh realism, horror, violence, grotesque insect anatomy, text, noise, cluttered background, extreme saturation, aggressive expressions
- **Aspect ratio:** 4:3
- **Seed:** 2202
- **Variaciones:** 4

### Leonardo — H3_S01 — El mapa despierta
- **Prompt:** Colorful semi-realistic adventure; sunset light; dynamic compositions; a sense of wind and movement. Scene S01 from 'El Mapa del Viento'. A gust opens the map in the town square and reveals a shifting route. Characters: Nico, Sara. Visual goal: Present the artifact and the inciting event of the adventure. Location: Town square. Time: Afternoon. Shot: Wide shot with central action. Keep consistency anchors: Nico: light brown jacket, green backpack, compass. Sara: dark teal scarf, cream notebook. Map: ancient parchment with blue-green lines activated by the wind.
- **Negative prompt:** explicit violence, unwanted text, incorrect anatomy, duplicate elements, blur, flat lighting, inconsistent wardrobe, generic map without magical glowing lines
- **Aspect ratio:** 16:9
- **Seed:** 3303
- **Variaciones:** 4

### Leonardo — H3_S07 — La biblioteca perdida
- **Prompt:** Colorful semi-realistic adventure; sunset light; dynamic compositions; a sense of wind and movement. Scene S07 from 'El Mapa del Viento'. Inside, the books and golden dust create a silent yet living atmosphere. Characters: Nico, Sara. Visual goal: Reveal the treasure and slow the pace with wonder. Location: Inside the library. Time: Timeless interior. Shot: Wide shot with depth. Keep consistency anchors: Nico: light brown jacket, green backpack, compass. Sara: dark teal scarf, cream notebook. Map: ancient parchment with blue-green lines activated by the wind.
- **Negative prompt:** explicit violence, unwanted text, incorrect anatomy, duplicate elements, blur, flat lighting, inconsistent wardrobe, generic map without magical glowing lines
- **Aspect ratio:** 16:9
- **Seed:** 3303
- **Variaciones:** 4

## 3) Ideogram Free — qué escribir exactamente
En Ideogram Free usa el prompt en inglés. Si no aparece campo de negative prompt o seed, no inventes el dato; deja `N/A` en bitácora. Añade dentro del prompt `No visible text.` al final.

### Ideogram — H1_S01 — Ronda en el pasillo de mantenimiento

Cinematic realistic sci-fi; cool lighting; blue/gray tones; high detail; moderate contrast. Scene S01 from 'La Estación de Niebla'. Mara checks a panel in a metallic corridor covered by a thin technical fog. Characters: Mara. Visual goal: Introduce Mara, the environment, and the atmosphere of anomaly. Location: Maintenance corridor. Time: Orbital night. Shot: Wide shot / short tracking move. Keep consistency anchors: Mara: short black hair with a silver streak, dark gray technical uniform with cyan lines, left bracelet. ARCO: translucent blue hologram. No visible text. Keep composition clean. Aspect ratio 16:9.

### Ideogram — H1_S08 — La estructura oculta

Cinematic realistic sci-fi; cool lighting; blue/gray tones; high detail; moderate contrast. Scene S08 from 'La Estación de Niebla'. From a large window, Mara observes the megastructure connected to the station, previously hidden behind the fog. Characters: Mara, ARCO. Visual goal: Close with a revelation and open the next phase. Location: Exterior observation deck. Time: After the lockdown. Shot: Extreme wide shot / backlighting. Keep consistency anchors: Mara: short black hair with a silver streak, dark gray technical uniform with cyan lines, left bracelet. ARCO: translucent blue hologram. No visible text. Keep composition clean. Aspect ratio 16:9.

### Ideogram — H2_S01 — Brillar más alto

Soft storybook illustration; warm palette; watercolor textures; clear expressions; clean composition. Scene S01 from 'La Luciérnaga y el Río'. Lumi intensifies her light in the middle of the night forest while the others watch her. Characters: Lumi. Visual goal: Introduce Lumi and her desire to stand out. Location: Forest clearing. Time: Night. Shot: Child-friendly wide shot / centered composition. Keep consistency anchors: Lumi: amber-gold firefly with a small leaf-green scarf, translucent wings, large eyes. Group: 2-3 warm-toned fireflies. River: wise non-literal reflection. No visible text. Keep composition clean. Aspect ratio 4:3.

### Ideogram — H2_S08 — El camino iluminado

Soft storybook illustration; warm palette; watercolor textures; clear expressions; clean composition. Scene S08 from 'La Luciérnaga y el Río'. Many small lights form a bright, harmonious path into the forest. Characters: Lumi. Visual goal: Close with a clear visual moral. Location: Main path. Time: Late night. Shot: Poetic extreme wide shot. Keep consistency anchors: Lumi: amber-gold firefly with a small leaf-green scarf, translucent wings, large eyes. Group: 2-3 warm-toned fireflies. River: wise non-literal reflection. No visible text. Keep composition clean. Aspect ratio 4:3.

### Ideogram — H3_S01 — El mapa despierta

Colorful semi-realistic adventure; sunset light; dynamic compositions; a sense of wind and movement. Scene S01 from 'El Mapa del Viento'. A gust opens the map in the town square and reveals a shifting route. Characters: Nico, Sara. Visual goal: Present the artifact and the inciting event of the adventure. Location: Town square. Time: Afternoon. Shot: Wide shot with central action. Keep consistency anchors: Nico: light brown jacket, green backpack, compass. Sara: dark teal scarf, cream notebook. Map: ancient parchment with blue-green lines activated by the wind. No visible text. Keep composition clean. Aspect ratio 16:9.

### Ideogram — H3_S07 — La biblioteca perdida

Colorful semi-realistic adventure; sunset light; dynamic compositions; a sense of wind and movement. Scene S07 from 'El Mapa del Viento'. Inside, the books and golden dust create a silent yet living atmosphere. Characters: Nico, Sara. Visual goal: Reveal the treasure and slow the pace with wonder. Location: Inside the library. Time: Timeless interior. Shot: Wide shot with depth. Keep consistency anchors: Nico: light brown jacket, green backpack, compass. Sara: dark teal scarf, cream notebook. Map: ancient parchment with blue-green lines activated by the wind. No visible text. Keep composition clean. Aspect ratio 16:9.

## 4) Midjourney (opcional si pagas)
Usa el prompt en inglés y añade al final los parámetros:
- H1: `--ar 16:9 --seed 1101`
- H2: `--ar 4:3 --seed 2202`
- H3: `--ar 16:9 --seed 3303`

Si quieres usar Midjourney, te conviene probar solo las mismas 6 escenas para no romper comparabilidad.