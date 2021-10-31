### Reporte 31-10-2021
### Autor: Javier Abarca Jimenez
### Carné: B70018
 
## Resumen de los temas
  * ## 1. Genetic algorithms
    * Genes y cromosomas
      Un gen está contenido en un cromosoma, este último se podría considerar como un conjunto de hiper parámetros para, por ejemplo, una red neuronal.
    * Población
      Es un grupo de ciertos individuos que poseen similitudes en su estructura o funcionamiento.
    * Crianza
      La producción de individuos a partir de miembros existentes, donde ambos aportan el mismo material genético, se denomina reproducción.
    * Mutación
      Es necesario para mantener la diversidad o la estocasticidad, entonces se hacen mutaciones aleatoriamente de los genes de los niños.
    * Fitness Score
      Mediante este puntaje se determina cual es el modelo, puede ser una red neuronal, más adecuada. Además, con este valor se puede calcular que tan probable es que evolucione uno de los individuos del modelo.
  * ## 2. Análisis de Asociación
    Consiste en estudiar atributos o características que suelen aparecer o ocurrir en conjunto, esto se logra mediante métodos que descubren o evidencian asociaciones entre atributos. Este concepto también es conocido como Análisis de afinidad, análisis de canasta de mercado o reglas de asociación. Algunos de los usos de este análisis:
      * Detección de fraudes.
      * Análisis de mercados y clientes.
      * Realizar ofertas con mejores resultados.
      * Manejo de inventarios.
  * ### 2.1 Reglas
    * Tienen la forma "Si a, entonces b".
    * En estas se definen dos propiedades, pueden ser una de respaldo y la otra de confianza, con un umbral o valor aceptable para cada una de estas.
  * ### 2.2 Dificultades
    La cantidad de reglas a encontrar es exponencial y el espacio de búsqueda también lo es, este crece dependiendo de la cantidad de productos por ejemplo.
  * ### 2.3 Generación de reglas
    * Encontrar todos los itemsets frecuentes
    * Generar reglas de asociación  que cumplan con las condiciones de respaldo y de confianza para los itemsets encontrados.
 
* ## Comentarios
  * La presentación de Análisis de Asociación tenía una estructura que ayudó bastante a asimilar bien la materia.
 
* ## Dudas
  * No tengo dudas en estos temas.
 
* ## Usos
  * Encontrar patrones probablemente difíciles de observar a simple vista a partir de datos generados en contextos con artículos o sucesos, cuya frecuencia es calculable o que al combinarlos generan un perfil.
 
* ## Material extra
  * Se utilizó este enlace [Hyperparameter Optimization With Genetic Algorithms In Kotlin](https://heartbeat.comet.ml/hyperparameter-optimization-with-genetic-algorithms-in-kotlin-75e9c5a1e5ab)