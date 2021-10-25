### Reporte Conceptual Multi-Layer Perceptron
### Estudiante: Javier Abarca Jimenez
### Carné: B70018
### Enlace: [Crash Course On Multi-Layer Perceptron Neural Networks](https://machinelearningmastery.com/neural-networks-crash-course/)
 
## Resumen
* ### Multi-Layer Perceptrons
  El objetivo no es crear modelos realistas del cerebro, sino desarrollar algoritmos y estructuras de datos robustos que se pueden utilizar para modelar problemas difíciles. Estas redes son buenas por su habilidad de aprender a representar los datos de pruebas y cómo relacionar esto con la variable de salida que se desea predecir
 
* ### Neurons
  El componente básico de las redes neuronales son las neuronas artificiales, tiene señales de entrada ponderadas y producen una señal de salida mediante una función de activación.
  * ### Neuron Weights
    Los pesos comunmente se inicializan con pequeños valores aleatorios, pero se pueden utilizar esquemas de inicialización más complejos.
  * ### Activation
     Las entradas ponderadas se suman y pasan a través de una función de activación, a veces llamada función de transferencia.
   
* ### Networks of Neurons
  Una fila de neuronas se denomina capa y una red puede tener varias capas y la arquitectura de estas es conocida como topología de red.
  * ### Input or Visible Layers
    La capa inferior que toma la entrada de su conjunto de datos se llama capa visible, porque es la parte expuesta de la red. En estas capas se utiliza una neurona por columna del conjunto de datos.
  * ### Hidden Layers
    Las capas posteriores a la capa de entrada se denominan capas ocultas porque no están directamente expuestas a la entrada. El aprendizaje profundo (por ser lentas entrenando) puede referirse a tener muchas capas ocultas en su red neuronal.
  * ### Output Layer
    Es responsable de generar un valor o vector de valores que correspondan al formato requerido para el problema.
 
* ### Training Networks
  * ### Data preparation
    Los datos deben ser numéricos, sino lo son se deben codificar. Esto mismo aplica para la variable de salida. Asimismo, las redes neuronales requieren que toda entrada sea normalizada de la misma manera.
  * ### Stochastic Gradient Descent
    Es el clásico y algoritmo de entrenamiento favorito. Este algoritmo procesa fila por fila como entrada, esta entrada va activando neuronas y finalmente se producen valores de salida. Por último, esta salida es comparada con un valor esperado y un error es calculado, este error se propaga por la red para poder actualizar los pesos apropiadamente.
  * ### Weight Updates
    Los pesos en la red se actualizan a partir de los errores calculados por cada entrada al realizar el entrenamiento y esto se llama aprendizaje en línea. Puede resultar en cambios rápidos pero también caóticos en la red.
  * ### Prediction
    Una vez que se ha entrenado una red neuronal, se puede utilizar para hacer predicciones para pruebas o validaciones.
 
## Comentarios
Desconocía la razón del nombre de aprendizaje profundo.
 
## Dudas
Por el momento quedó clara la materia.