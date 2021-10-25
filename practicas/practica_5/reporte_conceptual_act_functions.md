### Reporte Conceptual Multi-Layer Perceptron
### Estudiante: Javier Abarca Jimenez
### Carné: B70018
### Enlace: [CHow to Choose an Activation Function for Deep Learning](https://machinelearningmastery.com/choose-an-activation-function-for-deep-learning/)
 
## Resumen
* ### Activation Functions
    Sirven para definir como la suma ponderada de la entrada se transforma en una salida de un nodo o nodos en una capa de la red. Todas las capas ocultas suelen utilizar la misma función de activación. La capa de salida normalmente utiliza una función de activación diferente que las capas ocultas y depende del tipo de predicción requerida por el modelo.
* ### Activation for Hidden Layers
    Tres funciones de activación para capas ocultas:
    * Rectified Linear Activation (ReLU): Es la mas utilizada por lo simple de implementar y por su efectividad superando limitaciones que funciones de activación tienen dificultad de lograrlo. Es la recomendacion predeterminada.
    * Logistic (Sigmoid): Es buena práctica utilizar una inicialización de pesos "Xavier Normal" y estandarizar los datos de entrada a un rango entre 0 y 1.
    * Hyperbolic Tangent (Tanh): La función es muy similar a la logística y por esta misma razón se recomienda la misma practica al usarla.
* ### How to Choose a Hidden Layer Activation Function
  * Perceptrón multicapa (MLP): Función de activación de ReLU.
  * Red neuronal convolucional (CNN): Función de activación de ReLU.
  * Red neuronal recurrente: Función de activación Tanh y / o sigmoidea.
* ### How to Choose an Output Activation Function
Si el problema es de regresión, se debe utilizar una función de activación lineal con un nodo.
Si el problema es de clasificación, existen tres tipos principales de estos problemas. Recomendaciones según el tipo de problema:
  * Clasificación binaria: Un nodo, función de activación sigmoidea.
  * Clasificación multiclase: Un nodo por clase, función de activación softmax.
  * Clasificación de múltiples etiquetas: un nodo por clase, función de activación sigmoid.
 
## Comentarios
La función de activación ReLU para las capas ocultas cuando hicimos el caso de uso para el video fue la que lograba mejor precisión entonces si le veo sentido que sea considera como la "recomendación predeterminada".
 
## Dudas
Por el momento quedó clara la materia.
