# Portafolio-implementacion-IA-1
Evidencia individual de la implementación de técnicas de machine learning.

El modelo de machine learning que se implementó fue 'Regresion lineal', cuyo objetivo es encontrar una ecuación lineal que mejor se ajuste a los datos para permitir hacer predicciones o inferencias sobre la variable dependiente en función de la o las variables independientes.

Los datos utilizados fueron obtenidos de Kaggle, de una base llamada 'CO2 Emission by Vehicles', la cual está en el archivo 'co2_prueba.csv'.
Enlace a la base de kaggle: https://www.kaggle.com/datasets/debajyotipodder/co2-emission-by-vehicles 

Los archivos a revisar son los siguientes:
- La implementación sin uso de framework: 'implementacion_sinframework.ipynb'. https://github.com/michelle-morales/Portafolio-implementacion-IA-1/blob/main/implementacion_sinframework.ipynb 
- La implementación con framework: 'implementacion_framework.ipynb'. https://github.com/michelle-morales/Portafolio-implementacion-IA-1/blob/main/implementacion_framework.ipynb
- El refinamiento del modelo: 'implementacion_refinamiento.ipynb'. https://github.com/michelle-morales/Portafolio-implementacion-IA-1/blob/main/implementacion_refinamiento.ipynb 


Para todos los codigos se usa la misma base de datos antes mencionada.

El reporte se encuentra en los archivos ipynb. Todos los códigos tienen comentarios, observaciones y descripciones de los procedimientos, así como los resultados obtenidos. 

Cambios realizados:
- Se agregó información en el Readme como el nombre del dataset utilizado y se señalaron los archivos a revisar.
- En el reporte también se agregó información del dataset, así como una breve descripción de las variables usadas para implementar el modelo. También se describió el problema y la solución implementada, que en este caso es una regresión.
- Se agregaron gráficas para comparar las predicciones con los datos reales y analizar mejor el modelo.
- En la implementación con framework y el refinamiento del modelo se agregó al split el conjunto de validación ya que se estaba trabajando solo con el Train y Test. Además se agregó la sección de validación del modelo para mejorar los hiperparámetros.
- En el refinamiento se corrigió el diagnóstico de sesgo y varianza.
- Se argumentaron los cambios al modelo y la elección del modelo final.

En este portafolio también se encuentra la implementación del modelo de 'El precio de los autos', tanto en código como el reporte. Para este trabajo se usó la base de datos 'Precio_autos' la cual se encuentra en el archivo 'precio_autos.csv'.

Archivos a revisar:
- Reporte de implementación. 'Reporte_precio_autos.pdf'
- Código de la implementación. 'autos.Rmd'
