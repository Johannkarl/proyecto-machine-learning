# proyecto-machine-learning
predicción de resultados de partidos de la UEFA champions legue
# ⚽ ML_prediccion_goles / ML_goal_prediction

## 🌍 English

### 🧩 Problem to Solve

This project aims to predict the number of **goals a football player will score** in a season using historical performance statistics. This can help clubs and analysts estimate future performance and support decision-making for player recruitment or game strategies.

### 📂 Dataset

- **Source**: Provided locally (private dataset).
- **Description**: Contains detailed statistics for professional football players up to 2020, including:
  - Age
  - Appearances
  - Shots and shots on target
  - Assists
  - Key passes, fouls, offsides, etc.

> ℹ️ The dataset is private and was not obtained from a public URL. It includes both offensive and defensive stats across several match events.

### 🛠️ Solution Overview

We used a **Random Forest Regressor** to build a supervised regression model, trained with the most relevant features (like `Shots`, `Assists`, etc.) to predict the target variable `Goals`.  
The model achieved an **R² score of 0.94** and an **RMSE of 3.05** on test data.

### 🗂️ Repository Structure


---

## 🇪🇸 Español

### 🧩 Problema a resolver

Este proyecto busca predecir la cantidad de **goles que marcará un jugador de fútbol** en una temporada, a partir de estadísticas de rendimiento anteriores. Puede ayudar a clubes y analistas a estimar el rendimiento futuro y tomar decisiones sobre fichajes o estrategias de juego.

### 📂 Dataset

- **Fuente**: Proporcionado localmente (dataset privado).
- **Descripción**: Incluye estadísticas detalladas de jugadores de fútbol profesional hasta 2020, incluyendo:
  - Edad
  - Apariciones
  - Disparos y disparos al arco
  - Asistencias
  - Pases clave, faltas, fuera de juego, etc.

> ℹ️ El dataset es privado y no se obtuvo desde un enlace público. Contiene estadísticas tanto ofensivas como defensivas.

### 🛠️ Solución adoptada

Se utilizó un **Random Forest Regressor** para construir un modelo de regresión supervisada, entrenado con las variables más relevantes (como `Shots`, `Assists`, etc.) para predecir la variable objetivo `Goals`.  
El modelo alcanzó un **R² de 0.94** y un **RMSE de 3.05** sobre los datos de prueba.

### 🗂️ Estructura del repositorio

