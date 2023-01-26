#README!!!

Este código tiene como objetivo clasificar precios de viviendas en dos categorías: precios inferiores a $999 y precios mayores a $999. El conjunto de datos utilizado está compuesto por información sobre viviendas, incluyendo características como el tipo de propiedad, el número de baños y la ubicación.

## Dependencias

Para ejecutar este código, es necesario tener las siguientes dependencias instaladas:

- numpy
- pandas
- matplotlib
- seaborn
- sklearn

## Proceso

1. Se importan los paquetes necesarios y se cargan los conjuntos de datos de entrenamiento y prueba.

2. Se crea una nueva columna en el conjunto de entrenamiento llamada "category_price", la cual clasifica los precios en dos categorías: precios inferiores a $999 y precios mayores a $999.

3. Se eliminan columnas innecesarias del conjunto de entrenamiento y prueba.

4. Se realiza la categorización de las variables categóricas en ambos conjuntos de datos.

5. Se seleccionan las columnas presentes en ambos conjuntos de datos.

6. Se separa el conjunto de entrenamiento en dos subconjuntos, uno para entrenamiento y otro para pruebas.

7. Se escala los datos para que todas las características tengan la misma importancia.

8. Se entrena un modelo de Random Forest con el conjunto de entrenamiento.

9. Se hacen predicciones con el modelo entrenado en el conjunto de pruebas y en los datos de pruebas.

10. Se calcula la precisión y el recall del modelo en el conjunto de pruebas.
