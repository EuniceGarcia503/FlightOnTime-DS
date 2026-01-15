![Logo](https://raw.githubusercontent.com/EuniceGarcia503/FlightOnTime-DS/refs/heads/main/images/banner%20_repo_DS%20(1).png)
---

# Estado del proyecto.
🏗️ En construcción. 

# Sobre este módulo.

## Descripción. 

Este módulo contiene el trabajo del equipo de Data Science del proyecto FlightOnTime.
Su objetivo es desarrollar un modelo de Machine Learning capaz de predecir si un vuelo comercial despegará puntual o con retraso, utilizando datos históricos de vuelos.
El modelo resultante será consumido por una API REST desarrollada por el equipo de Back-End, como parte de un MVP de hackathon.

- [Decisiones sobre estructura y documentación.](https://github.com/EuniceGarcia503/FlightOnTime-DS/blob/main/docs/decisiones_repo_y_documentacion.ipynb)

---

## Alcance.

El trabajo del equipo de Data Science en este proyecto cubre las siguientes etapas:

- [Definición del problema de negocio.](https://github.com/EuniceGarcia503/FlightOnTime-DS/blob/main/docs/documentacion/definicion_del_problema_de_negocio.ipynb)
  
  [Justificación y decisiones adoptadas.](https://github.com/EuniceGarcia503/FlightOnTime-DS/blob/main/docs/justificacion/01_justificacion_problema_negocio.ipynb)
  
- [Definición del problema de Machine Learning.](https://github.com/EuniceGarcia503/FlightOnTime-DS/blob/main/docs/documentacion/definicion_del_problema_ml.ipynb)

  [Justificación y decisiones adoptadas.](https://github.com/EuniceGarcia503/FlightOnTime-DS/blob/main/docs/justificacion/02_justificaci%C3%B3n_problema_ml.ipynb)
  
- [Definición del target.](https://github.com/EuniceGarcia503/FlightOnTime-DS/blob/main/docs/documentacion/definicion_del_target.ipynb)

  [Justificación y decisiones adoptadas.]()
   
- [Descripción y comprensión del dataset.](ruta)  
- [Exploración de datos (EDA) enfocada en conclusiones.](ruta)  
- [Preparación de datos para el modelado.](ruta)  
- [Feature engineering con foco en información disponible antes del despegue.](ruta)  
- [Selección de un modelo adecuado para un MVP.](ruta)  
- [Entrenamiento del modelo.](ruta)  
- [Evaluación del desempeño del modelo.](ruta)  
- [Exportación del modelo e integración con la API](ruta)  

Este módulo no aborda la implementación de la API ni componentes de Front-End.

---
## Estructura.

```text
data/
├── raw/
│   └── Datos originales sin modificaciones.
├── processed/
│   └── Datos limpios y preparados para el modelado.

notebooks/
└── Notebooks que contienen el flujo principal de Data Science:
    exploración de datos (EDA),feature engineering, preparación y entrenamiento del modelo; evaluación.

models/
└── Modelo entrenado y serializado, listo para ser consumido por la API.

src/
└── Código reutilizable del proyecto:
    funciones de preprocesamiento, feature engineering y utilidades.

docs/
├── docs/justificacion/
│   └── documentos que explican y fundamentan decisiones
       conceptuales y técnicas.
├── docs/documentacion/
│   └── documentos formales que definen el problema, el alcance y las reglas utilizadas en el proyecto.

images/
└── Recursos visuales del proyecto:
    diagramas, esquemas y material gráfico para presentaciones.

requirements.txt
└── Librerías necesarias para ejecutar los notebooks y scripts del módulo.

```



