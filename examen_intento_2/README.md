# Análisis de Datos en la Industria Hotelera

Este repositorio contiene el trabajo realizado para el examen de Data Science Fundamentals. El objetivo del análisis es explorar un conjunto de datos relacionados con reservas de hoteles, limpiarlo y generar visualizaciones que permitan entender la satisfacción de los clientes.

## Contenido del Repositorio

- **examen_intento_2/**
  - **data/**: Carpeta que contiene el dataset `hotel_bookings.csv`.
  - **json/**: Carpeta con un archivo JSON `valores_unicos_iniciales.json` que contiene valores únicos de ciertas columnas del dataset.
  - **notebook/**: Carpeta que contiene el archivo `hotel_bookings.ipynb`, donde se realiza la limpieza y exploración de datos.

## Descripción del Proyecto

### Objetivos

- Limpiar y explorar el conjunto de datos de reservas de hoteles.
- Realizar análisis descriptivos y visualizaciones para entender los patrones de reserva y la satisfacción del cliente.

### Proceso Realizado

1. **Carga de Datos**: Se importaron las librerías necesarias y se cargó el dataset.
2. **Limpieza de Datos**:
   - Se verificaron y ajustaron los tipos de datos.
   - Se eliminaron valores duplicados.
   - Se manejaron valores faltantes.
   - Se eliminaron columnas innecesarias, como 'company'.
3. **Exploración de Datos**:
   - Se realizaron análisis descriptivos y estadísticas sobre el conjunto de datos.
   - Se identificaron tendencias y correlaciones.
4. **Visualizaciones**:
   - Se generaron al menos cuatro visualizaciones para ilustrar los hallazgos.
     - Histograma de la duración de la estancia.
     - Gráfico de dispersión para analizar la relación entre el precio promedio diario y el número de reservas.
     - Gráfico de barras que muestra la cantidad de reservas por tipo de habitación.
     - Gráfico circular que ilustra la proporción de clientes repetidos frente a nuevos.

## Entrega

- El proyecto fue organizado y se subió a un repositorio en GitHub con un tag `v1.1`, que corresponde a la entrega del segundo intento del examen, fechado el 23/10/2024.
  
## Cómo Ejecutar el Notebook

1. Clona este repositorio a tu máquina local.
2. Asegúrate de tener instalado Jupyter Notebook.
3. Navega a la carpeta `notebook/` y abre `hotel_bookings.ipynb`.
4. Ejecuta las celdas para ver los resultados del análisis.

## Requerimientos

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn


