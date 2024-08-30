 # Análisis de Comportamiento de Usuarios en Trash to Treasure


## Definir el Objetivo

**Objetivo:** Analizar el comportamiento de los usuarios en la aplicación móvil Trash to Treasure para identificar patrones y determinar qué usuarios podrían abandonar la aplicación.

A continuacion el plan de accion :

##  Plan de Acción

1. **Carga de Datos e Importacion de librerias** 
    - importar librerias
    - carga de datasets 


2. **Preprocesamiento de Datos:**
   - Estudiar valores ausentes.
   - Estudiar el tipo de correspondencia.
   - Estudiar valores duplicados.
   - Comprobar la exactitud de los nombres de columnas.
   - Renombrar las columnas.
   - Eliminar duplicados.
   - Convertir tipos.
   - Reemplazar valores ausentes.

3. **Análisis Exploratorio de Datos (EDA):**
   - Describir los datos: medias, medianas, desviaciones estándar.
   - Visualizar la distribución de los eventos.
   - Analizar la frecuencia de los eventos por usuario.
   - Analizar el tiempo dedicado a la aplicación por usuario.
   - Calcular la tasa de retención de usuarios.
   - Identificar patrones en la conversión de `contacts_show`.
   
3. **Segmentación de Usuarios:**
    - Utilizar técnicas de clustering ( k-means ) para segmentar a los usuarios en función de los eventos que completan.
   - Evaluar la calidad de los clusters obtenidos.
   - Asignar etiquetas a los segmentos de usuarios.

4. **Análisis de Métricas del Producto:**
   - Calcular y comparar la tasa de retención entre los segmentos.
   - Calcular y comparar el tiempo dedicado a la aplicación entre los segmentos.
   - Calcular y comparar la frecuencia de ocurrencia de eventos entre los segmentos.
   - Calcular y comparar la conversión en `contacts_show` entre los segmentos.

5. **Prueba de Hipótesis Estadísticas:**
   - **Hipótesis sobre la conversión en `contacts_show` entre `bing` y `google`:**
     - Formular la hipótesis nula y alternativa.
     - Realizar la prueba estadística adecuada.
   
   - **Otra hipótesis estadística:**
     - Formular una hipótesis basada en un patrón observado en los datos.
     - Realizar la prueba estadística adecuada para validar la hipótesis.

6. **Conclusiones y Recomendaciones:**
   - Resumir los hallazgos principales del análisis.
   - Proporcionar recomendaciones para la estrategia de retención y optimización del producto.
   - Sugerir acciones basadas en los segmentos de usuarios identificados.
