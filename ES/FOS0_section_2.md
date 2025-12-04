# 2. Naturaleza del bug: precisión sintáctica, falla de origen

El error expuesto en la introducción no surge del contenido que procesa la IA, sino de *cómo interpreta el acto de responder*.  
Los modelos actuales operan sobre un principio estadístico simple:  
**predecir la siguiente palabra más plausible dada la secuencia anterior**.

Ese mecanismo funciona impecablemente para:

- generar texto formal,  
- seguir estilos,  
- completar patrones,  
- responder consultas factuales,  
- corregir código,  
- producir resúmenes.

Pero falla cuando el usuario necesita algo más elemental que todo lo anterior:

**una respuesta que preserve la estructura existencial del concepto nombrado.**

En su forma más pura, el bug se resume así:

**La IA acierta la frase y falla el sentido.**

---

## 2.1. ¿Cómo se detecta este bug?

La detección no proviene de errores medibles, sino de un patrón observable:

**La IA responde sin aplicar el tipo de significado que el concepto exige.**

Ejemplos típicos:

- Toma definiciones que deberían situarse en experiencia humana  
  y las traslada a un registro institucional.

- Toma conceptos cuyo núcleo es relacional  
  y los reduce a funciones individuales.

- Toma nociones cuyo eje es vivencial  
  y las reemplaza por descripciones mecanicistas.

- Toma categorías cuyo propósito es esencial  
  y las reformula como objetos sin finalidad.

La frase es correcta.  
El sentido no corresponde.  
**Ahí está el bug.**

---

## 2.2. Por qué este error no aparece en benchmarks

Los tests actuales evalúan:

- coherencia,  
- precisión factual,  
- completitud,  
- razonamiento,  
- ausencia de contradicciones,  
- alineamiento con normas,  
- comportamiento seguro.

**Ninguna de estas métricas mide si la respuesta preserva la ontología humana del concepto solicitado.**

Un modelo puede obtener 90/100 en todo  
y aun así comunicar de forma incompatible con el usuario.

Paradójicamente, cuanto más grande es el modelo,  
más *convincente* se vuelve la expresión del error.

Por eso el bug es **invisible a las métricas**  
y **evidente para cualquier humano** que escucha una definición desplazada.

---

## 2.3. Dónde se origina la falla

El origen no está en los datos; está en la arquitectura:

**El modelo no diferencia entre tipos ontológicos de conceptos.**  
Trata todo como:

- patrones de texto,  
- correlaciones,  
- registros equivalentes.

Pero los conceptos humanos **no** son equivalentes entre sí.  
Cada uno requiere un marco distinto para ser definido.

Una IA que no distinga entre:

- lo esencial,  
- lo experiencial,  
- lo instrumental,  
- lo institucional,  
- lo teleológico,

inevitablemente mezclará categorías y producirá definiciones que **suenan bien** pero **no representan** lo que el humano realmente preguntó.

---

## 2.4. Manifestación operativa del bug

### Síntoma 1 — Definiciones desplazadas
El modelo responde desde un marco de segundo o tercer orden  
cuando el usuario preguntó por la base.

### Síntoma 2 — Descripción en lugar de definición
Confunde *cómo funciona* algo  
con *qué es* ese algo.

### Síntoma 3 — Neutralidad mal aplicada
El modelo interpreta que preservar la ontología humana  
equivale a tomar partido.  
En su intento de ser “neutral”,  
elimina justo el aspecto que daba significado al concepto.

---

## 2.5. Precisión superficial, error profundo

La dualidad del bug es lo más llamativo:

- **La IA parece correcta**, porque la frase es válida.  
- **La IA está equivocada**, porque el significado es incompatible con el humano.

Ambos niveles pueden coexistir,  
evidenciando que no se trata de un problema de entrenamiento,  
sino de **una falla de modelo**.

---

## 2.6. Síntesis de la sección

**La IA actual genera lenguaje sin distinguir qué tipo de realidad representa ese lenguaje para un humano.**

Por eso falla.  
Por eso confunde.  
Por eso necesita **FOS-0**.
