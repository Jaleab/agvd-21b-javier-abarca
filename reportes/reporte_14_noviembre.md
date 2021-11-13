### Reporte 14-11-2021
### Autor: Javier Abarca Jimenez
### Carné: B70018
 
## Resumen de los temas
## 1. Clustering
Es una técnica no supervisada cuya función es la de dividir en grupos un conjunto de datos, estos grupos pueden ser significativos, útiles, ambos o ninguno. Algunos usos son:
  * Hacer grupos o clases entre datos que comparten características
  * Análisis y comprender el espacio con el que se está trabajando
 
Estos grupos logran tener utilidad al representar de manera abstracta a cierta cantidad de elementos individuales, estos se convierten en segmentos prototipo. Estos últimos sirven para resúmenes (Técnicas como PCA aplicados a prototipos específicos), comprensión y en la búsqueda de vecinos cercanos.
 
## 1.1 Principios
Los principios de clustering son los siguientes:
  * Una métrica de similitud
  * Codificar atributos categoricas
  * Transformar atributos numéricos
  * Cantidad de clusters
 
## 1.2 Tipos
Las técnicas de clustering se dividen en los siguientes:
  * ### Particionamiento
    * K-means: Define el prototipo como un centroide (media de todos los puntos). Se utilizan objetos con valores continuos en espacios n-dimensionales. Existe también K-mode, este valga la redundancia utiliza la moda en vez de la media.
    * K- medoids: El prototipo se define como el punto más representativo entre todo el grupo, se aplica a los datos mediante una medida de similitud. Los medoides son un punto en los datos, al cambio un centroide es “sintético”.
  * ### Jerarquicos
    Es una forma de visualizar clusters unidos mediante múltiples niveles. Alguno de estos son BIRCH, Chameleon
  * ### Densidad
    Los clusters son regiones densas de objetos que estan separadas por regiones con poca densidad, pueden filtrar outliers. Algunas técnicas de este tipo son DBSCAN, OPTICS y DENCLUE
  * ### Grid
    Tienen un tiempo de procesamiento rápido, ya que depende del tamaño de la cuadrícula y no de la cantidad de datos. Algunos ejemplos de este tipo son STING y CLIQUE.
 
## 2 Características de los datos
  ## 2.1 Alta dimensionalidad
  * Muchos algoritmos no funcionan.
  * Entre mayor dimensionalidad, mayor volumen y si la cantidad de puntos no aumenta, la densidad va a tender a 0.
  * El cálculo de proximidad entre puntos si se tiene una mayor cantidad de atributos o dimensiones, se vuelve más uniforme
  ## 2.2 Tamaño
  * Existen algoritmos que trabajan bien con un tamaño de datos, pero al aplicar este mismo a otro conjunto de datos, ya sea de menor o mayor tamaño, puede ser que no funcione bien.
  ## 2.3 Ruido y outliers
  * Afecta a los algoritmos basados en prototipos.
  * Aplicar técnicas de limpieza antes de hacer clustering.
 
  # 2.4 Recomendación
  Si los algoritmos utilizan medidas de proximidad, es recomendable aplicar técnicas de reducción de dimensionalidad.
 
## 3. Self Organising Feature Map
Es una técnica de segmentación y visualización de datos de alta dimensionalidad (segunda o tercera, por lo general), estas técnicas son más conocidas como Self Organising Maps. Es un método de tipo no supervisado y esta técnica también sirve para tareas de reducción de dimensionalidad.
 
Esta variante de clustering basado en prototipos tiene como objetivo encontrar un conjunto de centroides a los cuales se van a relacionar o asociar los puntos del data set. Estos centroides siempre van a estar asociado a una neurona.
 
## Comentarios
  * Solo había trabajado con uno de los más conocidos (k-means) y era un tema que me interesaba (aún).
 
## Dudas
  * Por el momento no tengo dudas, probablemente surjan al hacer la tarea de este tema.
 
## Usos
  * Lograr identificar, en un problema en el que se desea agrupar los datos bajo ciertos criterios, cuál de las técnicas de segmentación o clustering es mas apropiada y que obstáculos se pueden encontrar.
 
## Material extra
  * Para este reporte no se utilizó material extra.