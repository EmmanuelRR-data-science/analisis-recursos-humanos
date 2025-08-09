# Análisis de Recursos Humanos con Python y SQLite

Este repositorio contiene el análisis completo de un dataset de recursos humanos sobre empleados que abandonan una empresa, utilizando Python, SQLite y visualizaciones en matplotlib/seaborn. El objetivo es crear una base de datos SQLite a partir de un CSV externo y realizar consultas SQL para extraer insights relevantes sobre satisfacción, horas trabajadas, promociones y evaluaciones.

---

## Descripción del Proyecto

Se partió de un archivo CSV que contiene variables como nivel de satisfacción, evaluación, número de proyectos, horas mensuales, promociones, estado de empleo, entre otras. Se importó a SQLite para realizar consultas específicas:

1. Comparar nivel de satisfacción promedio entre empleados que se quedan y los que se van.
2. Calcular el promedio de horas mensuales para empleados con salario bajo o medio.
3. Extraer empleados que obtuvieron promoción en los últimos 5 años y abandonaron la empresa.
4. Extraer empleados con evaluación igual o mayor a 0.9.

Posteriormente, se generaron visualizaciones para ilustrar estos insights.

---

## Requisitos

- Python 3.x
- Pandas
- SQLite3
- Matplotlib
- Seaborn
- Google Colab

---

- **Para reproducir el análisis solo ejecuta el notebook en Google Colab con el dataset cargado**
- **El informe completo está en Análisis de Recursos Humanos.pdf**
