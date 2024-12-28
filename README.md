# Kaggle-competicion-Enfermedad-Coronaria

# Proyecto de Entrenamiento de Modelo para Predicción de Enfermedades Coronarias

Este proyecto tiene como objetivo desarrollar un modelo de aprendizaje automático capaz de predecir el riesgo de enfermedades coronarias basado en un conjunto de características clínicas recopiladas por llamadas telefonicas de Estados Unidos. A continuación, se describen los pasos realizados en el desarrollo del modelo.

---

## 1. Introducción

Las enfermedades coronarias, incluyendo la enfermedad de las arterias coronarias y el infarto de miocardio, representan una de las principales causas de muerte a nivel mundial. Predecir de manera temprana estos problemas cardíacos puede salvar vidas, y el uso de datos accesibles sobre el historial de salud de una persona y su estilo de vida puede hacer que estas predicciones sean más viables y escalables en la práctica clínica.. Este proyecto busca construir un modelo de clasificación que utilice datos clínicos para identificar a pacientes en riesgo.

---

## 2. Recopilación de Datos

### Fuentes de Datos
- **Dataset utilizado:** Behavioral Risk Factor Surveillance System (BRFSS) de 2022
- **Número de observaciones:** 480 000 registros
- **Número de características:** 27

### Exploración Inicial
Se realizó un análisis exploratorio para comprender la distribución de las variables, detectar valores nulos y determinar la necesidad de transformaciones.

![Exploración de Datos](#) <!-- Coloca aquí una imagen o gráfico -->

---

## 3. Preprocesamiento de Datos

### Limpieza de Datos
- Eliminación de valores nulos.
- Tratamiento de valores atípicos.
- Normalización de variables numéricas.

### Codificación
- Variables categóricas transformadas mediante [método de codificación, e.g., one-hot encoding].

![Limpieza de Datos](#) <!-- Coloca aquí una imagen o gráfico -->

### División del Dataset
El dataset fue dividido en:
- **70%** para entrenamiento.
- **30%** para validación.

---

## 4. Selección del Modelo

Se evaluaron diferentes algoritmos para determinar el más adecuado:
- **Regresión Logística.**
- **Bosques Aleatorios.**
- **Gradient Boosting (e.g., XGBoost).**

### Métrica de Evaluación
Se utilizó la métrica **AUC-ROC** para medir el desempeño del modelo.

![Comparación de Modelos](#) <!-- Coloca aquí un gráfico comparativo -->

---

## 5. Entrenamiento del Modelo

El modelo seleccionado se entrenó utilizando los datos procesados. Se realizaron ajustes de hiperparámetros mediante búsqueda en cuadrícula (*grid search*) para optimizar el desempeño.

### Resultados del Entrenamiento
- **Precisión:** [Valor obtenido]
- **Recall:** [Valor obtenido]
- **AUC-ROC:** [Valor obtenido]

![Curva ROC](#) <!-- Coloca aquí una curva ROC -->

---

## 6. Evaluación del Modelo

El modelo fue evaluado en el conjunto de validación. Los resultados demuestran su capacidad para identificar casos de riesgo con un balance adecuado entre precisión y recall.

![Resultados de Evaluación](#) <!-- Coloca aquí una imagen de resultados -->

---

## 7. Implementación

Se desplegó el modelo en un entorno productivo mediante [inserta plataforma, e.g., Flask, AWS Lambda]. El modelo está preparado para recibir datos en tiempo real y devolver predicciones.

---

## 8. Conclusiones

El modelo desarrollado muestra un alto potencial para apoyar a los profesionales médicos en la identificación temprana de enfermedades coronarias. Las próximas iteraciones del proyecto incluirán:
- Uso de datos adicionales para mejorar el desempeño.
- Implementación de interpretabilidad del modelo.

---

## 9. Referencias

- [Inserta aquí referencias relevantes]

---

## Anexos

Incluye aquí cualquier información adicional que pueda ser relevante.

---

*¡Completa los espacios con imágenes, gráficos y resultados obtenidos!*
