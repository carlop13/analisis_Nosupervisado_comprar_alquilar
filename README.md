# Análisis de Datos: Comprar vs Alquilar

Este proyecto realiza un análisis de datos para entender las diferencias entre las decisiones de compra y alquiler utilizando técnicas de reducción de dimensionalidad. El análisis se basa en un conjunto de datos que contiene características relacionadas con la decisión de comprar o alquilar.

## Contenidos

1. **Cargar el Conjunto de Datos**: El proyecto comienza cargando el conjunto de datos `comprar_alquilar.csv`.
2. **Preprocesamiento**:
   - **Normalización**: Las características son normalizadas utilizando `StandardScaler`.
   - **Reducción de Dimensionalidad**: Se aplica PCA (Análisis de Componentes Principales) para reducir las dimensiones a 2 para la visualización.
3. **Visualización**:
   - **Gráfica PCA**: Se genera un gráfico de dispersión que muestra la separación entre las decisiones de compra y alquiler en el espacio de los dos primeros componentes principales.

## Instrucciones de Uso

1. **Instalación de Dependencias**:
   Asegúrate de tener las siguientes librerías instaladas:
   - `pandas`
   - `scikit-learn`
   - `matplotlib`
   - `seaborn`

   Puedes instalarlas utilizando pip:
   ```bash
   pip install pandas scikit-learn matplotlib seaborn
