# Análisis de Factores que Influyen en los Tiempos de Entrega y su Predicción
Este proyecto tiene como objetivo analizar y predecir los tiempos de entrega de un sistema logístico utilizando datos históricos de rutas, tiempos de viaje y características operacionales. A través del análisis, buscamos identificar los principales factores que afectan los tiempos de entrega y desarrollar un modelo predictivo para mejorar la eficiencia operativa.

## Tecnologías y Herramientas Utilizadas
- Python: Lenguaje principal para el análisis y modelado de datos.
- Pandas: Para la manipulación y análisis de datos.
- NumPy: Para operaciones numéricas.
- Matplotlib y Seaborn: Para la visualización de datos.
- Scikit-learn: Para la preprocesamiento de datos y modelado.
- LabelEncoder: Para la codificación de variables categóricas.

## Descripción del Análisis
 1. Exploración de Datos (EDA)
  - Inspección y limpieza de datos.
  - Identificación de valores atípicos y su eliminación mediante el método IQR.
  - Conversión de variables de tiempo (fechas y horas) para extraer características adicionales, como hora, día y mes de creación del viaje.
2. Codificación de Variables Categóricas
  - Se utilizaron técnicas de codificación de etiquetas (Label Encoding) para convertir las variables categóricas en valores numéricos, permitiendo su uso en modelos predictivos.
3. Análisis de Factores
  - Se formularon y probaron tres hipótesis clave:
    - La relación entre la distancia y el tiempo de entrega.
    - El impacto de los tipos de ruta en los tiempos de entrega.
    - El efecto de la hora del día en los tiempos de entrega.
4. Creación de Modelos Predictivos
  - Se desarrollaron modelos para predecir el tiempo de entrega basado en las variables disponibles, buscando identificar los factores más influyentes.

## Conclusiones
  - Factores clave: Los principales factores que afectan el tiempo de entrega son la distancia, el tipo de ruta y la hora del día. Las rutas express suelen tener tiempos de entrega más cortos, mientras que las entregas en horas pico tienden a ser más lentas.
  - Predicción: Se logró construir un modelo predictivo que puede estimar los tiempos de entrega con un alto nivel de precisión, lo que puede ayudar a optimizar las rutas y mejorar la eficiencia operativa.
  - Próximos pasos: Incluir datos externos como condiciones climáticas y tráfico para mejorar aún más la precisión del modelo y expandir el análisis hacia otros factores que afecten las
