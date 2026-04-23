# prediccion-precios-vivienda-ml
🏠 Predicción de precios de viviendas con redes neuronales y modelos de Machine Learning

Este proyecto tiene como objetivo predecir el precio de viviendas utilizando diferentes modelos de Machine Learning y comparar su rendimiento.

📊 Contenido del proyecto
Análisis exploratorio de datos (EDA)
Limpieza y preparación de datos
Transformación de variables (dummies y estandarización)
Selección de variables (AIC, BIC, RFE, Boruta, etc.)
Implementación de modelos predictivos
Evaluación mediante validación cruzada

🤖 Modelos utilizados
Regresión lineal
Random Forest
Gradient Boosting Machine (GBM)
XGBoost
Redes neuronales

📈 Resultados principales
Las variables más importantes para predecir el precio fueron:
Tamaño de la vivienda (livingArea)
Valor del terreno (landValue)
Número de baños (bathrooms)
Número de habitaciones (rooms)
Los modelos de regresión lineal con selección de variables (AIC/BIC) obtuvieron el mejor rendimiento.
Modelos más complejos como redes neuronales y boosting no mejoraron significativamente los resultados.

🧠 Conclusiones

Los resultados muestran que la relación entre las variables es principalmente lineal, por lo que modelos simples como la regresión lineal pueden ser suficientes para este tipo de problema.
