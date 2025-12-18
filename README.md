# Offly – Fast Prompting POC

## Introducción
Este proyecto presenta una prueba de concepto (POC) que aplica técnicas de Fast Prompting
para la generación de mensajes breves y empáticos en la aplicación Offly, orientada a ayudar
a jóvenes a mejorar su concentración.

## Problemática
Muchos jóvenes experimentan dificultades para mantener la concentración debido a
distracciones digitales constantes. Las intervenciones genéricas suelen ser poco efectivas
y no consideran el contexto emocional del usuario.

## Propuesta de solución
La solución consiste en el uso de un prompt único, parametrizado y reutilizable, que permite
generar mensajes personalizados según el nivel de distracción, estado emocional y momento
del día del usuario.

## Metodología
Se diseñó un prompt optimizado siguiendo principios de Fast Prompting, evitando consultas
innecesarias a modelos de IA y mejorando la eficiencia del sistema.

## Herramientas y tecnologías
- Python
- Jupyter Notebook
- Técnicas de Fast Prompting
- VS Code

## Implementación
La implementación se encuentra desarrollada en un Jupyter Notebook, donde se genera el
prompt dinámicamente a partir de variables contextuales del usuario.

## Análisis de costos
El enfoque propuesto permite realizar una única consulta a la API por mensaje generado,
reduciendo significativamente los costos y mejorando la escalabilidad del sistema.
