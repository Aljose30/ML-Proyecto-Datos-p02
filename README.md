Proyecto-2-dataton-Mercado-inmobiliario
implementacion de modelos de clasificación con Ml supervisado y no supervisado que permite clasificar el precio de las propiedades en venta, utilizando los datos disponibles.

descripcion de archivos dentro de repositorio
exploracion_data_houses.ipynb: este archivo contiene las herramientas y pasos que utilice para la visualizacion y comprension de mis datos

ml_supervisado_data_houses.ipynb: este archivo contiene los paso que segui para la implementacion y aplicasion de el modelo de machine learnig, cada paso esta comentado con mi proceso logico y descripcion de el codigo que utilice

ALEX-MGS.csv: este archivo es el resultado de el procesar el data frame de test utilizando mi modelo de machine learnig ya entrenado, este esta guardado en un archivo tipo csv en una columna con valores 0 y 1 representado el 1 valor 'low' y 0 no 'low'

descripcion de proceso para implementacion de modelo machine learnig
1 - El primer paso que realice fue la creacion de dataframe a partir los archivos recivido en formato parquet

2 - En este paso explore los archivos de una manera general para comprender en que y como son usados los datos que tengo disponibles para esto utlice herramientas como las siguientes: .head, .describe, .value_count, .isnull. etc.

3 - Este paso realize mas a profundidad el EDA, realice busqueda de nulos y eliminacion o reemplazo dependiendo de el caso, implemente herramientas de visualizacion para comprende la distribucion y forma de mis datos, continue con la normalizacion de mis datos y la depuracion de mis dataframes para su implementacion en el modelo este paso esta descrito a mas profundidad en el archivo exploracion_data_houses.ipynb:

4 - En este paso implemente todo lo necesario para la ejecucion correcta en el modelo que elegi, tambien realice las pruebas correspondientes para cersiorarme que funcionara y finalmente genere un archivo con las predicciones que resultaron de el modelo. este paso esta descrito a mas profundidad en el archivo ml_supervisado_data_houses.ipynb
