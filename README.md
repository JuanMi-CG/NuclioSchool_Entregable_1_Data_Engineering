# 🚗 Proyecto de Preprocesamiento de Datos para Data Science: Dataset de Coches BMW

## 📄 Descripción del Proyecto

Este proyecto tiene como objetivo realizar el preprocesamiento de datos sobre un dataset de coches BMW. El objetivo final es preparar los datos para predecir el precio del vehículo, aunque en esta fase no se realizará la predicción. 

## 📚 Índice de contenidos

1. 📝 Trabajo Previo
   - 📦 Importación de librerías
   - 📂 Carga de datasets
   - 🗂️ Estructura de Datos
   - 🔍 Detección de Nulos
     - 🛠️ Funciones
     - 📊 Criterios
     - 📉 Nulos con relevancia baja
     - 📈 Nulos con relevancia alta
     - ⚖️ Nulos con relevancia media
   - 🔄 Valores Duplicados
   - 📊 Análisis univariable
     - 🔢 Valores únicos
     - 🗓️ Fechas
     - 📈 Histogramas
2. 🛠️ Preprocesamiento
   - 🔗 Correlaciones
3. 📉 Matriz de Correlación
   - 🎯 Análisis del Target
   - ⚖️ Simetría
   - 🔍 Análisis entre el Target y las Variables Independientes
4. 🗃️ Categorización de columnas
   - 🛠️ Funciones
   - 📝 Modificaciones en los tipos de datos
5. 🔢 Codificación OneHot
   - ❓ ¿Cómo Funciona?
   - 📈 Importancia
   - 🔍 Segunda comprobación de correlaciones
6. 📋 Conclusiones del dataset
7. 🛠️ Herramientas para documentar en Word
   - ❌ Filas eliminadas

## 🗂️ Estructura del Proyecto

El proyecto está estructurado en varias secciones, cada una enfocada en un aspecto específico del preprocesamiento de datos. 

1. **🗑️ Eliminación de Columnas**
   - Se identificaron y eliminaron columnas irrelevantes para el análisis.
2. **🧹 Manejo de Valores Nulos**
   - Se trató y limpió las columnas con valores nulos.
3. **📊 Análisis Univariable**
   - Se realizó un análisis univariable para detectar outliers y posibles agrupaciones.
4. **🔗 Análisis de Correlación Inicial**
   - Se realizó un análisis de correlación inicial para identificar variables correlacionadas.
5. **🔍 Análisis Variable vs Target**
   - Se analizó la relación entre las variables y el target (precio del vehículo) para identificar insights interesantes.
6. **🔢 Transformación de Categóricas a Numéricas**
   - Se transformaron las variables categóricas a numéricas utilizando técnicas adecuadas.
7. **⚖️ Normalización de Variables Numéricas**
   - Se normalizaron las variables numéricas.
8. **🔗 Análisis de Correlación Final**
   - Se realizó un análisis de correlación final para observar los cambios después del preprocesamiento.
9. **📋 Dataset Limpio y Preprocesado**
   - Se presentó la lista completa de columnas del dataset limpio y preprocesado, incluyendo el tipo de dato de cada columna y un pantallazo de las primeras 5 líneas.

## 📁 Estructura de Carpetas

- **datasets/**: Contiene el dataset de coches BMW.
  - `BMW_dataset.csv`
- **PDFs/**: Contiene el documento PDF solicitado por el profesor.
  - `Entregable_BMW.pdf`
- **src/**: Contiene el código fuente del proyecto.
  - `preprocessing.py`
- **notebooks/**: Contiene los notebooks utilizados durante el desarrollo del proyecto.
  - `preprocessing.ipynb`
- **outputs/**: Contiene los resultados y outputs generados durante el preprocesamiento.
  - `correlation_matrix_initial.png`
  - `correlation_matrix_final.png`
  - `outliers_analysis.png`

## 🔧 Requisitos

- Python 3.x
- Librerías:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

## 🚀 Instrucciones

1. Clonar el repositorio.
   ```sh
   git clone [<URL>](https://github.com/JuanMi-CG/NuclioSchool_Entregable_1_Preprocesamiento.git)
   ```