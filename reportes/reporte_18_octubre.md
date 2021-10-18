### Reporte 18-10-2021
### Autor: Javier Abarca Jiménez 
### Carné: B70018

## Resumen de los temas
* ## Modelos lineales
    Este tipo de modelos suelen funcionar mejor en problemas de alta dimensionalidad. En esta técnica lo que se busca es minimizar un error/pérdida (loss). Estos algoritmos son sensibles a la escala de los atributos, por lo que requieren que se apliquen técnicas de regularización o estandarización. Algunos tipos de regularizaciones son:
    * Alfa y C (complejidad): Función de costo compuesta por el error cuadrático medio, el alfa y la complejidad.
    * L1 o Lasso: Funciona bien para atributos irrelevantes o si no se sospecha que existe correlación entre atributos.
    * L2 o Ridge: Funciona bien si se sospecha que existe correlación entre atributos.
    * Elastic net: Funciona bien cuando hay una gran cantidad de atributos porque le aplica Lasso o Ridge según un valor que se considere más apropiado.

* ## Perceptrón
    Un perceptrón es una estructura computacional que recibe varias entradas y con esto calcula un valor z. Esta estructura tiene dos partes, en una hace una operación sobre las entradas y en la otra realiza una operación sobre el valor z calculado. Según este último lado se decide si la señal se propaga o es suprimida. Las regresiones logísticas utilizan esta misma lógica.

* ## Redes neuronales
    Las redes neuronales se pueden ver como métodos lineales de manera general, pero en este procesamiento se involucran múltiples niveles para llegar a tomar una decisión. Cada una de las neuronas aplican alguna función no lineal

* ## Maquina de soporte vectorial
    Los algoritmos de entrenamiento SVM (Support Vector Machines) buscan encontrar una línea o un hiperplano que sea la mejor separación entre clases. Este hiperplano es definido mediante un margen utilizado para la toma de decisiones según una distancia calculada. Este algoritmo tiene modificaciones como la basada en pesos, en esta modificación cuando ocurre una clasificación errónea hay una penalización o castigo según el peso.
    
## Comentarios
  * Esta materia sirvió bastante para poder desarrollar mejor la parte práctica del video 1.
 
## Dudas
  * No tengo dudas en estos temas.
 
## Usos
  * Poder entender lo que sucede al emplear estos modelos para resolver una problemática de interés.
 
## Material extra
  * No se utilizó material extra.
