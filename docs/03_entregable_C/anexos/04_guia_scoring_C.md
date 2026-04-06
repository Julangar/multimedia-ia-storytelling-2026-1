# Guia de scoring — Entregable C

Usa la escala 0–5 en cada criterio. La idea es puntuar rapido, de manera consistente y sin sobredimensionar diferencias menores.

## Regla general
- **0–1**: no cumple o falla severamente
- **2**: cumple poco / resultado debil
- **3**: cumple de forma aceptable
- **4**: cumple bien
- **5**: cumple muy bien / candidato fuerte

## Criterios

### 1. score_alineacion
Mide si la imagen representa lo pedido por la escena.
- 0–1: faltan elementos clave o la accion no corresponde
- 2: representa algo relacionado pero incompleto
- 3: cumple lo esencial
- 4: representa bien casi todos los elementos
- 5: representa claramente la escena y sus detalles clave

### 2. score_personaje
Mide si los personajes se ven correctos y consistentes con su descripcion.
- 0–1: personaje ausente o deformado
- 2: personaje aparece, pero muy inconsistente
- 3: personaje reconocible con fallos visibles
- 4: personaje consistente y bien representado
- 5: personaje muy consistente y util para continuidad posterior

### 3. score_estilo
Mide si la estetica coincide con la direccion de arte definida.
- 0–1: estilo equivocado
- 2: estilo parcialmente adecuado
- 3: estilo aceptable
- 4: estilo bien alineado
- 5: estilo muy bien logrado y reusable

### 4. score_calidad
Mide artefactos, nitidez, composicion y limpieza visual.
- 0–1: errores graves
- 2: errores visibles que afectan lectura
- 3: calidad usable
- 4: calidad buena
- 5: calidad muy alta

### 5. score_storyboard
Mide si la imagen sirve para contar esa escena dentro de una secuencia.
- 0–1: no se entiende la accion
- 2: comunica algo, pero ambiguo
- 3: funciona de forma aceptable
- 4: comunica claramente la accion o estado
- 5: funciona muy bien como frame de storyboard

### 6. score_control
Mide el grado de control practico de la herramienta para repetir o ajustar resultados.
- 0–1: casi sin control
- 2: control muy limitado
- 3: control aceptable
- 4: control bueno
- 5: control alto (seed, negative, parametros o comportamiento repetible)

## Metodo rapido para llenar
1. Mira primero la escena sin comparar.
2. Pon puntaje a alineacion y storyboard.
3. Luego revisa personaje, estilo y calidad.
4. Finalmente asigna control segun la herramienta y la experiencia de uso.
5. Usa el campo `notas` solo cuando haya un fallo o hallazgo que realmente deba quedar documentado.
