# 🚗 Predicción de Precios de Vehículos Usados (Core)

Este proyecto tiene como objetivo implementar y evaluar modelos de regresión para predecir los precios de vehículos usados. Se selecciona el mejor modelo utilizando métricas de evaluación como **MSE**, **RMSE** y **R²**.

---

## 🛠️ Requisitos del Proyecto

### 1. Carga y Exploración de Datos
- Descargar y cargar el dataset.
- Realizar una exploración inicial (dimensiones, tipos de datos, valores únicos).
- Identificar valores faltantes, duplicados y outliers.

### 2. Limpieza y Preprocesamiento
- Manejar valores faltantes.
- Eliminar duplicados.
- Corregir inconsistencias en variables categóricas.
- Escalar las características numéricas.
- Transformar variables categóricas (OneHotEncoding, LabelEncoding, etc.).

### 3. Análisis Exploratorio de Datos (EDA)
- Crear visualizaciones univariadas y multivariadas.
- Calcular estadísticas descriptivas.
- Detectar relaciones entre variables.

### 4. Modelado y Evaluación
- Implementar al menos dos modelos de regresión:
  - `LinearRegression`
  - `RandomForestRegressor`
- Evaluar los modelos usando:
  - **MSE**: Error Cuadrático Medio
  - **RMSE**: Raíz del Error Cuadrático Medio
  - **R²**: Coeficiente de Determinación
- Comparar los modelos y seleccionar el mejor.

### 5. Optimización del Modelo
- Optimizar el modelo seleccionado con `GridSearchCV`.
- Ajustar hiperparámetros para mejorar el rendimiento.

### 6. Documentación y Entrega
- Documentar el proceso en un archivo `.ipynb` claramente comentado.
- Incluir visualizaciones con interpretación.
- Subir el proyecto a un repositorio en GitHub con un **tag de liberación**.

---

> 🔍 Este proyecto combina análisis exploratorio, modelado predictivo y buenas prácticas de Machine Learning para abordar problemas reales de precios de vehículos.

