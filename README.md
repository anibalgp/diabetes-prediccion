# Análisis Predictivo de Diabetes mediante Técnicas de Machine Learning

Proyecto desarrollado para el curso **Inteligencia Artificial (1INF24)** — PUCP.

## Descripción

Sistema de detección temprana de diabetes mellitus tipo II mediante algoritmos 
de clasificación supervisada aplicados al dataset Pima Indians Diabetes Database.

## Integrantes

- David Alexander Abad Cortez
- Axel Eduardo Arista Montero
- Juan Andrés Bazán Arteaga
- Anibal Giuliano Gonzales Paredes

## Estructura del repositorio

├── Grupo4_TA_Final.ipynb # Notebook principal con todo el análisis
├── diabetes.csv # Dataset Pima Indians Diabetes Database
└── README.md

## Modelos evaluados

| Modelo | Recall | ROC-AUC |
| :--- | :--- | :--- |
| LightGBM ⭐ | 0.83 | 0.947 |
| Random Forest | 0.83 | 0.944 |
| XGBoost | 0.81 | 0.949 |
| KNN | 0.80 | 0.793 |
| MLP | 0.78 | 0.906 |

## Modelo final
**LightGBM** — seleccionado por ser el modelo más equilibrado en las métricas de evaluación. Aunque XGBoost obtuvo el ROC-AUC más alto (0.949), LightGBM alcanzó el Recall máximo (0.83) junto con Random Forest. Se eligió la versión base de LightGBM por sobre la optimizada porque mantuvo la misma sensibilidad (0.83), un mejor ROC-AUC y una mayor simplicidad metodológica, priorizando así la minimización de los falsos negativos en el tamizaje clínico.

## Dataset

Pima Indians Diabetes Database — UCI Machine Learning Repository  
https://archive.ics.uci.edu/dataset/34/diabetes
