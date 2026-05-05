# Conclusiones del Entregable E

## Resultado central
El piloto comparativo muestra que **Ideogram con imagen de referencia** fue la condición más fuerte para las tres escenas críticas de H3. El uso de la referencia generada con ChatGPT mejoró de manera visible la estabilidad de personajes, el encuadre y la coherencia de estilo.

## Comparación por condición
- **ChatGPT baseline:** buen desempeño general, continuidad macro sólida y capacidad de edición local; presenta inconsistencias finas en mapa/brújula y rasgos de personajes.
- **Leonardo Phoenix 1.0, Prompt Enhance Off:** desempeño bajo en esta ronda; las imágenes fueron poco claras, con baja legibilidad y problemas de composición. Además, se reportó advertencia de problemas activos con Phoenix.
- **Leonardo Phoenix 1.0, Prompt Enhance On:** el texto enriquecido no produjo una mejora suficiente. Los outputs siguieron siendo difíciles de interpretar.
- **Ideogram con referencia de ChatGPT:** mejora fuerte en estilo, calidad, encuadre y estabilidad visual de personajes; la limitación principal fue el costo/tiempo de espera por créditos en el plan gratuito.

## Hallazgo metodológico
La comparación sugiere que, para storyboarding asistido con IA, **las referencias visuales pueden aportar más que el incremento de detalle textual del prompt**. El prompt demasiado detallado no mejoró el desempeño de Leonardo en este caso; en cambio, la imagen de referencia sí fortaleció Ideogram.

## Implicación para el paper
Este resultado es valioso como caso de estudio porque permite formular una hipótesis defendible:
> In AI-assisted storyboarding, visual references may improve character and style consistency more effectively than text-only prompt refinement, especially under free/consumer-grade tool constraints.

## Limitaciones
- Evaluación piloto con 3 escenas y 3 herramientas/condiciones.
- Scores basados en revisión del investigador, no en panel de evaluadores externos.
- Leonardo presentó incidencias operativas reportadas por la plataforma durante la generación.
- Ideogram tuvo limitaciones por créditos y requirió dos cuentas para completar la prueba.
