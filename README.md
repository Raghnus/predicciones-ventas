# predicciones-ventas

## Descripción
Haciendo uso de técnicas de regreción lineal, modelos knn y random forest, se pretende lograr una predicción de ventas para una tienda.

## Datos
### Carga de datos y limpieza
Durante todo el proces, se hizo uso del archivo https://drive.google.com/file/d/1ARmASpPilpstmf7beq6UGlv2pa4aPGmv/view?usp=sharing que contiene los datos que van a ser procesados.

### Limpieza
Al realizar las observaciones correspondientes de los datos, se pudo observar que presentaba datos con registros mal anotados, así como datos faltantes.
Para los datos mal registrados se procedio a agruparlos en las categorías que buscaban representar y cambiarlos.
Referente a los datos faltantes, se procedio a rellenarlos por medio de interpolación lineal y completando los datos categoricos, como valores no asignados.

### Visualizaciones
Para la visualización de datos obtamos a buscar las ventas según la tienda, categoría de producto, ubicación de la tienda, entre otras.

![image](https://user-images.githubusercontent.com/43797990/153787404-50aeeee7-f576-4450-a44c-e22b48229030.png)

![image](https://user-images.githubusercontent.com/43797990/153787425-dce96720-77e2-4511-9673-9ffa2d888c2c.png)

![image](https://user-images.githubusercontent.com/43797990/153787440-2d36a9b9-dd03-46f8-9596-f69866dbf7c5.png)

### Modelo predictivo
Para la realización del modelo predictivo, se realizo un cambio de variables categóricas por numéricos, posterior a esto se procedió con la división del conjunto de datos en una parte para el entrenamiento y otra para la prueba del mismo.
Se realizaron 3 modelos predictivos, uno de regresión lineal, uno KNN vecino más cercano y uno de random forest.

### Resultados
Referente a los modelos KNN y random forest se realizó la prueba con varios valores para vecinos y arboles, respectivamente para obtener el modelo con la mayor precisión posobile.
El resultado de precisión más alta obtenida en esta ocasión fue el KNN con una precisión cercana al 60%.

### Recomendaciones
Las recomendaciones van desde la cantidad y calidad de datos, sugiriendo un incremento en las mismas, así como una mejor manipulación de la misma para obtener mejores resultados referentes a la precisión del modelo.
