![Logo](https://raw.githubusercontent.com/EuniceGarcia503/FlightOnTime-DS/refs/heads/main/images/banner%20_repo_DS.png)
---

## Estado del proyecto.
🏗️ En construcción. 

# FlightOnTime – Data Science Module

Este directorio contiene todo el trabajo del equipo de Data Science para el proyecto **FlightOnTime**.

El objetivo del módulo es desarrollar un modelo de Machine Learning que permita predecir si un vuelo comercial despegará **puntual o retrasado**, a partir de datos históricos de vuelos.

Este módulo forma parte del repositorio principal del proyecto y está diseñado para integrarse con una API REST desarrollada por el equipo de Back-End.

---

## Estructura del proyecto

```text
data/
├── raw/
│   └── Datos originales sin modificaciones.
├── processed/
│   └── Datos limpios y preparados para el modelado.

notebooks/
└── Notebooks que contienen el flujo principal de Data Science:
    exploración de datos (EDA), preparación y entrenamiento del modelo.

models/
└── Modelo entrenado y serializado, listo para ser consumido por la API.

src/
└── Código reutilizable del proyecto:
    funciones de preprocesamiento, feature engineering y utilidades.

docs/
└── Documentación de apoyo:
    definiciones del problema, decisiones técnicas y análisis explicativos.

images/
└── Recursos visuales del proyecto:
    diagramas, esquemas y material gráfico para presentaciones.

requirements.txt
└── Librerías necesarias para ejecutar los notebooks y scripts del módulo.

