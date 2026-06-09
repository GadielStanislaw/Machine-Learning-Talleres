# Machine-Learning-Talleres

Implementaciones en clase de Machine Learning con Felipe Grijalva.

## Descripción

Este repositorio contiene los talleres y laboratorios desarrollados durante el curso de Machine Learning. Cada notebook aborda un tema específico con explicaciones teóricas y ejercicios prácticos implementados en Python usando scikit-learn.

## Contenido

### Feature Selection (`Feature_selection.ipynb`)
Exploración de las principales técnicas de selección de características aplicadas al dataset de Cáncer de Mama (scikit-learn):
- **Modelo base** — usando las 30 características disponibles
- **Método Filter** — SelectKBest con Mutual Information
- **Método Wrapper** — Eliminación Recursiva de Características (RFE)
- **Método Embedded** — Regresión Logística con regularización L1 (LASSO)
- **Método Híbrido** — combinación de Filter (MI) + Wrapper (RFE)
- **Borda Voting** — votación por consenso entre los 4 métodos anteriores

## Autores

- Stan Mora
- Evelyn Bermeo
