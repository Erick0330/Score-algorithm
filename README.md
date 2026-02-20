# 🧬 LRP1 Scoring Algorithm

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Library-Pandas-150458?style=for-the-badge&logo=pandas)
![Bioinformatics](https://img.shields.io/badge/Field-Bioinformatics-success?style=for-the-badge)

Este repositorio contiene un algoritmo especializado para el procesamiento, limpieza y puntuación (*scoring*) de datos biológicos relacionados con la proteína **LRP1**. El script está diseñado para transformar datos brutos de bases de datos proteómicas en archivos estructurados listos para su interpretación.

---

## 🧐 ¿Qué hace este algoritmo?

El flujo de trabajo principal se centra en la normalización de identificadores y el cálculo de métricas de relevancia. Sus funciones principales incluyen:

* **Normalización de IDs Uniprot:** Limpieza de caracteres especiales (como `*`) en identificadores de proteínas para asegurar la compatibilidad con otras bases de datos.
* **Cálculo de Scoring:** Implementación de lógica específica para puntuar la relevancia o interacción de proteínas en el contexto de LRP1.
* **Data Wrangling:** Transformación de DataFrames complejos, eliminación de redundancias y manejo de valores nulos.
* **Exportación Automatizada:** Generación de reportes finales en formato Excel (`.xlsx`) con formatos limpios para su uso inmediato.

---

## 🛠️ Requisitos Técnico

Para ejecutar este proyecto, necesitarás las siguientes librerías de Python:

```bash
pip install pandas openpyxl
