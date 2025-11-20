# 🚖 Predicción de Pedidos de Taxis - Sweet Lift Taxi

## 📌 Descripción del Proyecto
La compañía **Sweet Lift Taxi** ha recopilado datos históricos sobre pedidos de taxis en los aeropuertos. Para atraer a más conductores durante las horas pico, es necesario predecir la cantidad de pedidos de taxis para la próxima hora.

El objetivo de este proyecto es construir un modelo de Machine Learning para realizar dicha predicción.

## 🎯 Objetivo
La métrica de evaluación es la **RECM (Raíz del Error Cuadrático Medio)** o *RMSE* en inglés.
* **Meta:** El RECM en el conjunto de prueba no debe ser superior a **48**.

## 🛠️ Tecnologías Utilizadas
* **Python** 3.9+
* **Pandas** (Manipulación de datos y series temporales)
* **Matplotlib** (Visualización y análisis de estacionalidad)
* **Statsmodels** (Descomposición estacional `seasonal_decompose`)
* **Scikit-Learn** (Modelado predictivo: Regresión Lineal, Random Forest)
