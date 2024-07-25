# Análisis de Datos para la toma de decisiones en los deportes: LDD Futbol Analytics

## Descripción del proyecto
En este trabajo práctico creamos nuestra empresa LDD Futbol Analytics.
Trabajamos con el dataset `FBRef2020-21.csv` que contiene datos sobre los principales torneos de clubes y selecciones de fútbol del mundo.

## Estructura del proyecto
El proyecto esta dividido en las siguientes secciones:
1. **Preprocesamiento**
2. **Clustering**
3. **Clasificación**
4. **Recomendaciones de jugadores**

## Preprocesamiento
Cargamos, limpiamos los datos y reseteamos los índices. Además, elegimos las columnas que utilizaremos para la parte de *clustering*.

## Clustering
Agrupamos jugadores con características similares utilizando *k-medias* y *DBSCAN*.

## Clasificación
Predecimos la posición en la que juega cada jugador según sus datos estadísticos utilizando *KNN* para el dataset inicial y también para el dataset de jugadoras de la liga inglesa femenina `superleague2023.csv`

## Recomendaciones de jugadores
Utilizando el dataset `transfermarkt_fbref_201920.csv` que incluye la valuación de los jugadores, buscamos obtener recomendaciones de jugadores a comprar utilizando redes neuronales.

## Disclaimer
Este proyecto fue realizado para la materia Laboratorio de Datos de la carrera de Ciencia de Datos en la Universidad de Buenos Aires.
