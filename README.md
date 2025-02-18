# Detección_Cáncer_de_mama
1) Preprocesamiento y selección de características: Realicé un análisis exploratorio de datos (EDA), evaluando correlaciones, pairplots y métricas como solapamiento de distribuciones, correlación con la variable objetivo y no separabilidad. Eliminé características redundantes o poco informativas para mejorar el rendimiento del modelo.

2) Normalización: Aplicación de escalado estandarizado y validación cruzada para optimizar el número de folds y determinar el test size óptimo, garantizando una mejor generalización.

3) Optimización de hiperparámetros: Implementé GridSearchCV para ajustar hiperparámetros del modelo Support Vector Machine (SVM), maximizando su desempeño.

4) Evaluación del modelo: Alcancé una precisión del 98.68%, con una matriz de confusión bien balanceada y métricas de desempeño como F1-score y recall cercanos a 1, asegurando una alta capacidad de detección de casos positivos.
