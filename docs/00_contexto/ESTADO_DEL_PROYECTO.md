# ESTADO_DEL_PROYECTO — GI-II 2026-1 (Multimedia Interactiva)
**Proyecto:** Storytelling y Storyboarding asistidos con IA (GI-II 2026-1)  
**Autor:** Julian Andres Garcia Guerrero — **Código:** 20171020011  
**Programa:** Ingeniería de Sistemas — Facultad de Ingeniería — Universidad Distrital Francisco José de Caldas  
**Grupo:** Multimedia Interactiva y Animación Digital  
**Director / Monitor:** Paulo Alonso Gaona-García, PhD / Juan David Martínez Monroy  
**Repositorio (público):** https://github.com/Julangar/multimedia-ia-storytelling-2026-1  
**Última actualización:** 2026-03-03 16:14 (UTC-5)

---

## 1) Resumen ejecutivo
El proyecto implementa una **investigación aplicada** para **comparar herramientas** de narrativa asistida por IA y **generación de imágenes**, y su integración hacia un **storyboard coherente** (mini historia de **6–10 imágenes**), con evaluación comparativa y repositorio de experimentos.

**Entregable actual:** **Entregable A (Fase 1)** — Inventario de herramientas + matriz comparativa + rúbrica + set de 3 historias de prueba.

**Estrategia clave:** pruebas controladas (mismos prompts base por historia/escena), bitácora de parámetros y evaluación humana guiada (rúbrica 0–5 + gating).

---

## 2) Alcance y preguntas guía (marco de investigación)
**Preguntas guía (operacionales para el semestre):**
1. ¿Qué herramientas soportan mejor el proceso **guion → escenas → prompts → imágenes → storyboard** bajo restricciones de reproducibilidad?
2. ¿Qué tan consistente es cada herramienta al mantener **personaje** y **estilo** a través de 6–10 escenas?
3. ¿Cuál es el **costo/tiempo** por iteración y la facilidad para producir variaciones coherentes?
4. ¿Qué prácticas de **prompting/bitácora** maximizan la calidad y reducen retrabajo?

---

## 3) Metodología y bitácora (cómo se va a trabajar)
### 3.1 Diseño experimental (mínimo viable pero defendible)
- **Banco controlado:** 3 historias (géneros distintos) para pruebas comparables.
- **Unidad de análisis:** escena individual y secuencia completa (6–10 imágenes).
- **Normalización:** mismo texto base / misma escena / mismo # de variaciones por herramienta (cuando aplique).
- **Evidencia:** prompts, parámetros, outputs y score de rúbrica por escena.

### 3.2 Instrumentos
- **Rúbrica:** gating (sí/no) + puntajes 0–5 (alineación, consistencia personaje, consistencia estilo, calidad visual, utilidad storyboard, control/reproducibilidad).
- **Bitácora (CSV):** registro obligatorio por cada corrida (prompt completo, parámetros, modelo/versión, tiempo, costo, output, scores).
- **Repositorio/anexos:** tablas editables (CSV/MD), PDFs por entregable, outputs organizados.

### 3.3 Normas de presentación
Los entregables siguen formato académico en **APA 7**, usando la plantilla del proyecto.

---

## 4) Cronograma y reuniones (quincenal)
> Nota: el calendario puede ajustarse según recomendaciones del director/monitor. Mantener siempre “entregable el lunes previo”.

**Reuniones (martes, 15 min, Teams):**
- 2026-03-03 (kickoff) — *reunión programada hoy (Teams) a las 6:00 p. m.*
- 2026-03-17
- 2026-03-31
- 2026-04-14
- 2026-04-28
- 2026-05-12
- 2026-05-26 (cierre)

**Entregables (enviar el lunes previo a cada reunión, antes de 9:00 p. m.):**

| Fecha (lunes) | Entregable | Objetivo / evidencia mínima |
|---|---|---|
| 2026-03-02 | A | Inventario + matriz + rúbrica + 3 historias de prueba |
| 2026-03-16 | B | Paquetes narrativos (H1–H3) + Prompt Cards v1 |
| 2026-03-30 | C | Pruebas T2I iniciales (1–2 escenas por herramienta) + bitácora |
| 2026-04-13 | D | Mini historia completa (6–10 imágenes) + storyboard PDF |
| 2026-04-27 | E | “Mismo prompt” multi-plataforma + análisis comparativo |
| 2026-05-11 | F | Informe comparativo + catálogo prompts + manuales + repo |
| 2026-05-25 | Final | PDF final + anexos + repo listo para validación |

---

## 5) Entregables y artefactos (estado)
### 5.1 Entregables realizados
- ✅ Entregable A (Fase 1) — entregado (PDF/DOCX) y publicado en repo.
- ✅ Plantilla APA 7 v2 — publicada (PDF/DOCX) para mantener consistencia.

### 5.2 Estructura mínima del repositorio (fuente de verdad)
- `/docs`: entregables (PDF) y anexos (CSV/MD)
- `/prompts`: Prompt Cards por historia/escena
- `/logbook`: bitácora (CSV)
- `/outputs`: imágenes y storyboards exportados (por herramienta/historia/escena)

