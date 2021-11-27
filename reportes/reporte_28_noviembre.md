### Reporte 28-11-2021
### Autor: Javier Abarca Jimenez
### Carné: B70018
 
## Resumen de los temas
## 1. Series de tiempo
Son secuencias de valores que representan una variable de interés, estos valores pueden pertenecer a un conjunto discreto (minutos, días, años) o continuo.
 
En algunos conjuntos de datos el atributo de interés depende del tiempo, por lo que uno de los objetivos es el de analizar la dependencia entre la variable de salida y los aspectos relacionados al tiempo de esta serie. Algunas tareas de interés son:
 * La identificación de patrones en las observaciones del pasado.
 * La capacidad de realizar predicciones informadas sobre periodos futuros.
 
Las series de tiempo se pueden aplicar en múltiples áreas como negocios, finanzas, medio ambiente y la industria. Algunos ejemplos de usos en estas:
 * Prever el precio de cierre de una acción cada día.
 * Prever las ventas diarias de un producto en una tienda.
 * Prever la tasa de desempleo en una región en un cuatrimestre.
 
## 1.1 Componentes de una serie de tiempo
* ### Tendencia:
    Describe el comportamiento promedio de la serie a medida que pasa el tiempo, puede ser incremental, decremental y estable.
 
* ### Temporalidad
    Son las fluctuaciones como las olas de frecuencia que se pueden observar en la serie.
 
* ### Ruido
    Es un tipo de fluctuación que representa variaciones irregulares existentes en los datos.
 
## 2. Stream processing
Consiste en computar los datos directamente cuando se recibieron o producieron y esta naturaleza de los datos tiene que ver con los siguientes dos aspectos:
 
### 2.1 Aspectos de los datos
A continuación se van a abordar algunas propiedades relacionadas con la naturaleza de los datos:
* Cardinalidad:
    * Bounded:
        * Tamano finito.
        * Posible almacenarla.
        * Procesamiento por batch.
    * Unbounded:
        * Tamano teoricamente infinito.
        * Sin inicio y fin definidos.
        * Registros pequeños, pero volumen alto.
        * Distribución inconsistente.
        * No sigue una secuencia.
 
* Constitucion:
    * Tablas:
        * SQL.
        * NoSQL.
        * Archivos.
        * Datos en reposo.
    * Streams:
        * Fluyen en el tiempo.
        * Datos en movimiento .
 
## 2.2 Batch vs Streaming (Propiedades)
|                  | Batch                                                                | Streaming                                                   |   |   |
|------------------|----------------------------------------------------------------------|-------------------------------------------------------------|---|---|
| Frecuencia       | Trabajo de poca frecuencia con resultados hasta terminar de ejecutar. | Jobs en constante ejecución con resultados de igual manera.  |   |   |
| Desempeño        | Alta latencia.                                                        | Baja latencia.                                               |   |   |
| Fuentes de datos | Base de datos, APIs y archivos.                                       | Colas de mensajes, streaming eventos y transacciones.        |   |   |
| Tipo de análisis | Complejo.                                                             | Simple.                                                      |   |   |
| Procesamiento    | Ocurre después de almacenar los datos.                                | Se procesan y después se decide si almacenar los resultados. |   |   |
 
 
 
## Comentarios
  * Esta técnica de stream processing permite tomar acciones de manera más directamente y este tiempo de respuesta dependiendo del escenario es de gran valor.
 
## Dudas
  * Por el momento no.
 
## Usos
  * En Internet de las cosas creo que es bastante útil y había trabajado con esta técnica durante un concurso de IoT.
 
## Material extra
  * Para este reporte no se utilizó material extra.