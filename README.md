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

├── TAIA.ipynb # Notebook principal con todo el análisis
├── diabetes.csv # Dataset Pima Indians Diabetes Database
└── README.md

## Modelos evaluados

| Modelo        | Recall | ROC-AUC |
| ------------- | ------ | ------- |
| XGBoost ⭐     | 0.87   | 0.942   |
| LightGBM      | 0.83   | 0.947   |
| Random Forest | 0.83   | 0.944   |
| KNN           | 0.80   | 0.793   |
| MLP           | 0.78   | 0.906   |

## Modelo final

**XGBoost** — seleccionado por mayor Recall (0.87), priorizando la minimización de falsos negativos en el contexto clínico.

## Dataset

Pima Indians Diabetes Database — UCI Machine Learning Repository  
https://archive.ics.uci.edu/dataset/34/diabetes