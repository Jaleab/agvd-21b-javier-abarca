### Reporte 05-09-2021
### Autor:  Javier Abarca Jimenez 
### Carné: B70018

* ## Resumen de los temas
    * Big data: 
        * Conceptualización con 5 V's: 
          * Volumen.
          * Velocidad.
          * Variedad.
          * Veracidad.
          * Valor.
        * Hadoop Distributed File System: Sistema para almacenar Big Data, tareas paralelizadas mediante map reduce.
        * Data mining: Predecesor de Big Data. Un ejemplo muy popular es el caso de Pop tarts durante época de huracanes.
    * Data cleaning:
      * Valores faltantes, el ruido y las inconsistencias contribuyen a que los datos sean inexactos.
      * Ruido: Se puede encontrar al observar el valor de la media, de la mediana, de la moda, si la distribución de los datos es simétrica o si están sesgados.
      * Los datos se deben examinar siguiendo las siguiente reglas:
        * Regla única: Cada valor de un atributo específico tiene que ser único.
        * Regla consecutiva: No pueden faltar valores entre el rango que existe entre el minimo y maximo de un atributo. También deben ser únicos.
        * Regla de nulo: Registro en blanco, signos de pregunta, caracteres especiales u otros valores pueden indicar el valor de nulo. Esta regla debe indicar por ejemplo un 0 o -1 para los atributos numéricos, en blanco para los caracteres.
    * Hay herramientas que ayudan a limpiar, explorar y transformar como Open Refine para evitar hacer este trabajo completamente manual o programando.
    * Exploración y limpieza de datos
    	* Spurious Correlations: Correlaciones falsas. No tienen una conexión lógica, sino que poseen un "variable escondida". Ejemplos en: tylervigen.com
    	* Pasos iniciales: 
    		* Conocer el origen del data set.
    		* Tamaño del dataset para técnicas y herramientas.
    		* Significado de los atributos. Los datos pueden contener códigos que se debe conocer a que se refiere.
    		* Identificar si los atributos son numéricos o categóricos
    	* Cuarteto de Anscombe: Conjunto de datos con valores de media, varianza y correlación iguales se puede creer que son iguales estos datasets, pero al observar visualmente se puede verificar si existe diferencia.
    	* Análisis exploratorio: Es un primer paso y consiste en un conjunto de técnicas de estadística descriptiva, visualización, cambios de enfoque sobre el conjunto de datos.

* ## Comentarios
  * La materia teórica vista se ha podido asimilar mejor gracias a los ejemplos o casos reales.
  * La herramienta Open Refine es bastante útil.

* ## Dudas
  * ¿Cómo saber si un conjunto de datos está completamente limpio?
  
* ## Usos
  * La materia de limpieza, exploración y transformación, y la herramienta Open Refine van a ser útiles si en un proyecto se requiere (probablemente es deseable) sacarle provecho a los datos que se están generando para posteriormente graficarlos y llegar a conclusiones provechosas.

* ## Material extra 
  * No se utilizó material extra.