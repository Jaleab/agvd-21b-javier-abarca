### Reporte Tarea 1
### Autor: Javier Abarca Jimenez 
### Carné: B70018
 
* ## Dataset elegido
    * Google Play Store Apps: https://www.kaggle.com/lava18/google-play-store-apps
 
* ## Preguntas de investigación
    * ¿Cuál es la categoría de aplicaciones con mayor cantidad de instalaciones?
    * ¿Cuáles son las aplicaciones con mayor cantidad de reseñas?
    * Cual es la aplicación con categoría "COMICS"  con la mayor cantidad de reseñas?
* ## OpenRefine
  * ### Problemas identificados
    * El formato del atributo instalaciones y price no es apto para tratarlo como numérico.
      * Corrección: Eliminar el carácter '+', eliminar las ',' y especificar en el nombre del atributo que son más instalaciones que la cantidad del registro (es un mínimo). En el caso de price, eliminar el carácter '\$' y cambiar el nombre del atributo a "Price ($)"
    * Existen valores numéricos en columnas categóricas (Category), valores no numéricos en columnas numéricas (Reviews), entre otros problemas similares.
      * Corrección: Realizar facets para poder editar estos registros a valores como (NaN, Not defined). En el caso de una fila con varios registros con valores no útiles, eliminarlo.
    * Los registros del atributo Size no son numéricos y no tienen una unidad estándar.
      * Corrección: Nombrar la columna "Size" cómo "Size (M)", eliminar las M de los registros y pasar los convertir los valores que están en kilos (k) a Mega (M).
  * ### Atributos importantes
    * Installs: Cantidad mínima de instalaciones de cada una de las aplicaciones. Sirve para ordenar los datos y poder responder algunas de las preguntas de investigación. 
    * Category: Categoría de cada una de las aplicaciones. Sirve para agrupar y para filtrar las aplicaciones.
    * Reviews: Cantidad de reseñas que ha recibido cada una de las aplicaciones. Sirve para ordenar los datos 
  * ### Transformaciones
    * Estandarizar el atributo Size a Megas: Eliminar el carácter 'M' en las hileras que lo contengan, Agregar "0," a las hileras que contengan una 'k' al final y eliminar el carácter 'k' en las hileras que lo contienen.
    * Adaptar el formato de la columna instalaciones: Eliminar el carácter '+' al final de los registros y el carácter ',' para interpretar correctamente la cifra y especificar en el nombre del atributo que son más instalaciones que la cantidad del registro, es decir un mínimo.