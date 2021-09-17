### Reporte Tarea 1
### Autor: Javier Abarca Jimenez 
### Carné: B70018

* ## Dataset elegido
    * Google Play Store Apps: https://www.kaggle.com/lava18/google-play-store-apps

* ## Preguntas de investigacion
    * Cual es la categoria de aplicaciones con mayor cantidad de instalaciones?
    * Cuales son las aplicaciones con mayor cantidad de reseñas?
    * Cual es la aplicacion con categoria "COMICS"  con la mayor cantidad de reseñas?
* ## OpenRefine
  * ### Problemas identificados
    * El formato del atributo instalaciones y price no es apto para tratarlo como numerico.
      * Correccion: Eliminar el carácter '+', eliminar las ',' y especificar en el nombre del atributo que son más instalaciones que la cantidad del registro (es un minimo). En el caso de price, eliminar el caracter '\$' y cambiar el nombre del atributo a "Price ($)"
    * Existen valores numericos en columnas categoricas (Category), valores no numericos en columnas numericas (Reviews), entre otros problemas similares.
      * Correccion: Realizar facets para poder editar estos registros a valores como (NaN, Not defined). En el caso de un fila con varios registros con valores no utiles, eliminarlo.
    * Los registros del atributo Size no son numericos y no tienen una unidad estandar.
      * Correccion: Nombrar la columna "Size" como "Size (M)", eliminar las M de los registros y pasar los convertir los valores que estan en kilos (k) a Mega (M).
  * ### Atributos importantes
    * Installs: Cantidad minima de instalaciones de cada una de las aplicaciones. Sirve para ordenar los datos y poder responder algunas de las preguntas de investigacion. 
    * Category: Categoria de cada una de las aplicaciones. Sirve para agrupar y para filtrar asaplicaciones.
    * Reviews: Cantidad de reseñas que ha recibido cada una de las aplicaciones. Sirve para ordenar los datos 
  * ### Transformaciones
    * Estandarizar el atributo Size a Megas: Eliminar el caracter 'M' en las hileras que lo contengan, Agregar "0," a las hileras que contengan una 'k' al final y eliminar el caracter 'k' en las hileras que lo contienen.
    * Adaptar el formato de la columna instalaciones: Eliminar el caracter '+' al final de los registros y el caracter ',' para interpretar correctamente la cifra y especificar en el nombre del atributo que son más instalaciones que la cantidad del registro, es decir un minimo.