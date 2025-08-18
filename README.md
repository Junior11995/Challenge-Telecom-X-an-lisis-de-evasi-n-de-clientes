# 📊 Telecom X - Análisis de Evasión de Clientes (Churn)

## 📖 Descripción
Este proyecto forma parte del **Challenge de Data Science - Telecom X (Alura Latam)**.  
El objetivo es analizar los factores que llevan a la **evasión de clientes (Churn)** y generar insights estratégicos para reducir la tasa de cancelación.

A lo largo del proyecto se aplicó la metodología **ETL (Extract, Transform, Load)** y un **Análisis Exploratorio de Datos (EDA)** para identificar patrones y tendencias.

---

## 🚀 Objetivos del Proyecto
- Importar y manipular datos desde una **API en formato JSON**.  
- Aplicar **ETL**: limpieza, transformación y carga de datos.  
- Generar variables derivadas como **Cuentas_Diarias**.  
- Realizar un **EDA con visualizaciones estratégicas**.  
- Identificar factores que influyen en la evasión de clientes.  
- Producir un **informe final** con conclusiones y recomendaciones.

---

## 📂 Estructura del Proyecto

├── desaf_o_telecom_x.ipynb # Notebook principal con todo el análisis
├── TelecomX_Data.json # Fuente de datos (extraído desde la API)
├── telecomx_ready.csv # Dataset limpio y listo para análisis
└── README.md # Documentación del proyecto


---

## 🛠️ Tecnologías Utilizadas
- **Python 3**
- **Pandas** (manipulación de datos)
- **NumPy** (operaciones numéricas)
- **Matplotlib & Seaborn** (visualización de datos)
- **Plotly** (gráficos interactivos)
- **Google Colab / Jupyter Notebook**

---

## ⚙️ Instalación y Uso
1. Clonar este repositorio:
   ```bash
   git clone https://github.com/Junior11995/Challenge-Telecom-X-an-lisis-de-evasi-n-de-clientes.git
Instalar dependencias necesarias:

pip install -r requirements.txt


(opcional: puedes ejecutar directamente en Google Colab sin instalación local)

Abrir el notebook:

jupyter notebook desaf_o_telecom_x.ipynb

📊 Resultados del Análisis

Clientes con contratos mensuales presentan mayor tasa de evasión.

Los métodos de pago electrónicos muestran más cancelaciones.

La antigüedad del cliente (tenure) es un factor clave: clientes recientes cancelan más.

Promover contratos a largo plazo y bundles de servicios puede reducir el churn.

📝 Informe Final

El notebook incluye un informe completo con:

Introducción

Limpieza y transformación de datos

Análisis exploratorio

Conclusiones e insights

Recomendaciones estratégicas

👨‍💻 Autor

Desarrollado por [Junior Valera] como parte del Challenge de Alura Latam - Data Science.

📌 Recursos

📂 Dataset original: TelecomX_Data.json

📖 Documentación oficial de Pandas: DataFrame.describe()

📖 Blog Alura: Manipulación de strings en Pandas

