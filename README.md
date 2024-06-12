Este repositorio contiene el código desarrollado como parte del Trabajo de Fin de Máster (TFM) que aborda la predicción de la producción de energía eólica en el mercado eléctrico utilizando técnicas avanzadas de aprendizaje automático.

El objetivo principal de este proyecto es examinar y comparar diversos modelos de predicción de series temporales aplicados a un conjunto de datos de un parque eólico. Este conjunto de datos incluye información sobre la producción de energía y datos de predicciones meteorológicas.

Tras haber preprocesado los datos con el cuaderno data_preprocessing.ipynb para así obtener los datos limpios y ordenados: datos_TFM_Celia.csv, se han implementado diferentes modelos sobre el mismo conjunto de datos con el objetivo de comparar los errores obtenidos sobre el conjunto de prueba. Se comparan los errores MAE y RMSE. Cada modelo se ha  implementado en un cuaderno diferente: ARIMA.ipynb, MLP.ipynb, LSTM.ipynb, GRU.ipynb y xgboost.ipynb.

Los resultados muestran la superioridad de modelos que logran capturar la relación con la energía producida en los últimos instantes disponibles de histórico y con las predicciones meteorológicas, pero con arquitecturas simples que evitan la complejidad innecesaria (MLP y GBM). 

Se destaca la importancia de tener predicciones precisas para evitar desvíos en el mercado eléctrico con un análisis económico (en otro cuaderno .ipynb). Las conclusiones de este TFM resaltan la relevancia de estas técnicas de predicción no solo para mejorar la precisión de las predicciones, sino también para apoyar la transición hacia un sistema energético más limpio y eficiente.


