### Para la entrega de Momento de Retroalimentación: Módulo 2 Implementación de una técnica de aprendizaje máquina sin el uso de un framework. (Portafolio Implementación), se requiere revisar el archivo de Port_Imple_WOFRAMEWORK_A01571214_Lautaro_Coteja.ipynb y/o Port_Imple_WOFRAMEWORK_A01571214_Lautaro_Coteja.pdf.

#### Cambios Implementados en Port_Imple_WOFRAMEWORK_A01571214_Lautaro_Coteja para la entrega de Momento de Retroalimentación: Módulo 2 Implementación de una técnica de aprendizaje máquina sin el uso de un framework. (Portafolio Implementación):
##### El modelo implementado corresponde a un modelo adecuado para los Challenge indicados:
El modelo original implementaba una regresión lineal, cuando debía ser una regresión logística para ajustarse a los requisitos del Challenge. Se modificó el modelo a una **regresión logística** implementada manualmente, utilizando la función sigmoide para predecir las probabilidades de las clases.

##### Selección de valores para la tasa de aprendizaje y parámetros iniciales:
Se indicó que no se mencionaba el criterio utilizado para seleccionar la tasa de aprendizaje y los parámetros iniciales. Para solucionar esto, se agrego una explicacion en el documento ipynb y el pdf.

##### Implementación correcta del modelo:
El modelo fue corregido para utilizar **regresión logística** en lugar de regresión lineal, garantizando que se ajuste correctamente a los requerimientos del Challenge. El algoritmo de descenso de gradiente se utiliza para minimizar la función de costo log-loss, adecuada para este tipo de problemas de clasificación binaria.

##### Gráfica de predicciones vs datos reales (subset de prueba):
Se agregó la gráfica que compara las predicciones del modelo con los datos reales del conjunto de prueba. Ahora se incluye la línea de predicciones del modelo (`Model prediction`), que muestra las probabilidades estimadas por la regresión logística.

##### Cálculo correcto de la función de costo:
El cálculo de la función de costo fue corregido para utilizar **log-loss**, que es la función de costo adecuada para problemas de clasificación binaria. Anteriormente se estaba utilizando la función de costo de regresión lineal, lo cual no era correcto para este caso.

