Loan Prediction en pyspark con 8 modelos

Github: adolfogutcampos

Linkedin: www.linkedin.com/in/adolfo-gutiérrez-campos-91a595131

# ⚡ 0.- Introducción

El objetivo de este proyecto es demostrar el uso de PySpark junto con 8 modelos de Machine Learning y Deep Learning para predecir la aprobación de préstamos. El proyecto incluirá los siguientes pasos:

- 1- Extracción de datos: Recopilación de datos relacionados con la aprobación de préstamos, incluyendo características tales como ingresos, puntuación de crédito, importe del préstamo y estado del préstamo.

- 2- Análisis de datos: Tras un análisis de datos, se ha realizado matriz de correlaciones y Operaciones de SQL.

- 3- Limpieza y preaparación de datos: Garantizar que el conjunto de datos esté listo para su uso en algoritmos de Machine Learning y Deep Learning.

- 4- Ingeniería de funciones o caracteríssticas (Features): Selección e ingeniería de características relevantes para mejorar la precisión del modelo.

- 5- Elaboración de los 8 modelos: Estos modelos se van a entrenar y evaluar con el fin de generar predicciones de si un préstamos será aprobado o no basándose en las características de entrada o inputs.

El resultado final será una comparación de los indicadores de los 8 modelos de que puede predecir con precisión la aprobación de préstamos basándose en varias características. 
El proyecto puede ampliarse explorando diferentes algoritmos y mejorando la precisión de modelos.

El conjunto de datos se puede descargar del siguiente enlace:

https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset

# 🏗 1.- Modelos para predicción de viabilidad de préstamos

Construcción y evaluación de 8 modelos diferentes para la predicción de viabilidad de préstamos:

- 📈 Modelo 1: Logistic Regression (Machine Learning)

- 🌳 Modelo 2: Random Forest (Machine Learning)

- 🚀 Modelo 3: Gradient Boosting (Machine Learning)

- 🔥 Modelo 4: XGBoost (Machine Learning)

- 🧠 Modelo 5: Redes Neuronales Artificiales (ANN) (Deep Learning)

- 🌌 Modelo 6: Redes Neuronales Profundas (DNN) (Deep Learning)

- 📜 Modelo 7: Redes Neuronales Recurrentes (RNN) (Deep Learning)

- 🌐 Modelo 8: Redes Neuronales Convolucionales (CNN) (Deep Learning)

Tras haber elaborado los modelos, se ha identificado opciones de mejora para obtener mejores resultados en sus indicadores mediante:

- Ajuste de Hiperparámetros

- Ajuste de modelos adicionales como LightGBM o CatBoost, que son variaciones de Gradient Boosting y podrían ofrecer mejoras adicionales.

- Implementación de Modelos Ensamblados (Ensemble)

- Incorporación de Características Derivadas (Feature Engineering)

# 📊 2.- Comparación de modelos

| Modelo                             | AUC      | Exactitud (Accuracy) | Sensibilidad (Recall) | Precisión (Precision) | F1 Score | Coeficiente de Gini |
|------------------------------------|----------|----------------------|-----------------------|-----------------------|----------|---------------------|
| Modelo 1: Regresión Logística      | 0.787302 | 0.835052             | 0.835052              | 0.865740              | 0.808784 | 0.574603            |
| Modelo 2: Random Forest            | 0.817460 | 0.824742             | 0.824742              | 0.823080              | 0.808709 | 0.634921            |
| Modelo 3: Gradient Boosting        | 0.833333 | 0.793814             | 0.793814              | 0.793814              | 0.793814 | 0.666667            |
| Modelo 4: XGBoost                  | 0.813228 | 0.824742             | 0.928571              | 0.844156              | 0.884354 | 0.626455            |
| Modelo 5: ANN                      | 0.683598 | 0.773196             | 0.857143              | 0.833333              | 0.845070 | 0.367196            |
| Modelo 6: DNN                      | 0.625926 | 0.731959             | 0.842857              | 0.797297              | 0.819444 | 0.251852            |
| Modelo 7: RNN                      | 0.720635 | 0.793814             | 0.900000              | 0.828947              | 0.863014 | 0.441270            |
| Modelo 8: CNN                      | 0.719048 | 0.742268             | 0.828571              | 0.816901              | 0.822695 | 0.438095            |

