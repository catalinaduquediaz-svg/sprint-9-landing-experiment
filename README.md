# 🧪 Experimento A/B – Landing Page

Análisis de un experimento A/B realizado sobre dos versiones de una landing page (A y B), con el objetivo de evaluar diferencias en la tasa de conversión y el gasto promedio de los usuarios convertidos.

## 🎯 Objetivo

Analizar el desempeño de las versiones A y B y validar mediante pruebas estadísticas si existen diferencias significativas en conversión y gasto promedio. También se analiza la relación entre la conversión, la fuente de tráfico y el tipo de usuario.

## 🛠️ Tecnologías utilizadas

- Python
- Pandas
- NumPy
- SciPy
- Statsmodels
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔬 Análisis realizado

- Exploración y validación de los datos.
- Comparación del gasto promedio entre las páginas A y B mediante prueba t.
- Comparación de tasas de conversión mediante prueba de proporciones.
- Prueba chi-cuadrado para fuente de tráfico y conversión.
- Prueba chi-cuadrado para tipo de usuario y conversión.
- Visualización de variables categóricas.
- Interpretación de resultados estadísticos.
- Elaboración de insights ejecutivos y recomendaciones de negocio.

## 📈 Principales hallazgos

### Página A vs B

- Tasa de conversión A: **12,57 %**.
- Tasa de conversión B: **15,96 %**.
- Diferencia: **3,38 puntos porcentuales**.
- Gasto promedio entre usuarios convertidos: A **61,09** vs B **68,75**.
- Las diferencias observadas fueron estadísticamente significativas.

### Fuente de tráfico

Se encontró evidencia estadísticamente significativa de asociación entre la fuente de tráfico y la conversión (**p = 0,0341**). Organic concentra el mayor número absoluto de conversiones por su volumen de usuarios, mientras que Email presenta la mayor proporción de conversión.

### Tipo de usuario

No se encontró evidencia estadística suficiente de una asociación entre el tipo de usuario y la conversión (**p = 0,4736**). Las proporciones de conversión de usuarios nuevos y recurrentes son muy similares.

## 💡 Recomendaciones

- Considerar la página B como referencia para futuras iteraciones del experimento, dado su mayor tasa de conversión y mayor gasto promedio entre los usuarios convertidos.
- Profundizar en el desempeño y la rentabilidad de las fuentes de tráfico, incorporando métricas de costos e ingresos antes de tomar decisiones de inversión.

## 📁 Archivos

- `landing-experiment-ab-testing.ipynb`: notebook completo del análisis.
- `landing_experiment.csv`: dataset utilizado en el análisis. Colócalo en la raíz del repositorio para ejecutar el notebook localmente.

## ▶️ Cómo ejecutar el proyecto

1. Descargar o clonar el repositorio.
2. Instalar las dependencias indicadas en `requirements.txt`.
3. Colocar `landing_experiment.csv` en la misma carpeta que el notebook.
4. Abrir `landing-experiment-ab-testing.ipynb` con Jupyter Notebook, JupyterLab o VS Code.
5. Ejecutar las celdas en orden.

## 👩‍💻 Autora

Catalina Duque
