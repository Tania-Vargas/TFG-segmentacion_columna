# Aplicación de Inteligencia Artificial para la segmentación de imágenes médicas de la columna vertebral  
*Artificial Intelligence Application for medical image segmentation of the spine*
## Descripción
Este repositorio contiene el código desarrollado para el Trabajo de Fin de Grado en Ingeniería Informática, centrado en el diseño e implementación de un sistema de segmentación automática de imágenes médicas de la columna vertebral, con especial atención a radiografías laterales.

El sistema se apoya en modelos de segmentación basados en U-Net con encoder ResNet34, e incluye una fase de posprocesado para limpiar las segmentaciones y una fase final donde se calculan métricas clínicas (angulares y traslacionales) de interés para el diagnóstico médico.

## Autor
**Tania Évora Vargas Martínez**  
Universidad de La Laguna – Escuela Superior de Ingeniería y Tecnología  
Grado en Ingeniería Informática  
La Laguna, 2025

## Tutor
**Rafael Arnay del Arco**  
Profesor Titular de Universidad  
Departamento de Ingeniería Informática y Sistemas  
Universidad de La Laguna

## Estructura del repositorio
- `1_preprocesar.ipynb`: Conversión y normalización de imágenes (formato PNG).
- `2_entrenar_modelos.ipynb`: Entrenamiento de modelos de segmentación.
- `3_postprocesado.ipynb`: Limpieza, separación y validación de vértebras segmentadas.
- `4_metricas_clinicas.ipynb`: Cálculo de métricas clínicas a partir de máscaras limpias.
- `README.md`: Este archivo.

## Nota importante
Las salidas de las celdas han sido **eliminadas** en todos los notebooks para reducir el tamaño de los archivos y permitir su subida a GitHub (límite de 25 MB por archivo).  

Los resultados obtenidos durante la ejecución del sistema, incluyendo gráficas, segmentaciones visuales y métricas, están **recogidos en la memoria del TFG** y se explicarán durante la **defensa del trabajo**.

Este repositorio se proporciona únicamente como **referencia técnica** para el tribunal o cualquier persona interesada en el código fuente.
