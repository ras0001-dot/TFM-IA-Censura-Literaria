# TFM-IA-Censura-Literaria
Pipeline de OCR, PLN y análisis de grafos aplicado al estudio de la censura literaria.

Aquí se presenta el repositorio asociado al Trabajo Fin de Máster dedicado al análisis computacional de la censura literaria mediante técnicas de OCR, procesamiento del lenguaje natural y análisis de grafos.

## Objetivo

Crear un repositorio para reunir aquellos materiales metodológicos que sean elaborado durante el Trabajo Fin de Máster. La finalidad para la que se crea este repositorio es la de facilitar la comprensión y reproducibilidad del pipeline que ha seguido la investigación que se propone en el TFM.

## Pipeline metodológico

El flujo de trabajo o pipeline que se ha seguido en este proyecto se puede resumir en las siguientes fases:

1. Digitalización de las obras mediante OCR.
2. Evaluación y postprocesamiento del OCR.
3. Normalización y preprocesamiento textual.
4. Segmentación de las obras en unidades comparables.
5. Generación de archivos de aristas para Gephi.
6. Construcción y análisis de grafos léxicos.
7. Comparación estructural entre versiones.

## Contenido

- notebooks/: cuadernos de Google Colab.
- gephi/: grafos y resultados exportados.
- docs/: documentación complementaria.
- data_examples/: ejemplos de archivos de entrada y salida.

## Herramientas utilizadas

- **ABBYY FineReader**: digitalización y reconocimiento óptico de caracteres (OCR).
- **Python**: desarrollo del pipeline de procesamiento.
- **Google Colab**: ejecución y desarrollo de los cuadernos de trabajo.
- **pandas**: manipulación y transformación de datos.
- **Gephi**: construcción y análisis de grafos.

## Reproducibilidad

Por motivos de propiedad intelectual, el corpus completo de las obras analizadas no se distribuye públicamente. El repositorio incluye código, ejemplos de datos y materiales suficientes para comprender el flujo de trabajo y reproducir el pipeline sobre un corpus equivalente.

