# 📊 Predicción de Suscripción Bancaria: Machine Learning de Extremo a Extremo

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Perfil-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/ichbinzeed)
[![Python](https://img.shields.io/badge/Python-3.x-green?style=flat-square&logo=python)](https://www.python.org/)
[![Keras](https://img.shields.io/badge/Framework-Keras%20/%20TensorFlow-red?style=flat-square&logo=keras)](https://keras.io/)

## 🎯 Objetivo del Proyecto
El objetivo principal fue desarrollar un sistema de inteligencia artificial capaz de predecir si un cliente se suscribirá a un depósito a plazo fijo. Este modelo permite a las instituciones bancarias **optimizar sus campañas de marketing**, reduciendo costos operativos y contactando únicamente a los clientes con alta probabilidad de conversión.

---

## 🚀 Lo que hice

Para este proyecto, implementé un flujo de trabajo de Ciencia de Datos robusto y escalable:

* **Ingeniería de Características Inteligente:** Diseñé un sistema de procesamiento que separa automáticamente variables numéricas y categóricas, asegurando que el modelo reciba la información limpia y optimizada.
* **Selección Avanzada de Variables (RFECV):** Utilicé técnicas de eliminación recursiva con validación cruzada para identificar qué factores (como la duración de la llamada o indicadores económicos) realmente mueven la aguja del negocio, eliminando el "ruido" innecesario.
* **Arquitectura de Deep Learning (Keras):** Construí una Red Neuronal utilizando la API Funcional de Keras, integrando el preprocesamiento directamente en el modelo para facilitar su despliegue en producción.
* **Comparativa de Modelos:** No me quedé con una sola opción; evalué y comparé el rendimiento de múltiples algoritmos:
    * **Redes Neuronales (Keras)** 🏆 *(Mejor rendimiento en AUC)*
    * Regresión Logística
    * Support Vector Machines (SVM)
    * K-Nearest Neighbors (KNN)
    * Árboles de Decisión

---

## 📈 Resultados Obtenidos

El modelo final (Red Neuronal) alcanzó métricas sólidas que demuestran su fiabilidad:

| Métrica | Valor | Significado |
| :--- | :--- | :--- |
| **Accuracy** | **91.2%** | Alta precisión general en las predicciones. |
| **AUC-ROC** | **0.76** | Capacidad efectiva para distinguir entre clientes interesados y no interesados. |

> **Nota de Negocio:** Gracias al análisis de la **Curva ROC**, el modelo puede ajustarse para ser más "conservador" o "agresivo" según la estrategia comercial del banco en cada campaña.

---

## 🛠️ Herramientas y Tecnologías

* **Lenguaje:** Python
* **Análisis de Datos:** Pandas, NumPy
* **Visualización:** Matplotlib, Seaborn (Matrices de Confusión, Curvas ROC)
* **Machine Learning:** Scikit-Learn (Pipelines, RFECV, ColumnTransformer)
* **Deep Learning:** Keras / TensorFlow (API Funcional)

---

## ✉️ Contacto
Estoy buscando activamente oportunidades para aportar valor en equipos de Datos y Tecnología. Si te interesa mi perfil para roles de **Data Scientist, Data Analyst o ML Engineer**, hablemos:

* **LinkedIn:** [linkedin.com/in/ichbinzeed](https://www.linkedin.com/in/ichbinzeed)

---
*Proyecto desarrollado como parte de mis estudios de Machine Learning.*
