# Sistema Predictivo de Trading

## **Descripción del Proyecto**
Este proyecto implementa un sistema de predicción de precios de activos financieros y generación de señales de trading basado en modelos de Machine Learning. Analiza y utiliza **ARIMA, XGBoost, Random Forest** para la predicción y clasificación de señales, además de un entorno de **backtesting** para evaluar el rendimiento de las estrategias. La visualización de resultados se realiza mediante **Power BI**, donde los datos se estructuran en un modelo semántico con dashboards interactivos.

## **Requisitos del Sistema**

### **1. Entorno de Desarrollo**
- **Python 3.13** (específicamente esta versión para evitar problemas de compatibilidad).
- **Jupyter Notebook o Visual Studio Code** (para ejecutar los scripts de procesamiento y modelado de datos).
- **Power BI Desktop** (para la visualización de los datos procesados y resultados de predicción).

### **2. Instalación de Librerías Necesarias**
Asegúrate de instalar las dependencias ejecutando el siguiente comando en la terminal:

```bash
pip install numpy pandas matplotlib yfinance ta xgboost scikit-learn statsmodels optuna
