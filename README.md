📊 Análisis de Evasión de Clientes (Churn) – Telecomunicaciones
🧩 Descripción del Proyecto

La evasión de clientes (Churn) representa uno de los principales desafíos en el sector de telecomunicaciones, ya que impacta directamente en los ingresos y la sostenibilidad del negocio.

Este proyecto tiene como objetivo analizar el comportamiento de los clientes y detectar patrones asociados a la cancelación del servicio, utilizando técnicas de análisis exploratorio de datos y preparación para modelado predictivo.

El análisis se centra en variables demográficas, servicios contratados, tipo de contrato y comportamiento de facturación, permitiendo generar insights accionables para estrategias de retención.

🎯 Objetivos

Comprender el fenómeno de Churn en clientes de telecomunicaciones.

Identificar factores clave asociados a la evasión.

Analizar el impacto de variables categóricas y numéricas en la cancelación del servicio.

Preparar los datos para futuras etapas de modelado predictivo.

Proponer recomendaciones estratégicas basadas en los hallazgos.

🗂️ Estructura del Proyecto
│
├── 📓 notebook.ipynb        # Notebook principal con todo el análisis
├── 📄 README.md             # Documentación del proyecto
└── TelecomX_Data.json   # Dataset original (si aplica)

📥 Fuente de Datos

Formato: JSON

Contenido: Información de clientes, servicios contratados, facturación y estado de churn.

Los datos fueron importados desde una API/URL y normalizados para su análisis.

🧹 Limpieza y Tratamiento de Datos

Las principales tareas realizadas fueron:

Normalización de datos anidados con pd.json_normalize.

Conversión de variables numéricas almacenadas como texto.

Tratamiento de valores nulos y verificación de duplicados.

Normalización de variables categóricas.

Creación de la variable Cuentas_Diarias a partir de la facturación mensual.

📊 Análisis Exploratorio de Datos (EDA)

Se realizó un análisis exploratorio enfocado en variables relevantes para la evasión:

🔹 Variables Categóricas

Género

Tipo de contrato

Método de pago

Facturación electrónica

Servicios de internet y soporte técnico

🔹 Variables Numéricas

Tiempo de contrato (customer_tenure)

Cargo mensual

Total gastado

Costo diario (Cuentas_Diarias)

El análisis incluyó:

Tablas de frecuencia y proporciones

Histogramas

Boxplots

Comparaciones entre clientes con y sin churn

🧠 Principales Insights

Los clientes con contrato mensual presentan mayor tasa de evasión.

Una menor antigüedad está fuertemente asociada al churn.

Cargos mensuales y diarios elevados incrementan el riesgo de cancelación.

La falta de soporte técnico se relaciona con mayor evasión.

El género no muestra diferencias significativas en el churn.
<img width="470" height="498" alt="image" src="https://github.com/user-attachments/assets/34a71d50-b8a2-4478-872c-1c13f5ed70a3" />


📌 Recomendaciones

Incentivar contratos de mayor duración.

Implementar estrategias de retención temprana para nuevos clientes.

Optimizar planes con costos elevados.

Reforzar servicios de soporte técnico.

Diseñar campañas focalizadas según método de pago.

🛠️ Tecnologías Utilizadas

Python

Pandas

NumPy

Matplotlib

Scikit-learn

Google Colab / Jupyter Notebook

🚀 Próximos Pasos

Implementar modelos predictivos de churn (Regresión Logística, Árboles, etc.).

Evaluar métricas como accuracy, recall y ROC-AUC.

Desplegar el modelo para predicción de evasión en tiempo real.

Crear dashboards interactivos para monitoreo.

👤 Autor

Luis Alberto Huamaní Cahuana
📧 [albert052592@gmail.com]
📍 Proyecto de análisis y visualización de datos para el programa Oracle Next Education (ONE) - Alura LATAM.
