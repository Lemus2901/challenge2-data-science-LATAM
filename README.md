# 📊 TelecomX LATAM - Análisis de Evasión de Clientes (Churn)

Este proyecto analiza los datos de clientes de TelecomX en LATAM para identificar patrones de evasión (Churn) y proporcionar insights útiles para la toma de decisiones.

## 📁 Estructura del Proyecto

1. **Extracción**:
   - Los datos se obtienen desde un archivo JSON alojado en un repositorio público.
   - Se utiliza la librería `requests` para descargar los datos y `pandas` para estructurarlos en un DataFrame.

2. **Transformación**:
   - Se desestructuran columnas anidadas en el JSON (como `customer`, `phone`, `internet`, y `account`).
   - Los datos se combinan en un único DataFrame para facilitar el análisis.

3. **Análisis y Visualización**:
   - Se realizan gráficos para explorar la relación entre variables como:
     - Tipo de servicio de Internet y Churn.
     - Método de pago y Churn.
   - Se utiliza `matplotlib` y `seaborn` para las visualizaciones.

4. **Informe Final**:
   - Se presentan los hallazgos clave en gráficos y resúmenes.

## 📊 Visualizaciones

Algunos gráficos generados incluyen:
- **Distribución de Churn**: Muestra la proporción de clientes que evaden el servicio.
- **Relación entre el tipo de servicio de Internet y Churn**.
- **Relación entre el método de pago y Churn**.

