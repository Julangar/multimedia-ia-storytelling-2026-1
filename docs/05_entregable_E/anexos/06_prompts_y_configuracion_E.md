# Prompts y configuración usados - Entregable E

## Escenas evaluadas
- H3_S01: El mapa despierta
- H3_S04: Tormenta en el campo
- H3_S07: La biblioteca perdida

## ChatGPT baseline
Se usaron las imágenes ya generadas previamente para H3. La estrategia consistió en:
- pasar anclajes fijos junto al prompt completo de S01;
- en S02-S08 pasar prompt completo por escena;
- editar S06 varias veces para corregir mano/libro.

## Leonardo Phoenix 1.0 - Prompt Enhance Off
Configuración:
- Model: Phoenix 1.0
- Prompt Enhance: Off
- Contrast: Medium
- Generation Mode: Fast
- Style: Illustration
- Ratio: 16:9
- Number of images: 4
- Negative prompt: On
- Fixed Seed: 3303

Incidencia:
- La plataforma mostró el mensaje: `We are aware of issues impacting Phoenix generations and are investigating.`
- En S07, 2 de 4 outputs no fueron entregados por moderación; se acreditaron 8 tokens.

## Leonardo Phoenix 1.0 - Prompt Enhance On
Configuración igual a la anterior, pero con:
- Prompt Enhance: On

Resultado:
- El prompt enriquecido no mejoró de forma relevante la legibilidad ni claridad de las escenas.

## Ideogram con referencia
Se usó una imagen de referencia generada con ChatGPT para sostener personajes y estilo.

Configuración registrada:
- Prompt y negative prompt en una misma petición.
- Imagen de referencia de ChatGPT.
- Type: Generation.
- Model: Nano Banana / Auto 3.0 según metadatos visibles.
- Aspect ratio: 16:9.
- Resolución: 1376 x 768.
- 4 imágenes por escena.
- Se usaron dos cuentas por límite de créditos.
