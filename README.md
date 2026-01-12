![Logo](https://raw.githubusercontent.com/EuniceGarcia503/FlightOnTime-DS/refs/heads/main/images/banner%20_repo_DS%20(1).png)
---

# Estado del proyecto.
🏗️ En construcción. 

# Descripción.

Este submódulo contiene el trabajo del equipo de Data Science del proyecto FlightOnTime.
Su objetivo es desarrollar un modelo de Machine Learning capaz de predecir si un vuelo comercial despegará puntual o con retraso, utilizando datos históricos de vuelos.
El modelo resultante será consumido por una API REST desarrollada por el equipo de Back-End, como parte de un MVP de hackathon.

---

# Estructura.

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

