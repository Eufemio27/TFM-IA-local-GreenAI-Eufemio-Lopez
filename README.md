# Material complementario del TFM

Repositorio complementario del Trabajo Final de Máster:

**Evaluación comparativa de modelos locales de inteligencia artificial en español académico: calidad de respuesta, tiempo de ejecución e impacto ambiental estimado**

Autor: Eufemio López Rodríguez  
Universidad Internacional de Valencia  
Máster Permanente en Inteligencia Artificial Generativa  
Curso académico: 2025-2026  
Directora: Profesora Diana Damas Diego

## Descripción

Este repositorio contiene los materiales complementarios utilizados en el TFM. Su finalidad es facilitar la trazabilidad, revisión y replicabilidad del estudio.

El trabajo compara tres modelos locales de inteligencia artificial aplicados a tareas académicas en español:

- `google/flan-t5-small`
- `google/flan-t5-base`
- `Qwen/Qwen2.5-0.5B-Instruct`

Las variables principales analizadas fueron:

- calidad de respuesta;
- tiempo de ejecución;
- CO₂e estimado durante la inferencia.

## Estructura del repositorio

El repositorio se organiza en las siguientes carpetas:

- `01_csv/`: archivos CSV generados durante el experimento, resultados evaluados y tablas resumen.
- `02_notebooks_colab/`: notebooks utilizados para ejecutar los modelos en Google Colab.
- `03_rmarkdown/`: archivo R Markdown utilizado para documentar el análisis.
- `04_pdf_analisis/`: PDF generado a partir del análisis reproducible.
- `05_graficos/`: gráficos generados durante el análisis.
- `06_capturas/`: capturas de pantalla del proceso experimental.

## Herramientas utilizadas

- Google Colab
- Python
- Transformers
- PyTorch
- CodeCarbon
- R Programming
- R Markdown

## Nota metodológica

Los valores de CO₂e deben interpretarse como estimaciones comparativas dentro del entorno experimental utilizado. No representan una medición absoluta del impacto ambiental total de cada modelo.

La memoria principal del TFM se entrega por la plataforma oficial de la universidad. Este repositorio funciona únicamente como material complementario para facilitar la revisión de datos, código, gráficos y resultados.
