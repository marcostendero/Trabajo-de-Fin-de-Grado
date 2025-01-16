# Proyecto de Fin de Grado: Supervisión del Rendimiento y la Recuperación de Deportistas con Dispositivos Wearables

Este proyecto tuvo como objetivo desarrollar un sistema de supervisión del rendimiento y la recuperación de deportistas de contacto utilizando dispositivos wearables. El desarrollo constó de tres fases: configuración de una red personal de dispositivos, implementación de un sistema de monitoreo para capturar datos, y un sistema de análisis para evaluar el rendimiento y la recuperación, en el que se desarrolló un algoritmo de calificación de ambos parámetros según la literatura de las ciencias del deporte y la salud.

Para la fase de análisis de datos, se usó *Pandas* como librería principal de Python.

## Estructura del Proyecto

El repositorio contiene los siguientes archivos principales:

- `TFG_MarcosTenderoCarmona.pdf`: Memoria del proyecto, que contiene todo el fudamento teórico y los resultados y conclusiones.
- `Depurado.ipynb`: Jupyter notebook para el depurado y transformación de los datos antes de su análisis, asegurando la calidad de los datos capturados. En este proceso se eliminan duplicados, se rellenan datos faltantes y se descartan outliers.
- `TFG.ipynb`: Jupyter notebook con el código de análisis de los datos capturados, utilizando técnicas de procesamiento y visualización. Este cuaderno contiene funciones de procesado segmentado de cada parámetro, funciones de evaluación con variables categóricas a partir de la literatura revisada y funciones de evaluación de rendimiento y recuperación según el algoritmo planteado.


## Tecnologías Utilizadas

- **Hardware**:
  - Garmin Venu 2 (Smartwatch)
  - Garmin HRM-Pro Plus (Sensor de frecuencia cardíaca)
- **Software**:
  - Python (Jupyter, Pandas, Matplotlib, etc.) en Anaconda Navigator
  - Garmin Connect y Garmin Express
  

## Objetivos del Proyecto

El objetivo principal del proyecto se centra en la monitorización del rendimiento deportivo y la recuperación de un usuario en deportes de contacto mediante el despliegue de una red personal de dispositivos wearables y explotación de los datos capturados mediante la realización de un análisis de dichos datos.
Este objetivo principal se desglosó en 8 objetivos específico, que englobamos de la siguiente manera:
1. **Búsqueda y Despliegue Red Personal de Dispositivos Wearables**: Configuración de una red de dispositivos wearables para monitorizar parámetros fisiológicos relevantes durante los entrenamientos, trras un análisis de mercado. 
2. **Monitoreo de Datos**: Determinación de métricas valiosas tras la parametrización del deporte estudiado. Desarrollo de un sistema para capturar datos en tiempo real durante las sesiones deportivas.
3. **Análisis de Datos**: Implementación de un algoritmo para analizar la recuperación y el rendimiento de los deportistas con base en los datos recogidos.

## Resultados Obtenidos
Se pueden comprobar los resultados obtenidos en el capítulo 5 de la memoria. 

En general, se obtuvieron resultados muy positivos, demostrando que la interpretación de la literatura fue correcta. 

## Calificación Obtenida con el Proyecto
Con este proyecto obtuve ua calificación de **10 - Matrícula de Honor** en el Grado en Ingeniería de Telecomunicaciones por la Universidad de Granada.


## Contribuciones
Si deseas colaborar en el proyecto, siéntete libre de hacer un fork, realizar cambios y enviar un pull request. Asegúrate de seguir las buenas prácticas de desarrollo y documentar bien el código.

## Autor
Marcos Tendero Carmona
Grado en Ingeniería de Tecnologías de Telecomunicación - Universidad de Granada
Tutor: Juan Antonio Holgado Terriza