---

## 6) Decisiones tomadas (Decision log)
1. Repo público en GitHub como “fuente de verdad” (documentos + anexos + bitácora + outputs).
2. Evaluación basada en rúbrica (gating + 0–5), priorizando coherencia narrativa y consistencia visual.
3. Banco controlado de 3 historias para comparación (géneros distintos).
4. Ritmo quincenal: entregable el lunes previo + reunión corta de control.

---

## 7) Próximos pasos (inmediatos)
### Para el Entregable B (2026-03-16)
- Definir para cada historia: logline, sinopsis, escaleta, fichas de personajes, lista de escenas (6–10) y diálogos mínimos.
- Crear **Prompt Cards v1** por escena: (objetivo, personajes, entorno, cámara, estilo, restricciones, prompt + negativos + parámetros).
- Confirmar shortlist de herramientas para Fase 2 (mínimo 4–6 generadores) y criterios de selección.

---

## 8) Riesgos y mitigaciones
| Riesgo | Impacto | Mitigación |
|---|---|---|
| Variabilidad de outputs / cambios por versión de modelo | Sesgo en comparación | Registrar modelo/versión y parámetros; repetir corridas controladas; usar seed cuando sea posible |
| Transformación interna del prompt (según plataforma) | Comparabilidad reducida | Guardar prompt final y evidenciarlo en el informe; disclosure metodológico |
| Costos por uso / límites de plan | Menos cobertura experimental | Definir presupuesto y número de corridas; priorizar herramientas “core” |
| Políticas/PI | Restricciones en outputs | Documentar políticas; evitar prompts conflictivos; incluir consideraciones éticas |

---

## 9) Referencias base y documentos del proyecto
- Entregable A (Fase 1).
- Plantilla APA 7 (GI-II).
- Cronograma y metodología aplicada (documento interno del proyecto).
- Artículos/lecturas de referencia (PDFs compartidos en el proyecto).

---

## 10) Resumen de avance (para pegar al final en cada sesión)


## Resumen de avance — 2026-03-16
- **Qué se hizo:**
  - Se desarrolló el **Entregable B (Fase 1 completa)**.
  - Se consolidaron los **3 paquetes narrativos completos** (H1–H3).
  - Se definieron **24 escenas base** (8 por historia).
  - Se construyeron las **Prompt Cards v1** en formato CSV y Markdown.
  - Se preparó la **bitácora de experimentos** para iniciar la Fase 2.
  - Se organizó la estructura del repo para `docs/02_entregable_B/`, `prompts/` y `logbook/`.

- **Evidencia:**
  - Entregable formal: `docs/02_entregable_B/Entregable_B_GI-II_2026-1_Julian_Garcia.pdf`
  - Anexos: `docs/02_entregable_B/anexos/`
  - Prompts: `prompts/H1_estacion_de_niebla/`, `prompts/H2_luciernagas_y_el_rio/`, `prompts/H3_mapa_del_viento/`
  - Bitácora: `logbook/bitacora_experimentos_preparada_B.csv`

- **Decisiones:**
  - Se mantienen las 3 historias del banco controlado del proyecto.
  - Se trabaja con 8 escenas por historia en esta versión.
  - Se deja shortlist de herramientas para Fase 2 sin cerrar aún la selección final hasta la validación del profesor/monitor.
  - Se conserva la coherencia nominal del proyecto, aunque la carpeta de H2 en repo siga con la variante `luciernagas`.

- **Próximo paso:**
  - Validar con el profesor/monitor:
    - historias,
    - escenas,
    - Prompt Cards,
    - y shortlist de herramientas.
  - Luego iniciar el **Entregable C** con 1–2 escenas por herramienta y registro en bitácora.

- **Commit sugerido:**
  - `Add Entregable B, prompt cards v1, narrative packages, and phase-2 logbook prep`

## Resumen de avance — 2026-03-16
- **Qué se hizo:**
  - Se revisaron los archivos H1_prompt_cards_v1.md, H2_prompt_cards_v1.md y H3_prompt_cards_v1.md.
  - Se generaron las versiones v2, manteniendo el formato y la estructura original.
  - Se tradujo únicamente el contenido de las líneas Prompt (EN) para dejarlas completamente en inglés.

- **Evidencia (links):**
  - Archivo(s): H1_prompt_cards_v2.md, H2_prompt_cards_v2.md, H3_prompt_cards_v2.md

- **Decisiones:**
  - No se modificaron Prompt (ES), Negative prompt, Línea guía, ni la estructura de escenas.
  - Se conservó el nombre base de cada archivo y solo se cambió el sufijo de versión a v2.

- **Próximo paso:**
  - Validar las traducciones en el flujo de generación de imágenes y usar estas versiones como base para pruebas comparativas.

- **Commit sugerido:**
  - `docs(prompts): translate EN prompt cards for H1 H2 H3 and publish v2 files`

- **Archivos que cambian:**
  - H1_prompt_cards_v2.md
  - H2_prompt_cards_v2.md
  - H3_prompt_cards_v2.md
