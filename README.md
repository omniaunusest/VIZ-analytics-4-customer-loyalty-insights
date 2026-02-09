# Customer Flight and Loyalty Analysis

This project analyzes customer flight activity and loyalty data for an airline. It involves data cleaning, transformation, exploratory data analysis (EDA), and visualization to extract insights about customer behavior and the effectiveness of the loyalty program.

## Index

*   [English Version](#english-version)
    *   [Project Description](#project-description)
    *   [Files in this project](#files-in-this-project)
    *   [Getting Started](#getting-started)
*   [Versión en Español](#versión-en-español)
    *   [Descripción del Proyecto](#descripción-del-proyecto)
    *   [Archivos en este proyecto](#archivos-en-este-proyecto)
    *   [Cómo empezar](#cómo-empezar)

---

## English Version

### Project Description

This project performs a comprehensive analysis of an airline's customer loyalty program. It starts with two separate datasets, `c-flight-activity.csv` and `c-loyalty-history.csv`, which are cleaned, transformed, and merged into a single dataset, `flight-loyalty-activity.csv`.

The analysis explores various aspects of the data, including:
*   **Customer Demographics:** Province, city, gender, education, salary, and marital status.
*   **Flight Activity:** Flights booked, flights with companions, total distance, and points accumulated.
*   **Loyalty Program Engagement:** Loyalty card types, customer lifetime value (CLV), enrollment and cancellation patterns, and points redemption.

The key findings and visualizations are documented in the Jupyter notebooks and summarized in the `Documentación.md` file.

### Files in this project

*   `EDA.ipynb`: Jupyter notebook for Exploratory Data Analysis.
*   `Transformación.ipynb`: Jupyter notebook for data transformation and cleaning.
*   `Visualización.ipynb`: Jupyter notebook for data visualization.
*   `Documentación.md`: Detailed documentation of the analysis process and findings (in Spanish).
*   `csv/`: Directory containing the raw and processed data files.
    *   `c-flight-activity.csv`: Raw flight activity data.
    *   `c-loyalty-history.csv`: Raw loyalty history data.
    *   `flight-loyalty-activity.csv`: Merged and cleaned data.
*   `img/`: Directory containing the visualizations generated during the analysis.
*   `src/`: Directory containing source code.
    *   `lookandcompare.py`: Python script for data comparison.

### Getting Started

To explore this project, you can:
1.  Review the Jupyter notebooks (`EDA.ipynb`, `Transformación.ipynb`, `Visualización.ipynb`) to understand the step-by-step analysis.
2.  Read the `Documentación.md` file for a detailed explanation of the project.
3.  Examine the datasets in the `csv/` directory.

---

## Versión en Español

### Descripción del Proyecto

Este proyecto realiza un análisis exhaustivo del programa de lealtad de clientes de una aerolínea. Comienza con dos conjuntos de datos separados, `c-flight-activity.csv` y `c-loyalty-history.csv`, que se limpian, transforman y fusionan en un único conjunto de datos, `flight-loyalty-activity.csv`.

El análisis explora varios aspectos de los datos, incluyendo:
*   **Datos Demográficos de los Clientes:** Provincia, ciudad, género, educación, salario y estado civil.
*   **Actividad de Vuelo:** Vuelos reservados, vuelos con acompañantes, distancia total y puntos acumulados.
*   **Participación en el Programa de Lealtad:** Tipos de tarjetas de lealtad, valor del ciclo de vida del cliente (CLV), patrones de inscripción y cancelación, y canje de puntos.

Los hallazgos clave y las visualizaciones están documentados en los cuadernos de Jupyter y resumidos en el archivo `Documentación.md`.

### Archivos en este proyecto

*   `EDA.ipynb`: Cuaderno de Jupyter para el Análisis Exploratorio de Datos.
*   `Transformación.ipynb`: Cuaderno de Jupyter para la transformación y limpieza de datos.
*   `Visualización.ipynb`: Cuaderno de Jupyter para la visualización de datos.
*   `Documentación.md`: Documentación detallada del proceso de análisis y los hallazgos.
*   `csv/`: Directorio que contiene los archivos de datos brutos y procesados.
    *   `c-flight-activity.csv`: Datos brutos de actividad de vuelo.
    *   `c-loyalty-history.csv`: Datos brutos del historial de lealtad.
    *   `flight-loyalty-activity.csv`: Datos fusionados y limpios.
*   `img/`: Directorio que contiene las visualizaciones generadas durante el análisis.
*   `src/`: Directorio que contiene el código fuente.
    *   `lookandcompare.py`: Script de Python para la comparación de datos.

### Cómo empezar

Para explorar este proyecto, puedes:
1.  Revisar los cuadernos de Jupyter (`EDA.ipynb`, `Transformación.ipynb`, `Visualización.ipynb`) para comprender el análisis paso a paso.
2.  Leer el archivo `Documentación.md` para una explicación detallada del proyecto.
3.  Examinar los conjuntos de datos en el directorio `data/`.
