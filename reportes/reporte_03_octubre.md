### Reporte 3-10-2021
### Autor:  Javier Abarca Jimenez 
### Carné: B70018

## Resumen de los temas
  * Existen tres tipos de uso para los conjuntos de datos, estos son los siguientes:
    * Para entrenamiento: Este es el conjunto de datos que se le da al modelo para que se ajuste. No debe ser utilizado para evaluar la precisión del modelo obtenido.
    * Para validación: Es para ir ajustando el modelo, pero al mismo tiempo ir observando los resultados obtenidos para evaluarlo.
    * Para pruebas: La elección de este conjunto de datos se debe realizar con cuidado, ya que es el que va a evaluar el modelo final.

El rendimiento de un modelo se puede medir mediante análisis estadístico, observando la distribución de errores y utilizando matrices de confusión. Esta última consiste en una matriz que relaciona los valores verdaderos con los valores predichos por el modelo para conocer su precisión.

Los árboles de decisión suelen ser intuitivos: estos pueden ser multiclase y si el dato es continuo, son agrupados en umbrales. En estos árboles se conoce como una hoja pura si todos los elementos pertenecen a una misma clase. Se debe controlar la complejidad de estos árboles, es decir evitar que ocurra un sobreajuste (todas las hojas son puras).

* ## Árboles de decisión
  * Ventajas:
    * Fácil de interpretar.
    * Se pueden utilizar atributos numéricos y categóricos.
    * No es sensible a datos faltantes.

  * Desventajas:
    * Complejidad para interpretar crece bastante según el tamaño del árbol.
    * Suelen suceder sobreajustes.
    * Sensibilidad a cambios en el data set.

* ## Random Forests
  Es una colección de árboles (cada uno aprendió de manera distinta) y las predicciones se toman al calcular el promedio del bosque.

  * Ventajas:
    * No requiere cambio de escala.
    * Se puede paralelizar.
    * Menor sobreajuste que en árboles individuales.
    * Mejores resultados porque los árboles aprenden de manera individual.

  * Desventajas:
    * Difícil de interpretar.
    * Son costosos con respecto a tiempo y memoria según el tamaño del dataset.
    * No funcionan bien con datos dispersos (por ejemplo, datos de puro texto).

* ## Gradient boosting
  Árboles seriales configurados, cada uno, para corregir el error del árbol anterior. Es un algoritmo greedy y estos árboles son de 4 a 8 niveles. Estos son más sensibles a los parámetros que Random Forest.
    * Ventajas: 
      * Más rápidos que Random Forests.
      * Robustez en escala de los datos y los tipos de atributos.
    * Desventajas:
      * Requieren ajustar parámetros.
      * Tardan en entrenarse.
* ## Entrenamiento y validación
  Si se realiza el entrenamiento y la validación del modelo utilizando splits del conjunto de datos, esto va a producir sensibilidad debido a esta dependencia. Un método utilizado es Cross-validation, este particiona el dataset para entregar varios modelos con estos diferentes subconjuntos. Este último método tiene diferentes técnicas, alguna de estas son las siguientes:
    * Stratified K-Fold Cross-validation: Se obtienen resultados robustos.
    * Leave one out Cross Validation (LOOCV): Utilizada con un conjunto de datos con un tamaño pequeño. Se utiliza bastante.
    * Shuffle split Cross Validation: Utilizada con conjunto de datos grandes.
    * Cross-validation with Groups: Se utiliza cuando las observaciones provienen de una misma fuente (observaciones que le corresponden a un grupo), por ejemplo si es de una misma persona.

* ## Comentarios
  * La teoría cubierta durante estas dos semanas aclararon conceptos utilizados en las prácticas, por lo que fue de bastante valor.

* ## Dudas
  * No tengo dudas en estos temas.
  
* ## Usos
  * Crear modelos que pueden llegar a obtener buenas predicciones y poder ajustarlos al conocer la función de sus parámetros.

* ## Material extra 
  * No se utilizó material extra.
