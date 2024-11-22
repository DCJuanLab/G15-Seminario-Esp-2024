
# MEO3 - Análisis Predictivo de Accidentes de Tránsito en Bogotá

Este proyecto forma parte de la Universidad de Antioquia, en el marco de la Especialización en Analítica y Ciencia de Datos. El trabajo fue desarrollado como un seminario académico, utilizando Python para el análisis y procesamiento de datos.

## Descripción

El objetivo de este proyecto es analizar datos sobre accidentes de tráfico en Bogotá, 2023, para predecir dos aspectos clave:
1. **Gravedad de los accidentes** utilizando un modelo de machine learning.
2. **Frecuencia de los accidentes** con un modelo de series de tiempo.

## Integrantes

- **Juan Sebastián Espinosa** 
- **José Luis Mena** 

## Requisitos previos

Antes de ejecutar este proyecto, asegúrese de tener instaladas las siguientes herramientas:

- **Python 3.8 o superior**.
- **Jupyter Notebook o Google Colab**.
- **Bibliotecas necesarias**: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `scipy`.

Puede instalar las bibliotecas ejecutando:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn scipy
```

## Archivos incluidos

| **Archivo**                      | **Descripción**                                                                  |
|-----------------------------------|----------------------------------------------------------------------------------|
| `ME03.ipynb`                      | Notebook principal con el desarrollo completo del proyecto.                       |
| `Gravedad.xls`                    | Tabla procesada para aplicar modelos de machine learning y predecir la gravedad. |
| `Frecuencia.xls`                  | Tabla procesada para aplicar modelos de series de tiempo y predecir la frecuencia de accidentes. |

## Cómo ejecutar el notebook

1. Clone o descargue este repositorio en su máquina local.
2. Abra el archivo `ME03.ipynb` en Jupyter Notebook o súbalo a Google Colab.
3. Ejecute las celdas en orden para reproducir los resultados.

## Estructura del notebook

1. **Librerías**: Importación de las librerías necesarias para el análisis, procesamiento de datos, visualización y modelado.
2. **Importación de Datos y Selección de Columnas Significativas**: Importación de los datos desde el archivo `SIGAT_ANUARIO_2023.xlsx` y selección de las columnas más relevantes para el análisis.
3. **Unión de Campos Seleccionados de las Tablas**: Combinación de las tablas `Siniestros`, `Vehículos` y `Actores` para crear un único DataFrame.
4. **Manejo de Valores Faltantes y Eliminación de Registros Duplicados**: Tratamiento de los valores vacíos y registros duplicados para asegurar la calidad de los datos.
5. **Analítica Descriptiva**: Análisis de las variables numéricas y categóricas, incluyendo gráficos de distribución y pruebas estadísticas.
6. **Preparación del DataFrame para Modelación de la Gravedad de los Accidentes**: Transformación de las variables para la predicción de la gravedad usando machine learning.
7. **División de los Datos para la Predicción de la Gravedad**: División de los datos en conjuntos de entrenamiento y prueba.
8. **Preparación del DataFrame para la Predicción de la Frecuencia de Accidentes por Día (Series de Tiempo)**: Agregación de datos por fecha y localidad para modelar la frecuencia de accidentes.
9. **Analítica Descriptiva de la Serie de Tiempo**: Análisis de la frecuencia de accidentes a lo largo del tiempo, identificando tendencias, estacionalidad y anomalías.

## Créditos

Desarrollado por estudiantes de la **Universidad de Antioquia** como parte de la **Especialización en Analítica y Ciencia de Datos**.
