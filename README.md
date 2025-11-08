# An-lisis_y-_Predicci-n-
# Descripción

Aplicación en Google Colab que analiza, visualiza y predice el precio spot de la electricidad.
Permite comparar varios países, observar tendencias, y
evaluar el impacto de variables como combustibles, embalses y precipitaciones.

# Cómo funciona

Carga de datos: se suben archivos CSV o se generan datos simulados.

Limpieza automática: el código detecta columnas de fecha y valor.

Visualización: crea gráficos de puntos, líneas e interpolación spline.

Comparación internacional: muestra precios medios por país.

Predicción: usa modelos Random Forest y polinomial para estimar precios futuros.

Evaluación: calcula métricas MAE, RMSE y R².

Resultados: genera gráficas de relación precio–combustible–precipitación y exporta CSV.

# Ejecución en Google Colab

Abre el notebook en Colab.

Ejecuta las celdas en orden.

Sube tus archivos CSV cuando se solicite.

Observa las gráficas y métricas generadas.

Descarga los resultados desde /content/.

# Salidas principales

Gráficas de evolución e interpolación.

Predicción de precios a 7 días.

Indicadores de precisión del modelo.

Archivos CSV con resultados y comparaciones.
