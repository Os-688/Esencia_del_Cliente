<p align="center">
   <h1 align="center"> Mi proyecto Esencia del Cliente (Desafio).</h1>
</p>


<p align="center">
  <img src="Imagenes/Grafica7.PNG" alt="Grafica de cloropletas">
</p>

## Descripción:

Esencia del cliente es un proyecto de machine learning sobre la optimizacion y creacion de distintos modelos, revisando y eljiendo los mejores parametros e hiperparametros. 
Esta relacionado con el analisis de clientes de una linea de supemercados.

![Grafica de barras de carreras](Imagenes/Grafica6.PNG)

## Instrucciones de Uso

Para ejecutar el proyecto, se recomienda ejecutar el notebook en Google Colab. Si optas por otro método, asegúrate de descargar todas las librerías usadas y luego importarlas. Con esto, podrás ejecutar todas las celdas de código.

## Características Principales

- Graficas de calor y correlacion para la eleccion de las mejores variables.
- Traduccion del dataframe.
- Graficas enfocadas en encontrar caracteristicas de los clientes(datos).
- Observaciones e Hipotesis.
- Eleccion de variables y prueba para elejir las mejores columnas(Variables) con diferentes tipos de datos(categorico ordinal,nominal y numerico).
- Modelo de clusterizacion Kmeans con pruebas de silhouette, davies_bouldin, calinski_harabasz.
- Prueba de integridad.
- Modelos con los tres tipos de datos mencionados con el cumplimiento de todas las pruebas anteriores.
- OneHotEncoding, Estandarizacion y dummies.
- Descripcion de clusters y recomendaciones a efectuar.
- Funciones con bucles y GridSearchCv para obtener los mejores hiperparametros en arboles de decision, bosques de decision y SVC.
- Tratamiento con predicciones del modelo.

![Grafica de barras horizontales](Imagenes/Grafica1.PNG)

![Grafica de calor](Imagenes/Grafica5.PNG)

![Grafica con sublienzo](Imagenes/Grafica4.PNG)

![Graficas de lineas](Imagenes/Grafica3.PNG)

![Graficas de lineas](Imagenes/Grafica2.PNG)




## Requisitos Previos

### Google Colab
1. Sigue el orden de ejecución de cada sección.

### Otros Entornos
1. Instala las siguientes bibliotecas:
   
  - pandas
  - numpy
  - matplotlib
     - matplotlib.pyplot 
  - seaborn
  - scikit-learn
     - sklearn.tree.DecisionTreeClassifier
     - sklearn.svm.SVC
     - sklearn.ensemble.RandomForestClassifier
     - sklearn.cluster.KMeans
     - sklearn.metrics.silhouette_score
     - sklearn.metrics.davies_bouldin_score
     - sklearn.metrics.calinski_harabasz_score
     - sklearn.model_selection.train_test_split
     - sklearn.preprocessing.OneHotEncoder
     - sklearn.preprocessing.StandardScaler
     - sklearn.model_selection.cross_validate
     - sklearn.model_selection.GridSearchCV


```python
pip install pandas
pip install requests
pip install fuzzywuzzy
pip install seaborn
pip install matplotlib
pip install plotly
pip install bar_chart_race
pip install numpy
```

## Instalación

Para instalar el proyecto, sigue la secuencia de ejecución en Google Colab, la cual instalará las bibliotecas necesarias. Si utilizas otro entorno, instala cada biblioteca antes de importarlas.

## Ejemplos de Uso

La ejecucion de las celdas es lineal. Podras ver todos los graficos y codigo en funcionamiento siguiendo la linea de ejecución.
![Ejemplo visual del texto de arriba](Imagenes/linea_ejecucion.PNG)

## Autor

- **Os-688**

## Agradecimientos

Agradezco a scikit-learn.

## Estado del Proyecto

Versión 1.0 estable. Última actualización: 04/12/2023.
