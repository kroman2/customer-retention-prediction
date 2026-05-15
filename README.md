# Customer Retention Prediction

## Descripción
Este proyecto tiene como objetivo predecir si un cliente regresará o no a una plataforma de comercio electrónico, utilizando técnicas básicas de ciencia de datos y modelos de clasificación.

## Dataset
El conjunto de datos incluye información de clientes como:
- Edad
- Gasto
- Interacción con marketing
- Género

Estas variables permiten analizar el comportamiento de compra y su relación con el retorno del cliente.

## Proceso

El proyecto se desarrolló siguiendo las etapas principales de ciencia de datos:

1. Exploración de datos  
   - Revisión de estructura, tipos de datos y estadísticas descriptivas  

2. Visualización  
   - Análisis de distribución de variables como edad, gasto y género  

3. Preprocesamiento  
   - Codificación de variables categóricas  
   - Escalado de variables numéricas  

4. Modelado  
   - Logistic Regression  
   - Decision Tree  
   - Random Forest  

5. Evaluación  
   - Comparación de modelos mediante precisión  
   - Selección del mejor modelo  

6. Optimización  
   - Ajuste de hiperparámetros con GridSearchCV  

## Resultados

El modelo de regresión logística fue seleccionado como el más adecuado, obteniendo una precisión del 100% en el conjunto de prueba.

La matriz de confusión mostró que el modelo clasifica correctamente todos los casos, sin errores de predicción.

## Conclusión

El modelo permite identificar clientes con baja probabilidad de retorno, lo cual puede ser utilizado para implementar estrategias de retención como promociones personalizadas o campañas de seguimiento.

Sin embargo, debido al tamaño y simplicidad del conjunto de datos, los resultados no garantizan el mismo desempeño en escenarios reales más complejos.

## Tecnologías utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  

