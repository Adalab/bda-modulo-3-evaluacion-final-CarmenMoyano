# Análisis de Datos de Vuelos y Educación

## Descripción 

Este proyecto tiene como objetivo analizar los datos de clientes de una compañía aérea para evaluar la relación entre el nivel educativo y diversos aspectos de las reservas de vuelos. Se realiza un análisis descriptivo y pruebas estadísticas para determinar si existen diferencias significativas en el número de vuelos reservados en función del nivel educativo.

## Contenido

1. [Preparación de Datos](#preparación-de-datos)
2. [Análisis Descriptivo](#análisis-descriptivo)
3. [Prueba Estadística](#prueba-estadística)
4. [Visualización de Datos](#visualización-de-datos)

## Preparación de Datos

### Carga y Limpieza de Datos

- **Carga de datos**: Los datos se cargan desde un archivo CSV.
- **Limpieza de datos**: Se eliminan duplicados y se corrigen errores en los datos (por ejemplo, fechas).

### Filtrado de Datos

- **Filtrado temporal**: Se filtran los clientes activos durante el periodo de enero 2017 a diciembre 2018.
- **Cálculo de fechas**: Se crean nuevas columnas para fechas combinando año, mes y día.

## Análisis Descriptivo

### Estadísticas Descriptivas

- **Cálculo de estadísticas**: Se agrupan los datos por nivel educativo y se calculan estadísticas descriptivas (media, mediana, desviación estándar, percentiles) del número de vuelos reservados.

### Comparación de Grupos

- **Agrupación**: Se dividen los niveles educativos en grupos de alto, medio y bajo, y se calcula la media y desviación estándar del número de vuelos reservados para cada grupo.

## Prueba Estadística

### Evaluación de Normalidad

- **Prueba de Shapiro-Wilk**: Se evalúa si los datos se ajustan a una distribución normal.

### Prueba de Diferencias

- **Prueba t de Student**: Se realiza para comparar las medias del número de vuelos reservados entre los grupos de alto y bajo nivel educativo.

### Alternativa para Datos No Normales

- **Prueba de Mann-Whitney U**: Se utiliza si los datos no siguen una distribución normal para comparar las medianas entre los grupos de alto y bajo nivel educativo.

## Visualización de Datos

### Gráficos Generales

- **Distribución por Provincia**: Gráfico de barras mostrando la distribución de clientes por provincia.
- **Salario por Nivel Educativo**: Gráfico de barras que muestra el salario promedio por nivel educativo.
- **Número de Vuelos Reservados**: Gráfico de líneas que muestra la evolución mensual de los vuelos reservados.
- **Relación entre Distancia y Puntos Acumulados**: Gráfico de dispersión con una línea de regresión para evaluar la relación entre distancia y puntos acumulados.

### Código

El código fuente se encuentra en los archivos `.py` y `.ipynb` proporcionados. Asegúrate de tener todas las librerías necesarias instaladas, que incluyen:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy`

## Requisitos

- Python 3.x
- Jupyter Notebook (si se usa el archivo `.ipynb`)

### Instalación de Dependencias

Puedes instalar las dependencias necesarias usando `pip`:

```bash
pip install pandas numpy matplotlib seaborn scipy
