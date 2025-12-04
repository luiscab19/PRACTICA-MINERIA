# Análisis de Datos de Recursos Humanos - Proyecto de Minería de Datos

Proyecto académico de análisis de datos del departamento de Recursos Humanos de una empresa tecnológica, desarrollado como parte del curso de Minería de Datos.

## Información del Proyecto

- **Cátedra**: Minería de Datos
- **Período**: 2025C
- **Autor**: Luis Alvarez
- **Docente**: Daniel Carrizo

## Descripción del Proyecto

Este proyecto realiza un análisis exhaustivo de los datos del departamento de Recursos Humanos de una empresa de tecnología, con el objetivo de identificar patrones, tendencias y áreas de oportunidad en la gestión del talento humano.

## Contenido del Análisis

### 1. Configuración Inicial y Carga de Datos
- Importación de librerías (pandas, numpy, matplotlib, seaborn, scipy)
- Carga del dataset desde archivo Excel

### 2. Diagnóstico Inicial del Dataset
- Verificación de dimensiones y estructura del dataset
- Análisis de tipos de datos
- Identificación de valores faltantes

### 3. Proceso de Limpieza y Transformación de Datos
- Eliminación de registros duplicados
- Imputación de valores faltantes en múltiples columnas:
  - MarriedID
  - GenderID
  - MaritalStatusID
  - EmpStatusID
  - EmploymentStatus
  - DeptID
  - PerfScoreID
  - Salary
  - HispanicLatino
  - ManagerID
- Estandarización de tipos de datos
- Eliminación de columnas redundantes

### 4. Análisis de Preguntas Clave

#### 4.1. Relación entre departamento y rendimiento
- Prueba de Chi-cuadrado para evaluar asociación
- Visualización mediante gráfico de barras

#### 4.2. Perfil de diversidad de la organización
- Análisis de distribución por raza/etnia
- Distribución por género
- Distribución hispano/latino
- Distribución por estado civil

#### 4.3. Mejores fuentes de contratación para diversidad
- Análisis estadístico de relaciones entre fuentes de reclutamiento y diversidad
- Evaluación de efectividad por fuente

#### 4.4. Predicción de rotación de empleados
- Análisis de tasas de rotación por departamento
- Identificación de razones principales de terminación
- Desarrollo de indicadores predictivos

#### 4.5. Equidad salarial
- Análisis de equidad por género (prueba t)
- Análisis de equidad por raza (ANOVA)
- Análisis de equidad por origen hispano/latino

## Tecnologías Utilizadas

- **Python 3.x**
- **pandas**: Manipulación y análisis de datos
- **numpy**: Cálculos numéricos
- **matplotlib**: Visualización de datos
- **seaborn**: Visualización estadística
- **scipy**: Análisis estadístico
- **Google Colab**: Entorno de desarrollo

## Estructura del Código

El código está organizado en las siguientes secciones:

1. Configuración inicial y carga de datos
2. Diagnóstico del dataset
3. Limpieza y transformación de datos
4. Análisis de preguntas específicas
5. Visualización de resultados
6. Conclusiones estadísticas

## Hallazgos Principales

### 1. Departamento vs. Rendimiento
No se encontró relación significativa entre el departamento de trabajo y la puntuación de rendimiento (p = 0.5464).

### 2. Perfil de Diversidad
- Distribución de género: 56.6% femenino, 43.4% masculino
- Sobre-representación de empleados blancos (60.1%)
- Mínima representación hispana (0.3%)

### 3. Fuentes de Contratación
- Relación significativa con diversidad racial (p = 2.5e-08)
- No hay relación significativa con género u origen hispano

### 4. Predicción de Rotación
- Tasas de rotación varían por departamento (22% a 100%)
- Patrones predecibles en razones de terminación

### 5. Equidad Salarial
- No se encontraron diferencias significativas por género, raza u origen hispano/latino
- Prácticas remunerativas equitativas

## Instrucciones de Ejecución

1. Cargar el archivo `dataset_exercise.xlsx` en Google Colab
2. Ejecutar todas las celdas en orden secuencial
3. Revisar los resultados y visualizaciones generadas

## Datos Requeridos

El análisis requiere un archivo Excel con las siguientes columnas (entre otras):
- Employee_Name
- Position
- Department
- Salary
- PerformanceScore
- Sex
- RaceDesc
- HispanicLatino
- EmploymentStatus
- TermReason
- Y otras variables demográficas y laborales
# google colab:
link:  https://colab.research.google.com/drive/1IpCvC7zUExpwRpCuQPNNiIW5NAEGwne1?usp=sharing
