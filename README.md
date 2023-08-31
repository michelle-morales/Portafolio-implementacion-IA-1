# Portafolio-implementacion-IA-1
Evidencia individual de la implementación de una técnica de machine learning sin el uso de un framework y con uso de framework.

La técnica implementada fue regresion lineal.

Los datos utilizados fueron obtenidos de Kaggle, de una base llamada 'CO2 Emission by Vehicles', la cual está en el archivo 'co2_prueba.csv'.
La implementación sin framework está en el archivo llamado 'implementacion_sinframework.ipynb'. La implementación con framework está en el archivo 'implementacion_framework.ipynb'

Se eligió solo una variable para implementar el modelo, la cual fue 'Fuel Consumption Comb (mpg)' y la variable a predecir fue 'CO2 Emissions(g/km)'. 
Para la implementación sin framework los datos se dividieron a la mitad para usar una parte en el train o otra en el test. Para la implementación con framework se usó un train_size = 0.75.

Finalmente se evaluó el modelo con mean_squared_error, mean_absolute_error y r_squared.
