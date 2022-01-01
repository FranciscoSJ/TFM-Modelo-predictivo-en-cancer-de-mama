# Modelo predictivo en cáncer de mama. Reducción de la dimensionalidad en la detección del tumor maligno.

En este repositorio se encuentra la implementación del Trabajo de Fin de Máster de la Titulación Máster en Ciencia de Datos por la Universitat Oberta de Catalunya (UOC).

En esencia, este trabajo consiste en aplicación de un proceso de minería de datos sobre un juego de datos bastante conocido y de libre acceso, conjunto de datos del cáncer de mama de Wisonsin.
Disponible en: https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+%28original%29

A continuación se resume las fases de las que consta este trabajo y que se pueden encontrar como resultado de la ejecución del código:

**1. Limpieza del Dataset.** En esta etapa, tras haber realizado la lectura del fichero de datos del Hospital de Wisconsin, realizaremos diferentes operaciones de limpieza y preprocesado de los datos para optimizar su calidad y poder así extraer el máximo de información con la mayor precisión posible. Prestaremos especial atención al datatype de los datos, los campos vacíos, etc. para aplicar las operaciones de transformación e imputación de valores que consideremos necesarias.

**2. Estadística descriptiva del dataset.** Calcularemos algunas estadísticas básicas de nuestro dataset para tener una visión superficial de cómo se distribuyen los datos, así como qué posibles atributos pueden tener mayor/menor correlación.

**3. Reducción de la dimensionalidad.** En esta fase, aplicaremos técnicas como PCA, t-SNE o UMAP que nos permitan reducir el tamaño del dataset.

**4. Algoritmos de clasificación.** Tras la reducción de dimensionalidad, construiremos nuestros modelos con los algoritmos de clasificación: Decision Tree, KNN, Naive-Bayes y SVM. Dividiremos previamente el conjunto de datos al que le habremos aplicado previamente la reducción de la dimensionalidad en train set y test set. En cada uno de los modelos trataremos de de ajustar los parámetros adecuados que optimicen la precisión del modelo en cuestión mediante el oportuno hyperparameter tuning.

**5. Evaluación.** Finalmente, tras la aplicación de cada algoritmo, tendremos que cotrastar el resultado obtenido con el juego de datos original, para así verificar la precisión encontrada y la bondad tanto del modelo como de la propia reducción de la dimensionalidad.


### En resumen:

**1. Limpieza del dataset.**

**2. Estadísitica descriptiva**

**3. Reducción de la dimensionalidad**

 - PCA
  
    - Decision Tree

    - KNN

    - Naive-Bayes

    - SVM

- t-SNE

    - Decision Tree
    - KNN
    - Naive-Bayes
    - SVM
    
- UMAP

    - Decision Tree
    - KNN
    - Naive-Bayes
    - SVM
