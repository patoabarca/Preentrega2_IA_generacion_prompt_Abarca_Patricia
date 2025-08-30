# Asistente IA de Afiliaciones

## Introducción

Proyecto desarrollado en el marco del curso _Inteligencia Artificial – Generación de Prompts_. El objetivo es crear un asistente interno para el área de **Afiliaciones\*, que agilice la resolución de consultas frecuentes sobre **altas, bajas y modificaciones de afiliados\*\* (obligatorios, voluntarios y colectivos) y sus grupos familiares.

## Problema

Los agentes reciben gran volumen de consultas repetitivas, con normativa dispersa y respuestas poco uniformes. Esto genera demoras, dependencia de referentes y riesgo de inconsistencias.

## Propuesta de solución

Implementar un sistema de **prompts optimizados** que, a partir de una **base de conocimiento en CSV con FAQs validadas**, devuelva respuestas claras, trazables y estandarizadas en formato JSON o visualizaciones simples.

## Viabilidad

- **Técnica:** factible con herramientas gratuitas/educativas (ChatGPT, CSV, Colab, diagrams.net).
- **Económica:** costo muy bajo (≈ USD 0.0002 por consulta; con 400–480 consultas al mes, ≈ USD 0.08–0.10).
- **Tiempo:** MVP en 4 semanas (curado de FAQs, diseño de prompts, pruebas, medición).

## Objetivos

- Reducir tiempos de respuesta en un 30–50%.
- Asegurar ≥ 90% de concordancia normativa.
- Uniformar criterios de respuesta y trazabilidad.
- Liberar tiempo operativo de los agentes.

## Metodología

- Construcción de base de conocimiento en **CSV**.
- Diseño iterativo de prompts y pruebas en **notebook**.
- Medición de impacto (línea de base y post-MVP).
- Ajustes y escalado a otros temas internos.

## Herramientas y tecnologías

- **Prompts estructurados en JSON** (checklist, términos clave, buenas prácticas, cierre).
- **Python + OpenAI API** para implementación en notebook.
- **CSV** como fuente de FAQs validadas.
- **GitHub** para control de versiones.
- **Diagrams.net / Excalidraw** para visualizaciones.

## Implementación

- Prompt principal implementado en Python.
- Notebook de pruebas incluye ejecución, respuestas de ejemplo y cálculo de costos.

---

## 📂 Estructura del repositorio

PREENTREGA2_IA_GENERACION_PROMPTS/
│

├── data/
│ └── base_conocimiento_afiliaciones_clean.csv # Base de conocimiento (FAQs validadas)

│
├── docs/
│ └── Preentrega2_Abarca_Patricia.pdf # Documento con desarrollo del proyecto

│
├── notebooks/
│ └── 01_fast_prompting_texto_texto.ipynb # Notebook con implementación y pruebas
│ └── 02_fast_prompting_texto_imagen.ipynb # Notebook con implementación y pruebas

│
└── README.md # Resumen del proyecto
