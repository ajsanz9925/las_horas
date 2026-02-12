Flujo de trabajo operativo — Novelas
Principio rector

GitHub es el único archivo canónico.
Nada existe si no está consolidado en el repositorio.

ChatGPT, Word, NotebookLM o cualquier otra herramienta son entornos de trabajo auxiliares. No sustituyen el archivo oficial.

1. Flujo diario de escritura (bloque a bloque)
1.1 Extracción del bloque

Abrir 01_manuscrito/cap_X.md.

Copiar el bloque completo que se va a trabajar.

Trabajar siempre desde la versión existente en el repositorio.

Nunca trabajar desde memoria o versión paralela.

1.2 Trabajo literario

Pegar el bloque en ChatGPT.

Realizar ajustes de:

ritmo

transición

poda

precisión léxica

Obtener versión final del bloque.

ChatGPT funciona como taller, no como archivo.

1.3 Conteo de palabras

Copiar el bloque final.

Pegar en Word.

Revisar → Contar palabras.

Anotar el número real.

El conteo siempre se realiza por bloque, no por capítulo completo.

1.4 Consolidación en el repositorio

Sustituir el bloque en cap_X.md por la versión final.

Actualizar 02_ledger/LEDGER.md:

Formato obligatorio:

Capítulo X
- Bloque X.1 → XXXX palabras → Estado
- Bloque X.2 → XXXX palabras → Estado

Total capítulo: XXXX palabras
Estado: En desarrollo / Validado


Realizar commit con formato:

[Capítulo X] Acción breve


Ejemplos:

[Capítulo 3] Ajuste transición bloque 3.2

[Capítulo 1] Actualización conteo y estado

[General] Actualización ledger

Si no hay commit, la sesión no se considera cerrada.

2. Uso de NotebookLM (lectura estructural)

NotebookLM se utiliza únicamente con versiones estables.

2.1 Preparación

En 06_export/ colocar:

manuscrito parcial o completo (.md o .docx)

ledger

fichas de personajes (si procede)

cronología (si procede)

2.2 Función

NotebookLM se utiliza para:

detectar contradicciones

localizar apariciones

analizar coherencia

identificar objetos o motivos recurrentes

verificar cronología

NotebookLM no edita el texto. Informa.

3. Uso opcional de Gemini

Gemini puede utilizarse para:

esquemas panorámicos

mapas estructurales

síntesis de capítulos

detección de patrones repetitivos

Las sugerencias nunca sustituyen el archivo del repositorio.

4. Uso opcional de Perplexity

Perplexity se utiliza únicamente para documentación externa:

datos históricos

normativa

geografía verificable

contexto factual

Procedimiento:

Localizar fuentes.

Guardarlas en el repositorio si son relevantes.

Usarlas como base documental.

Nunca introducir información sin respaldo.

5. Reglas de disciplina

Una novela = un repositorio.

Un hilo activo por novela.

No trabajar versiones paralelas.

No modificar bloques sin actualizar ledger.

No cerrar sesión sin commit.

6. Señal de estabilidad

El sistema funciona correctamente cuando:

Cada bloque tiene conteo registrado.

Cada capítulo tiene estado definido.

No existen textos fuera del repositorio.

El historial de commits es legible.

Este documento fija el flujo de trabajo hasta nueva revisión explícita.
