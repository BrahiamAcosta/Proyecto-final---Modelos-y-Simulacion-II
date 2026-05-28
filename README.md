# Predicción del Retorno Relativo de Inversión en Taquilla Cinematográfica

Proyecto desarrollado para el curso **Modelos y Simulación II** utilizando el dataset **The Movies Dataset** de Kaggle.

## Objetivo del proyecto

El objetivo del proyecto es predecir el retorno relativo de inversión de una película en taquilla utilizando metadatos disponibles antes del estreno.

El problema se aborda como una tarea de **regresión supervisada**, utilizando como variable objetivo:

```text
y = log(revenue / budget)
```

---

# Contenido del repositorio

El repositorio contiene:

* `Comparación_de_Modelos_de_Aprendizaje_de_Máquina_en_la_Predicción_de_Ingresos_Cinematográficos.pdf`
  Reporte completo del proyecto, metodología y resultados.

* `exploracion_movies_dataset.ipynb`
  Notebook inicial de exploración preliminar y análisis del dataset.

* `modelos_prediccion_taquilla.ipynb`
  Notebook principal con el pipeline completo de Machine Learning.

---

# Video de sustentación

El video de sustentación del proyecto se encuentra en el siguiente enlace:

**https://youtu.be/8EgnVZrPnmY**

---

# Dataset utilizado

Dataset original:

* The Movies Dataset — Kaggle
  https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset

Archivos necesarios:

```text
movies_metadata.csv
credits.csv
keywords.csv
```

---

# Ejecución en Google Colab

A continuación se dan las instrucciones para ejecutar el notebook principal:

`modelos_prediccion_taquilla.ipynb`

## Requisitos previos

Antes de ejecutar el notebook:

1. Tener una cuenta de Google.
2. Descargar el dataset desde Kaggle.
3. Descomprimir el dataset descargado.

---

## Configuración de Google Drive

En la raíz principal de Google Drive debe existir una carpeta llamada:

```text
movies-modelos2
```

Dentro de esa carpeta deben ubicarse los siguientes archivos:

```text
movies_metadata.csv
credits.csv
keywords.csv

Estos se obtienen al descomprimir el dataset.
```

La estructura esperada es:

```text
Mi unidad/
└── movies-modelos2/
    ├── movies_metadata.csv
    ├── credits.csv
    └── keywords.csv
```

---

## Ejecución del notebook

1. Subir el notebook a Google Colab.
2. Abrir el notebook.
3. Ejecutar las celdas en orden secuencial, bloque por bloque.

El notebook fue diseñado para ejecutarse directamente sobre Google Colab utilizando archivos almacenados en Google Drive.

---
