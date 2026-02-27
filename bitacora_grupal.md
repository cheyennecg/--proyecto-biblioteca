# 📓 La Bitácora Dinámica de Préstamos

Este documento es el **diario de grupal**. Aquí hemos documentado, paso a paso, cómo organizamos todo el proyecto: las decisiones que tomamos, las ideas que surgieron y la forma en que trabajamos juntos para construir esta informe.

Además de la organización, esta bitácora es un **espacio honesto** para contar las dificultades que enfrentamos y cómo las superamos. 

---
## 🗓️ Día 1 - Limpieza de datos (orden, fechas, días)

### Inicio del análisis
1. **Carga de datos**: Subimos el archivo `prestamos_biblioteca_publica.csv` a Google Sheets, manteniendo los datos originales.
2. **Duplicado de seguridad**: Duplicamos el documento para trabajar sin riesgo de perder información.
3. **Trabajo colaborativo**: Compartimos el archivo con todo el equipo y cada miembro hizo su propia hoja para experimentar y anotar su visiones.

### Entendiendo la estructura
Revisamos a fondo la tabla para identificar:
* Las columnas y su significado.
* El tipo de datos (números, fechas, categorías...).
* Cantidad total de registros y posibles errores.
* **Orden lógico**: Vimos que la columna `fecha_prestamo` estaba desordenada; la organizamos para permitir el análisis.

### Preguntas clave de investigación
Definimos los pilares de nuestro análisis:
* **Categoría**: ¿Qué género e idioma destacan? ¿Volumen anual de préstamos?
* **Idiomas**: Porcentaje de préstamos por idioma.
* **Actividad temporal**: En que meses, franjas horarias (mañana/tarde) y días de la semana se prestan más libros. 
¿Existen patrones estacionales?¿Y de horarios y días?
* **Duración y devoluciones**: Porcentaje de libros entregados fuera de plazo, tiempos de devolución por categoría y descuadres.



## 🗓️ Día 2 - Preparación y Estructuración de Datos

### Creación de tablas 
Gracias a la organización de **Oksana**, aprendimos a estructurar la tabla de manera individual con filtros y nuevas columnas sin alterar el orden de fechas. Este paso fue vital para entender la importancia de una "tabla limpia". 

Pasamos de "mirar la tabla" a buscar respuestas concretas mediante la creación de nuestras primeras tablas dinámicas.

> **Obstáculos**: El mayor reto fue entender el valor de una tabla bien organizada como paso previo a las tablas dinámicas. También comprendimos con ensayo y error que la tabla no podía tener modificación cada vez que queriamos crear una tabla dínamica, sino que, tendríamos que "jugar" con la configuración de la misma para viualizar bien los datos. La falta de experiencia previa con Google Sheets/Excel hizo que este concepto fuera un gran aprendizaje.


## 🗓️ Día 3 - Visualización de Datos y Análisis  

### Creación de tablas diámicas
Bajo la guía y paciencia de Oksana a la hora de aprender, ya que ella sabía hacerlas, nos pusimos a crear y ver cómo creaban otros compañeros las tablas dinámicas aprendiendo así de una manera proactiva y dinámica.
 
Partiendo de dichas tablas, incluidas las que Oksana ya había preparado el día anterior, seleccionamos las más relevantes y empezamos a crear las gráficas que iban a dar respuesta a nuestras preguntas.

### Proceso de diseño de las Gráficas

1. **Creación de gráficas**: Probamos diversos formatos visuales hasta hallar los que mejor comunicaban los patrones que habíamos observado.
2. **Creación de leyenda**: Complementamos cada gráfica con una leyenda con conclusiones concisas y reflexiones sobre los hallazgos.


> **Obstáculos**: La dificultad principal fue entender el funcionamiento de las tablas dinámicas y comor organizar dichos datos para posteriormente elegir el estilo de gráfico adecuado y decidir qué datos en los elementos (ejes, series) incluir o suprimir para no saturar la información.




## 🗓️ Día 4 - Informe del análisis

Nos enfocamos en transformar los análisis individuales en un **informe claro y conciso.**  

### Perfeccionamiento visual
* Ajustamos colores y formatos para garantizar visualizaciones impactantes.
* Cada hoja se estructuró con: **Tabla dinámica + Gráfico + Leyenda**.

### Aprendizaje colaborativo
Este día nos dimos cuenta que no sólo podíamos organizar la tabla a través de filtros como nos enseño **Oksana** sino con funciones específicas que fuimos buscando colaborativamente.
En este punto, nos tomamos un respiro en la creación de gráficas y volvimos a practicar el "limpiar" una tabla descubriendo que existen varios caminos.  

