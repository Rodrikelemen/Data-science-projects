# Proyectos Data Science

Realizado por [Rodrigo Kelemen](https://www.linkedin.com/in/rodrigo-kelemen-b3b5b513b/)

## Amazon reviews - The Multilingual Amazon Reviews Corpus
El objetivo de estre proyecto es armar un modelo que pueda predecir, a raiz de una review realizada por un usuario de amazon, cual es la calificacion asignada a dicha compra (del 1 al 5)
El proyecto esta conformado por los siguientes features:

#### Parte 1

+ Importacion y estado de salud del dataset

+ Analisis exploratorio de datos

      a.Analisis general
      b.Peliculas mal puntuadas
      c.Peliculas bien puntuadas

+ Preparacion de datos
 
      a-Stemming
      b.Vectorizer

+ Modelos de clasificacion

      a.GaussianNB - Modelo benchmark
      b.Arbol de decision
      c.Random forest

5- Probando con otra transformacion de datos

      a.Lemmantization
      b.Implementacion del mejor modelo (Punto 4)

#### Parte 2: ¿Se pueden mejorar los resultados con deep learning?

+ Modelos de deep learning con la misma cantidad de datos

       a.Stemming
       b.Lemmantization

+ Modelos de deep learning con mas cantidad de datos

       a.Stemming
       b.Lemmantization 


## Sistemas de recomendación - Steam reviews
En este proyecto se implemento un sistema de recomendación basado en la tecnica de filtro colaborativo. Donde el output de este proyecto es devolver las 5 mejores recomendaciones tanto para un id de usuario como para un id de un juego determinado.
El proyecto esta conformado por los siguientes features:
+ Importacion y estado de salud del dataset

+ EDA & Transformacion de datos

      a.Tratamiento de valores faltantes
      b.Detección y eliminación de Outliers

+ Implementacion de modelos de recomendacion

      a-Normal predictor: Modelo benchmark 
      b.SVD
      c.SVDpp
      d.CoClustering

+ Recomendacion de videojuegos

      a.Recomendaciones por usuario
      b.Recomendaciones por videojuego


## Breast Cancer Challenge
En el mes de sensibilización sobre el cancer de mama, se armo este proyecto con el objetivo de predecir si un tumor es benigno o maligno usando como input muestras de tumores.
En este proyecto se implementaron los siguientes features:

+ Importacion y estado de salud del dataset

+ EDA & correlaciones con la variable a predecir

+ Implementacion de un modelo de ML en forma de benchmark

      a.Arbol de decisión
    

+ Implementacion de tres modelos de ML con un tunning de los hiperparametros

      a.Arbol de decisión
      b.Vecinos mas cercanos
      c.Regresion logistica

+ Conclusiones

+ Anexo: threshold para todos los modelos


## Justicia con data
En el día internacional contra la violencia de género, se armo este desafio con el objetivo de explorar los datos y encontrar patrones en las denuncias presentadas en el juzgado numero 10 de CABA respecto a casos de violencia de genero.
El proyecto esta conformado por lo siguientes features:

+ Importacion y estado de salud del dataset

+ Analisis exploratorio de datos

+ Preparacion de datos

+ Implementacion de un modelo de clustering con la tecnica k-means

+ Conclusiones





