# ML-Proyecto-Datos-p02
Aprendizaje supervisado - Prediccion de precios de vivienda


Este código tiene como objetivo clasificar precios de viviendas en dos categorías: precios inferiores a $999 y precios mayores a $999. El conjunto de datos utilizados está compuesto por información sobre viviendas, características incluyendo como el tipo de propiedad, el número de baños y la ubicación.

## Acceso a los archivos:

### https://drive.google.com/drive/folders/1xLzPvyqmxqV0Dkmw-RmZQmKJh4UipNlQ?usp=share_link

## dependencias
Para ejecutar este código, es necesario tener las siguientes dependencias instaladas:

### numb
### pandas
### matplotlib
### seaborn
### sklearn

#### Se importan los paquetes necesarios y se cargan los conjuntos de datos de entrenamiento y prueba.

#### Se crea una nueva columna en el conjunto de entrenamiento "category_price", la llamada cual clasifica los precios en dos categorías: precios inferiores a $999 y precios mayores a $999.

####  Se eliminan las columnas necesarias del conjunto de entrenamiento y prueba.

####  Se realiza la categorización de las variables categóricas en ambos conjuntos de datos.

####  Se seleccionan las columnas presentes en ambos conjuntos de datos.

####  Se separa el conjunto de entrenamiento en dos subconjuntos, uno para entrenamiento y otro para pruebas.

####  Se escalan los datos para que todas las características tengan la misma importancia.

####  Se entrena un modelo de Random Forest con el conjunto de entrenamiento.

####  Se hacen predicciones con el modelo alterado en el conjunto de pruebas y en los datos de pruebas.

####  Se calcula la precisión y el recuerdo del modelo en el conjunto de pruebas.
