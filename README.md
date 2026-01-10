![Logo](https://raw.githubusercontent.com/EuniceGarcia503/FlightOnTime/refs/heads/main/Imagenes/banner_readme_DS.png)
---

## Estado del proyecto.
🏗️ En construcción. 

## Estructura del Repositorio.

- `data/`: datasets del proyecto.
  - `raw/`: datos originales sin modificaciones.
  - `processed/`: datos limpios y preparados para el modelado.
- `notebooks/`: flujo principal de Data Science (EDA, preparación y modelado).
- `models/`: modelo entrenado listo para ser consumido por la API.
- `docs/`: documentación y análisis de apoyo.
- `src/`: código reutilizable (preprocesamiento y features).
- `images/`: recursos visuales del proyecto (banner, diagramas).
- `requirements.txt`: librerías utilizadas.

> Nota: los datos en `data/raw/` se conservan sin modificaciones; cualquier transformación se realiza sobre copias en `data/processed/`.


## Descripción.
🤖 Este proyecto busca aplicar modelos de *Machine Learning* y algoritmos de **clasificación binaria**, basados en datos históricos de vuelos.

🎯 Su objetivo principal será el **estimar el riesgo de retraso** y determinar si un vuelo **despegará a tiempo o no**.

### Inputs a utilizar:
- Aerolínea.
- Aeropuerto de origen.  
- Aeropuerto de destino.  
- Fecha de partida.  
- Distancia del vuelo. 

### Outputs deseados:
- Predicción del estado del vuelo (a tiempo / retrasado). 
- Probabilidad asociada a la predicción.

## Dataset.
📌 Información sobre la fuente de datos y su estructura será incorporada en esta sección.

## Uso de los Notebooks.
📌 En esta sección se documentará el flujo de trabajo y el orden recomendado de ejecución de los notebooks.
