# Cálculo de Áreas Deforestadas mediante Segmentación de Imágenes Satelitales

Este proyecto implementa un sistema para detectar áreas deforestadas en imágenes satelitales mediante técnicas de procesamiento de imágenes y segmentación. El objetivo principal es automatizar el análisis de imágenes para calcular la cantidad de área afectada por la deforestación.

## Beneficios del Proyecto

1. **Monitoreo Automático**: Automatiza el proceso de detección de áreas deforestadas en grandes conjuntos de datos de imágenes satelitales.
2. **Análisis Eficiente**: Permite un análisis eficiente de regiones afectadas, ahorrando tiempo en comparación con métodos manuales.
3. **Visualización Informativa**: Ofrece visualizaciones claras y detalladas de las áreas deforestadas, facilitando el estudio y la toma de decisiones en proyectos de conservación y manejo de recursos naturales.
4. **Aplicación Práctica**: Útil para organizaciones medioambientales, gobiernos y proyectos de investigación que necesiten monitorear el impacto de la deforestación a lo largo del tiempo.

## Requisitos

- Python 3.x
- OpenCV
- NumPy
- Matplotlib
- SciPy

## Explicación del Proyecto
Este proyecto está basado en el uso de técnicas avanzadas de segmentación de imágenes, específicamente diseñadas para detectar y medir áreas deforestadas. A partir de imágenes satelitales, el sistema identifica las áreas que han sufrido deforestación, calculando el área afectada en kilómetros cuadrados. Los pasos principales incluyen:

- Preprocesamiento de Imágenes: Las imágenes satelitales se ajustan y normalizan para optimizar la precisión del modelo de segmentación.
- Segmentación: Utilizando un enfoque de segmentación basado en técnicas de procesamiento de imágenes, se identifican las áreas de deforestación dentro de la imagen satelital.
- Cálculo de Áreas: Una vez segmentadas las áreas afectadas, se calcula el área total utilizando métodos basados en la escala de la imagen satelital.
- El sistema es capaz de procesar múltiples imágenes de forma automatizada, lo que permite el monitoreo constante de grandes áreas forestales y su cambio a lo largo del tiempo.

## Resultados
El sistema genera los siguientes resultados:

- Imágenes Procesadas: Imágenes satelitales con las áreas deforestadas resaltadas visualmente para facilitar la interpretación.
- Cálculo del Área Afectada: Proporciona el cálculo preciso del área total deforestada en kilómetros cuadrados, que es crucial para estudios medioambientales y la implementación de políticas.
