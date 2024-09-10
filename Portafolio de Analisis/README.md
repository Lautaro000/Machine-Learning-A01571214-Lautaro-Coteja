## --------------------FAVOR DE LEER--------------------
### Para la entrega de Momento de Retroalimentación: Módulo 2 Análisis y Reporte sobre el desempeño del modelo. (Portafolio Análisis), se requiere revisar el archivo de MR_M2_Port_Analisis_Desempeño_Del_Modelo_A01571214_Lautaro_Coteja.pdf y/o MR_M2_Port_Analisis_Desempeño_Del_Modelo_A01571214_Lautaro_Coteja.ipynb.
### Para la entrega de Momento de Retroalimentación: Reto Análisis del contexto y la normatividad. (Portafolio Análisis), se requiere revisar el archivo de MR_Reto_Analisis_del_Contexto_y_la_Normatividad_Portafolio_Analisis_A01571214_Lautaro_Coteja.pdf.

#### Cambios Implementados en MR_M2_Port_Analisis_Desempeño_Del_Modelo_A01571214_Lautaro_Coteja para la entrega de Momento de Retroalimentación: Módulo 2 Análisis y Reporte sobre el desempeño del modelo. (Portafolio Análisis):
##### Explicación del tipo de ajuste obtenido y comparación entre modelos:
Se indicó que no se incluyó una explicación sobre el tipo de ajuste para los diferentes modelos entrenados con distintas cantidades de muestras. Para solucionar esto, se agregó una sección explicando cómo el primer modelo entrenado con 2 muestras tiene un ajuste deficiente debido a la falta de datos, mientras que el modelo final, entrenado con 40 muestras, presenta un mejor ajuste, reduciendo el error de predicción a medida que se incrementan las muestras.

##### Análisis de sesgo y varianza en los modelos:
Se señaló que no se realizó un análisis del sesgo y varianza de los modelos. En respuesta a esta observación, se incluyó un análisis detallado sobre el impacto del sesgo y la varianza en los modelos, explicando cómo la cantidad de datos afecta ambos factores. Este análisis está respaldado por los resultados obtenidos en los experimentos de entrenamiento.

##### Identificación de la cantidad óptima de muestras para entrenamiento:
Se indicó que no se identificó la cantidad adecuada de muestras para el entrenamiento. Se analizó la evolución del error cuadrático medio (MSE) con diferentes tamaños de muestras, identificando que la cantidad óptima de muestras para el entrenamiento se encuentra entre 30 y 35. Esta selección se justifica con base en la estabilización del MSE en el conjunto de validación.

##### Entrenamiento de un nuevo modelo con la cantidad de muestras seleccionada:
Se comentó que no se entrenó un nuevo modelo con la cantidad óptima de muestras. Para corregir esto, se entrenó un nuevo modelo utilizando 35 muestras, y se calcularon los errores cuadráticos medios (MSE) en los conjuntos de entrenamiento, validación y prueba, demostrando una mejora en el rendimiento del modelo.

##### Comparación de los errores del modelo final contra el modelo base:
Finalmente, se mencionó que no se compararon los errores del modelo final contra el modelo base. Se compararon los errores del modelo final con el modelo base, destacando que el modelo final tiene un mejor rendimiento en todos los conjuntos de datos (entrenamiento, validación y prueba), lo que indica una configuración superior para la predicción.

#### Cambios Implementados en MR_Reto_Analisis_del_Contexto_y_la_Normatividad_Portafolio_Analisis_A01571214_Lautaro_Coteja.pdf para la entrega de Momento de Retroalimentación: Reto Análisis del contexto y la normatividad. (Portafolio Análisis):
##### Especificacion de donde se encuentra el archivo
Se indico que no habia ninguna entrega que se pudiera identificar por lo que no se podia dar feedback, por lo que se actualizo este README.md y el nombre del archivo para que se vea especificamente bien donde esta el archivo a revisar.
