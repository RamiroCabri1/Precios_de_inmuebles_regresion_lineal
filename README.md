Proyecto de Análisis y Modelado de Datos Inmobiliarios
Descripción del Proyecto
Este proyecto fue desarrollado como parte del bootcamp de Data Science ofrecido por Alura Latam en colaboración con Oracle. El objetivo principal es aplicar técnicas de análisis exploratorio de datos (EDA), preprocesamiento, y modelado predictivo a un dataset de valores inmobiliarios.

El proyecto se centra en la limpieza y el análisis de datos para identificar factores clave que influyen en los precios de las propiedades, culminando en la creación de un modelo predictivo robusto.

Autor
Cabri Ramiro

Herramientas y Librerías Utilizadas
El análisis se llevó a cabo en un entorno de Google Colab, aprovechando la flexibilidad y las capacidades colaborativas de la plataforma. Las siguientes librerías de Python, fundamentales en el ecosistema de Data Science, fueron utilizadas:

Pandas: Para la manipulación y el análisis de datos.

NumPy: Para operaciones numéricas eficientes.

Matplotlib y Seaborn: Para la visualización de datos y la creación de gráficos informativos.

Scikit-learn: Para el preprocesamiento de datos y la construcción de modelos de Machine Learning.

Plotly Express: Para la creación de visualizaciones interactivas.

statsmodels: Para el análisis estadístico y la evaluación de modelos.

Metodología
La estructura del proyecto sigue un flujo de trabajo estándar en ciencia de datos:

Análisis Exploratorio de Datos (EDA): Se examinaron las características del dataset, se identificaron distribuciones y se detectaron relaciones entre las variables.

Preprocesamiento de Datos: Se manejaron valores nulos, se corrigieron tipos de datos y se aplicaron transformaciones como el aplanamiento de diccionarios anidados para preparar el dataset para el modelado.

Análisis de Multicolinealidad: Se utilizó el Factor de Inflación de Varianza (VIF) para identificar y gestionar la redundancia entre variables explicativas, garantizando la estabilidad del modelo.

Modelado Predictivo: Se construyó un modelo de regresión lineal para predecir los valores de las propiedades y se evaluó su rendimiento utilizando gráficos de dispersión de residuos.

Visualizaciones Clave
A lo largo del proyecto, se generaron diversas visualizaciones para entender mejor los datos, incluyendo:

Gráficos de histograma para analizar la distribución de variables numéricas.

Diagramas de caja (boxplots) para identificar la dispersión y los valores atípicos.

Gráficos de barras para comparar métricas entre diferentes categorías.

Mapas de calor (heatmaps) para visualizar la matriz de correlación.

Gráficos de residuos para evaluar el rendimiento del modelo.

Conclusiones
El proyecto permitió extraer insights valiosos sobre los factores que inciden en el valor de las propiedades. El modelo predictivo desarrollado, aunque demuestra un buen rendimiento general, presenta áreas de mejora, especialmente en la predicción de valores extremos, lo cual fue identificado a través del análisis de residuos.
