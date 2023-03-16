# Analisis-salarios
Este repositorio contiene el código del proyecto de preprocesamiento y análisis de datos de un dataset sobre remuneraciones de docentes y la creación de un modelo de predicción para el mismo dataset
## Tabla de contenidos
* [Dataset](#dataset)
* [Exploración](#exploración)
* [Modelo](#modelo)
* [Resultados](#resultados)
## Dataset
El conjunto de datos consiste en los salarios de nueve meses recogidos de 397 profesores universitarios en los EE.UU. durante 2008 y 2009. Se puede encontrar el dataset en el siguiente link https://rpubs.com/kibbuz/Salaries

## Exploración
* Para la exploración visual de los datos se utilizaron tablas y gráficos de dispersión y de caja y bigote. 
* Para comprobar la normalidad de los datos se utilizó la técnica del QQ-Plot.
* Conclusión de la exploración de los datos.

## Modelo
Se realizaron dos modelos utilizando los algoritmos Rigde y Lasso. Se consideraró el 80% de los datos para realizar el entrenamiento y el 20% para test.

## Resultados

Algoritmo | MSE | 
--- | --- |
Ridge | 642.549.192 | 
Lasso | 200.634.319 | 

Se considera que el modelo no tiene un rendimiento correcto debido al alto valor del MSE. Se considera que esto se puede deber a que la cantidad de datos no es suficiente y tal como se puede observar en el análsis exploratorio de los datos de manera gráfica ; las variables continuas con respecto a la variable objetivo (salario) mantienen una gran dispersión, no existe una clara dependencia lineal entre variables
