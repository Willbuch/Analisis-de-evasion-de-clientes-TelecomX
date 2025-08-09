
# Proyecto: Análisis de Evasión de Clientes - Telecom X

Este proyecto tiene como objetivo analizar los datos de clientes de **Telecom X** para identificar los factores que influyen en la evasión (churn), utilizando herramientas de análisis de datos en Python.

## Objetivos del Proyecto

- Comprender el comportamiento de los clientes que cancelan sus servicios.
- Detectar patrones y variables asociadas al churn.
- Apoyar al equipo de Data Science en la construcción de modelos predictivos.
- Proponer recomendaciones estratégicas para reducir la tasa de cancelación.

## Dataset

El dataset se encuentra en formato JSON y fue obtenido de un repositorio público de GitHub. Contiene información sobre clientes, sus características demográficas, servicios contratados, historial de facturación y si abandonaron el servicio o no.

- Fuente de datos: [TelecomX_Data.json](https://raw.githubusercontent.com/ingridcristh/challenge2-data-science-LATAM/main/TelecomX_Data.json)
- Diccionario de datos: [Diccionario de variables](https://raw.githubusercontent.com/ingridcristh/challenge2-data-science-LATAM/main/TelecomX_diccionario.md)

## Estructura del Proyecto

El análisis está dividido en las siguientes etapas, las cuales se encuentran estructuradas dentro del notebook `EDA_Churn_TelecomX_Structurado.ipynb`:

### 1. Extracción de Datos
- Importación de bibliotecas.
- Lectura de datos desde la fuente remota.

### 2. Transformación de Datos
- Inspección inicial de columnas y tipos de datos.
- Limpieza de inconsistencias (nulos, duplicados, tipos incorrectos).
- Creación de la columna `Cuentas_Diarias`.
- Estandarización de variables categóricas.

### 3. Carga y Análisis
- Análisis descriptivo de las variables.
- Visualización de la distribución de evasión.
- Análisis por variables categóricas y numéricas.
- Cálculo de correlaciones.

### 4. Informe Final
- Conclusiones principales del análisis.
- Recomendaciones para reducir el churn.

## Herramientas Utilizadas

- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Resultados

El análisis reveló que ciertos factores como el tipo de contrato, el método de pago y el monto facturado influyen significativamente en la decisión de cancelar el servicio. Estas observaciones pueden ser utilizadas como base para la creación de modelos predictivos y acciones de retención.
