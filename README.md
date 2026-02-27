# 🚢 Análisis Exploratorio de Datos (EDA) - Titanic Dataset

## 📋 Contexto y Objetivo
Este proyecto forma parte de mi portafolio de Data Science. Consiste en un Análisis Exploratorio de Datos (EDA) exhaustivo sobre el clásico dataset del Titanic. 
El objetivo principal no es crear un modelo predictivo todavía, sino demostrar dominio en la manipulación de datos: entender las distribuciones, limpiar valores nulos, detectar patrones de supervivencia y generar *insights* visuales claros.

## 🛠️ Herramientas Utilizadas
- **Lenguaje:** Python
- **Manipulación de Datos:** Pandas, NumPy
- **Visualización:** Seaborn, Matplotlib
- **Entorno:** Google Colab / Jupyter Notebook

## 🚀 Metodología Aplicada
1. **Data Wrangling:** Identificación y tratamiento de valores nulos (ej. imputación de la Edad mediante la mediana).
2. **Análisis Univariado:** Entender la distribución de las variables individuales (tarifas, edades, clases).
3. **Análisis Bivariado:** Relacionar variables independientes con la variable objetivo (`Survived`).
4. **Correlaciones:** Análisis de variables numéricas para evitar multicolinealidad en futuros modelos.

## 💡 Conclusiones Ejecutivas
- **Género:** Las mujeres tuvieron una tasa de supervivencia significativamente mayor (aprox. 74% vs 19% en hombres).
- **Estatus Socioeconómico:** Los pasajeros de 1ra clase (Pclass 1) tuvieron mayor prioridad de rescate.
- **Edad:** Los niños (menores de 10 años) muestran un pico de supervivencia, indicando que se respetó el protocolo "mujeres y niños primero".
