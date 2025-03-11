# AQI_Prediction_Model-

Índice de Calidad del Aire y Consumos Energéticos

Este proyecto tiene como objetivo analizar la relación entre el consumo energético per cápita y la calidad del aire (AQI) en distintos países. Para ello, desarrollamos un modelo de Machine Learning basado en Random Forest, capaz de predecir la categoría AQI a partir del mix energético y el PIB per cápita.

Tecnologías Utilizadas
- Python (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn)
- Machine Learning (Random Forest, Árboles de Decisión, Regresión Lineal Múltiple)
- Power BI (Visualización y análisis de datos)

Metodología
1.	Limpieza y preprocesamiento de datos: Filtrado, tratamineto de nulos y transformación de variables categóricas.
2.	Selección de características: Eliminación de colinealidad y variables redundantes mediante análisis de correlación y VIF.
3.	Entrenamiento y evaluación del modelo: Comparación entre Random Forest, Árbol de Decisión y Regresión Lineal.
4.	Interpretación de resultados: Evaluación de importancia de variables con Feature Importance.

Hallazgos Principales
-	Bajos consumos energéticos: Alta probabilidad de un AQI bajo, independiente del mix energético y del PIB.
-	Consumos medios/altos: El mix energético es clave; mantener el AQI en niveles aceptables requiere más de un 50% de energía renovable.
-	Consumos extremos: Solo un mix cercano al 100% de energías renovables permite mantener un AQI moderado.
-	PIB y mitigación: Los países con mayor PIB tienen más capacidad para mitigar la contaminación gracias a inversión en tecnologías limpias.

Futuras Mejoras
-	Ampliar el dataset con datos de más países, especialmente en África, Oceanía y América del Sur.
-	Explorar modelos más avanzados, como XGBoost o Redes Neuronales.
-	Integrar predicciones del mix energético óptimo para cumplir objetivos de calidad del aire descrito en la Agenda 2030.

Agradecimientos

Este proyecto fue desarrollado en el Bootcamp de Data Analytics en Neoland, con la guía de Nacho y Cris, y el esfuerzo de todo el equipo.

¡Cualquier sugerencia o feedback es bienvenido!
