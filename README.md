# Predicción de user rating en animes

## Objetivo
Desarrollar un modelo para predecir el User Rating de animes a partir de variables descriptivas, realizando previamente un proceso de limpieza, transformación y selección de variables.

## Dataset
Dataset de animes con información como rating de usuarios, número de votos, año de emisión y otras características.

## Metodología
- Análisis de calidad de datos y eliminación de variables irrelevantes
- Transformación de variables de texto a numéricas
- Análisis exploratorio (EDA) con distribuciones y detección de patrones
- Identificación de outliers mediante IQR y Z-score
- Transformaciones adicionales: logaritmos en variables sesgadas y codificación de variables categóricas
- Tratamiento de valores nulos
- Análisis de correlaciones con foco en la variable objetivo
- Selección de variables: filtro por correlación y forward selection

## Resultados
- Identificación de variables con mayor relación con el rating
- Mejora en la calidad del dataset tras transformación
- Consistencia entre selección de variables y análisis exploratorio

## Tecnologías utilizadas
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