Aprendimos funciones cómo:
* MONTH , WEEKDAY, CONCAT.
 
> **Obstáculos**: Lograr una estructura impecable en cada hoja e insertar y redactar leyendas que fueran claras y profesionales.

---

## 🗓️ Día 5 - Revisión y entrega final

Día de consolidación y pulido de los detalles finales.

### Puntos clave del cierre:
* **Refinamiento**: Unificamos la estética de cada hoja. 
* **Ensayos**: Realizamos prácticas de la presentación para eliminar redundancias y hacer el mensaje más efectivo.
* **GitHub**: Establecimos un repositorio colaborativo para una gestión eficiente de documentos.
* **Insights** : Documentamos los hallazgos significativos, patrones y tendencias clave extraídos de los datos.


 
## 📝 Qué hallazgos nos llamaron la atención sus conclusiones 

### Conclusiones Generales 

✅ *Preferencias de los Lectores*  

El análisis de los préstamos realizados permite identificar patrones claros en los hábitos de lectura de los usuarios:

* **Idioma**: Tras el castellano, el catalán se posiciona como el segundo idioma más leído, lo que refleja una presencia significativa de demanda en esta lengua y justifica mantener una oferta equilibrada en ambos idiomas.  

* **Géneros más demandados**:
La ficción se consolida como el género más popular, concentrando la mayor parte de los préstamos.  
Le sigue el género infantil, lo que sugiere una fuerte participación del público joven o de familias que utilizan activamente el servicio.

* **Géneros menos solicitados**:
El género lírico y la divulgación presentan los niveles más bajos de demanda.
Especialmente relevante es el caso del género lírico, que representa un porcentaje mínimo del total de préstamos.  

---

✅ *Periodos de Actividad*  

El comportamiento temporal de los préstamos muestra una marcada estacionalidad:
* **Distribución diaria**:
Las tardes registran mayor actividad que las mañanas, lo que puede estar relacionado con la disponibilidad horaria de los usuarios tras la jornada laboral o escolar.
* **Distribución estacional**:  
La primavera es la temporada con mayor volumen de préstamos.
Marzo y mayo destacan como los meses de mejor desempeño anual.
El verano, en cambio, presenta el nivel más bajo de actividad, siendo julio y agosto los meses con menos solicitudes.
Relación con el calendario escolar:
Las tendencias observadas coinciden claramente con el calendario académico, lo que refuerza la hipótesis de que una parte significativa de los usuarios está vinculada al entorno educativo.

✅ *Periodos de tiempos* 

El análisis del tiempo de préstamo y la puntualidad en las devoluciones muestra resultados mayoritariamente positivos
* **Duración de los Préstamos y Cumplimiento de Plazos**:  
La duración media es 14 días, lo que indica un uso ajustado al periodo estándar establecido.   
El 94,25% de los libros se devuelven dentro del plazo, reflejando un alto nivel de responsabilidad por parte de los usuarios.  
* **Análisis por género**:  
*La ficción* representa el 39,46% del total de préstamos, consolidándose como el género predominante.  
Presenta una tasa de devolución puntual del 94,17%, alineada con la media general.  
 *El género lírico* supone únicamente el 1,15% del total de préstamos, lo que confirma su baja demanda. Sin embargo, destaca negativamente en términos de puntualidad, con solo un 33,04% de devoluciones dentro del plazo, muy por debajo de la media.  
Este contraste sugiere que, aunque el género lírico tiene una baja rotación, podría requerir medidas específicas de seguimiento o revisión de plazos, ya que concentra proporcionalmente más retrasos.

### Conclusión Global
El servicio presenta un comportamiento sólido y estable, con altos niveles de cumplimiento en las devoluciones y una clara concentración de la demanda en ficción e infantil. La estacionalidad está fuertemente vinculada al calendario escolar, lo que permite anticipar ciclos de mayor y menor actividad.  
Como líneas estratégicas futuras se podrían considerar:
* **Reforzar** la oferta y actividades en los géneros más demandados.  
* **Diseñar** acciones de promoción para dinamizar los géneros menos solicitados.
* **Implementar** medidas de seguimiento específico para los préstamos del género lírico.
* **Aprovechar** los periodos de menor actividad (verano) para campañas de captación o actividades culturales.  

En conjunto, los datos muestran un servicio eficiente, con oportunidades claras de optimización basadas en patrones identificables y consistentes.
