# Bike Sales Analysis Dashboard (Excel)

[English Version](#english-version) | [Versión en Español](#versión-en-español)

---

## English Version

This repository contains a comprehensive data analysis project regarding bicycle purchases, processed entirely in Microsoft Excel. The project covers the full data lifecycle: from cleaning raw data to creating a dynamic and interactive Dashboard.

### Project Content
The main analysis is located in the [Excel Project.xlsx](./Excel%20Project.xlsx) file and is organized into the following stages:

#### 1. Data Cleaning & Standardization
Data auditing was performed to ensure consistency across the dataset:
* **Duplicate Removal:** Initial cleanup to ensure unique records.
* **Normalization:** * Marital Status: `M` -> `Married`, `S` -> `Single`.
    * Gender: `F` -> `Female`, `M` -> `Male`.
* **Feature Engineering (Age Bracket):** Categorized age using nested `IF` functions:
    * **Adolescent:** Under 31 years old.
    * **Middle Age:** 31 to 54 years old.
    * **Old:** Over 54 years old.

#### 2. Analysis with Pivot Tables
Multiple pivot tables were developed to identify consumer patterns, focusing on:
* Average income per purchase decision by gender.
* Impact of commute distance on sales.
* Customer segmentation by age brackets.

#### 3. Interactive Dashboard
The project concludes with a centralized visual panel that includes:
* **Dynamic Charts:** Visualizations that update automatically based on the pivot tables.
* **Slicers:** Interactive filters (Region, Education, Occupation) that allow real-time data exploration.

---

## Versión en Español

Este repositorio contiene un proyecto completo de análisis de datos sobre la compra de bicicletas, procesado íntegramente en Microsoft Excel. El proyecto abarca todo el ciclo de vida de los datos: desde la limpieza de datos crudos hasta la creación de un Dashboard dinámico e interactivo.

### Contenido del Proyecto
El análisis principal se encuentra en el archivo [Excel Project.xlsx](./Excel%20Project.xlsx) y está organizado en las siguientes etapas:

#### 1. Limpieza de Datos y Estandarización
Se realizaron procesos de auditoría de datos para asegurar la consistencia:
* **Eliminación de duplicados:** Limpieza inicial para garantizar registros únicos.
* **Normalización:** * Estado Marital: `M` -> `Married`, `S` -> `Single`.
    * Género: `F` -> `Female`, `M` -> `Male`.
* **Ingeniería de Variables (Age Bracket):** Se categorizó la edad mediante funciones `IF` anidadas:
    * **Adolescent:** Menores a 31 años.
    * **Middle Age:** Entre 31 y 54 años.
    * **Old:** Mayores de 54 años.

#### 2. Análisis con Tablas Dinámicas
Se desarrollaron múltiples tablas dinámicas para identificar patrones de consumo, destacando:
* Relación entre ingresos promedio y la decisión de compra por género.
* Impacto de la distancia de transporte (Commute Distance) en las ventas.
* Segmentación de clientes por rangos de edad.

#### 3. Dashboard Interactivo
El proyecto culmina en un panel visual centralizado que incluye:
* **Gráficos Dinámicos:** Visualizaciones automáticas basadas en las tablas de análisis.
* **Segmentadores (Slicers):** Filtros interactivos de Región, Educación y Ocupación que permiten explorar los datos en tiempo real.

---
## How to view / Cómo visualizarlo
**EN:** To experience the dashboard interactivity (slicers and filters), please download the `.xlsx` file and open it in the Microsoft Excel desktop application.

**ES:** Para experimentar la interactividad del Dashboard (filtros y segmentadores), se recomienda descargar el archivo `.xlsx` y abrirlo en la aplicación de escritorio de Microsoft Excel.
