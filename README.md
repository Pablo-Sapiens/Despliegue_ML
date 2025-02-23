**Despliegue de Algoritmos de Machine Learning** 🚀

Este proyecto tiene como objetivo la construcción, entrenamiento, ajuste y despliegue de modelos de Machine Learning utilizando técnicas avanzadas de preprocesamiento y validación. También se incluye el registro de experimentos con MLflow y la creación de una API para la interacción con el modelo.

🔍 **1. Dataset: Descarga directa desde sklearn.datasets.**

🧑‍💻 **2. Análisis Exploratorio de Datos (EDA)**

📊 Características del Dataset: Número de instancias y atributos.

🏠 Información de los Atributos: Descripción de cada variable.

🔍 Análisis de las Categorías: Distribución y estadísticas.

📚 División Train/Test: Separación de datos para entrenamiento y evaluación.

📈 Correlaciones: Matriz de correlación entre variables.

🧹 **3. Preprocesamiento de Datos**

Limpieza de Datos: Tratamiento de outliers y valores atípicos.

🔄 Escalado de Características:

MinMaxScaler

StandardScaler

🤖 **4. Entrenamiento de Modelos**

Regresión Lineal

Árbol de Decisión

🎯 **5. Validación Cruzada**

Aplicación de validación cruzada para evaluar el rendimiento de los modelos.

🌳 **6. RandomForestRegressor**

Entrenamiento y ajuste de hiperparámetros.

⚙️ **7. Perfeccionamiento del Modelo**

Búsqueda de hiperparámetros óptimos con GridSearchCV y RandomizedSearchCV.

🥇 **8. Elección del Mejor Modelo**

Comparación de métricas y selección del modelo final.

🧪 **9. Evaluación con el Conjunto de Test**

Métricas finales sobre datos no vistos.

📝 **10. Registro de Métricas con MLflow**

Registro de experimentos y modelos entrenados.

🐍 **11. Generación de Archivos Python**

.py para funciones reutilizables y ejecución con argumentos.

⚡ **12. Despliegue con FastAPI**

Creación de un servicio API para realizar predicciones en producción.

💡 **Cómo Ejecutar el Proyecto**

Clonar el repositorio.

Crear y activar un entorno virtual.

Instalar dependencias con pip install -r requirements.txt.

Ejecutar los notebooks para generar y entrenar modelos.

Levantar la API de FastAPI con uvicorn api.main:app --reload.

🚀 **Futuras Mejoras**

Implementar un modelo más complejo como XGBoost o LightGBM.

Despliegue en servicios cloud como AWS, GCP o Azure.

Creación de un dashboard interactivo para visualización de métricas.
