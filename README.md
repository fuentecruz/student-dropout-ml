# 🎓 Predicción de Deserción Estudiantil con Machine Learning

## 📌 Descripción

Este proyecto consiste en la creación de un dataset sintético que simula la deserción estudiantil en un contexto universitario. Su propósito es facilitar el análisis y la predicción de abandono académico mediante técnicas de Machine Learning.

---

## 🎯 Objetivo

Generar un conjunto de datos que permita identificar estudiantes en riesgo de abandonar sus estudios durante el primer año académico.

---

## 🧠 Enfoque de Machine Learning

El problema se aborda como una tarea de **clasificación supervisada**, donde se predice una variable binaria:

* **Dropout:** Sí / No

Se propone el uso de **Regresión Logística** debido a que:

* Es adecuada para problemas de clasificación binaria
* Permite estimar probabilidades
* Es fácil de interpretar

---

## 📊 Información del Dataset

El dataset contiene **500 registros** con las siguientes variables:

### 🔹 Variables Demográficas

* Edad: 17–30
* Género: Masculino / Femenino
* Origen: Urbano / Rural

### 🔹 Variables Académicas

* HighSchool_GPA: 50–100 (con outliers hasta 120)
* Admission_Score: 50–100
* First_Semester_Grade: 40–100 (incluye valores atípicos como 0)

### 🔹 Variables Financieras

* Nivel Socioeconómico: Bajo / Medio / Alto
* Beca: Sí / No
* Préstamo: Sí / No

### 🔹 Variable Objetivo

* Dropout: Sí / No

---

## ⚠️ Problemas de Datos Simulados

Para representar escenarios reales, se introdujeron:

* **Valores faltantes:**
  5% de los datos fueron reemplazados aleatoriamente por valores nulos

* **Outliers:**

  * HighSchool_GPA con valores hasta 120
  * First_Semester_Grade con valores iguales a 0

* **Variables categóricas:**
  Requieren codificación para su uso en modelos

---

## 📈 Análisis Exploratorio de Datos (EDA)

Se realizó un análisis exploratorio utilizando Google Colab.

### 🔎 Hallazgos principales:

* Se validó correctamente la estructura del dataset
* Se identificaron valores faltantes y outliers
* Se analizó la distribución de la variable objetivo
* Se observó relación entre el rendimiento académico y la deserción

---

## 📊 Resultados

El modelo de Machine Learning permite identificar patrones asociados al abandono estudiantil.
*(Aquí puedes agregar accuracy si lo tienes, por ejemplo: “El modelo alcanzó una precisión de XX%”)*

---

## 🧾 Conclusión

El dataset generado es consistente y cumple con los objetivos planteados.
Permite aplicar técnicas de Machine Learning para predecir la deserción estudiantil y analizar factores de riesgo.

---

## 📁 Estructura del Repositorio

```
student-dropout-ml/
│
├── student_dropout_dataset.csv
├── analysis.ipynb
└── README.md
```

---

## 🛠️ Herramientas Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

---

## 📌 Notas Finales

Este proyecto fue desarrollado con fines académicos para simular un caso real de análisis de datos y Machine Learning.

