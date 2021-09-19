### Reporte 19-09-2021
### Autor:  Javier Abarca Jimenez 
### Carné: B70018
 
* ## Resumen de los temas
    * Transformación de datos
        * Dataset : Es una colección de objetos o datos. También dependiendo del contexto de trabajo se les puede referir como una colección de registros, de puntos de observación,entre otros. Se describen a través de atributos (columnas, campos, variables, dimensión).
        * Tipos de atributos
            *   Según el tipo de datos se le da un abordaje distinto. Estos tipos son los siguientes:
                * Categoricas
                    * Análisis cualitativa
                        * Nominal: Nombres, sustantivos
                        * Ordinal: Establecen un orden      
                * Numericos
                    * Análisis cuantitativo
                        * Intervalos de valores: Proporciones
    * Tipos de conjuntos de datos
        * Record data: Es el más común, estos incluyen los que son de personas.
        * Basados en grafos: Relaciones entre objetos, por ejemplo si se realiza una araña en páginas web.
        * Datos ordenados: Colecciones de datos de transacciones (temporal), secuencias de AND (secuencial), el valor de acciones, precipitación (espacial).
        * Características generales:
            * Dimensionalidad: Número de columnas.
            * Dispersión: Hay valores más presentes en comparación a otros.
            * Resolución: Precisión o profundidad de los valores en los registro.
    * Trabajos
      * Agregación: Combinar dos o más objetos (suma, promedio, entre otras operaciones).
      * Muestreo: Seleccionar un subconjunto. Esto es útil cuando el conjunto es extremadamente grande o no nos interesa trabajar con todos los datos. Es costoso obtener y procesar todo el conjunto. Existen los siguientes tipos:
        * Aleatoria: Evita que las muestras estén sesgadas. Puede ser sin reemplazo (no se mantiene la probabilidad )o con reemplazo (se mantiene la probabilidad)
        * Estratificado: Población con muchos tipos de objetos y distinto número de objetos entre los tipos. Existe alta asimetría en los datos y por esto el muestreo aleatorio no es adecuado. Hay varias formas, dos de estas son las siguientes:
            * Igual cantidad de objetos de cada grupo
            * Cantidad de objetos proporcional al tamaño del grupo
        * Progresivo: Adaptativo, inicia con una muestra pequeña e itera hasta llegar a un tamaño que ya sea bueno para trabajar
    * Selección de atributos
        * Weighting: Asignar peso según importancia del atributo.
        * Embedded: Algoritmo de análisis toma las decisiones.
        * Filter: Antes del algoritmo, una decisión como eliminar atributos con la mejor correlación.
        * Wrapper: Utiliza el mismo algoritmo para encontrar la mejor respuesta del modelo propio.
    * Binarización: Transformación de atributos continuos y discretos en binarios. 
        * Asimétricos: Ampliación de atributos, a partir de los valores categóricos se generan valores numéricos.
    * Discretización: Transformación de atributos continuos en categóricos.
    * Normalización: Alinear los datos que están en escalas distintas, un tipo común de normalización es min-max. No sirve bien con datos anómalos.
    * Estandarización: Transformar variables con una distribución normal, crea una variable con media 0 y desviación estándar 1. Sirve mejor que la normalización con datos anómalos.
 
* ## Comentarios
  * La teoría cubierta durante estas dos semanas sirvieron para aclarar la materia, ya que habían conceptos que no se habían profundizado.
 
* ## Dudas
  * No tengo dudas en estos temas.
  
* ## Usos
  * Poder comprender y manejar conjuntos de datos con mayor facilidad.
 
* ## Material extra 
  * No se utilizó material extra.
