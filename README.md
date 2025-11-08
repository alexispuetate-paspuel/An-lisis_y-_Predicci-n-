# Análisis y Predicción
# Descripción

Aplicación desarrollada en Google Colab que permite analizar, visualizar y predecir el precio spot de la electricidad.
También ofrece la posibilidad de comparar varios países, observar tendencias y evaluar el impacto de variables como combustibles, embalses y precipitaciones.

# Cómo funciona

Antes de comenzar, descarga la carpeta comprimida con los archivos disponibles en Classroom.

Carga de datos: se pueden subir archivos CSV o generar datos simulados.

Limpieza automática: el código detecta las columnas de fecha y valor, y corrige posibles errores o valores faltantes.

Visualización: se generan gráficos de puntos, líneas e interpolaciones tipo spline para mostrar las tendencias de los datos.

Comparación internacional: permite visualizar los precios promedio por país y compararlos en un mismo gráfico.

Predicción: utiliza modelos de Random Forest y regresión polinomial para estimar precios futuros.

Evaluación: calcula métricas como MAE, RMSE y R² para medir la precisión del modelo.

Resultados: genera gráficas de relación entre precio, combustible y precipitación, y exporta los resultados en archivos CSV.

# Ejecución en Google Colab

Abre el notebook en Google Colab.

Ejecuta las celdas en orden.

Sube tus archivos CSV cuando se solicite.

Observa las gráficas y las métricas generadas.

Descarga los resultados desde la carpeta /content/.

# Salidas principales

Gráficas de evolución e interpolación del precio.

Predicción de precios a siete días.

Indicadores de precisión del modelo (MAE, RMSE y R²).

Archivos CSV con resultados y comparaciones entre países.
