# 🧪 Experimento A/B | Landing Page

Proyecto de **Data Analytics** desarrollado con Python para evaluar el desempeño de dos versiones de una landing page mediante métricas de conversión, gasto promedio y pruebas estadísticas.

---

## 📌 Resumen ejecutivo

Se analizó un experimento A/B con dos versiones de landing page (A y B) para determinar si existían diferencias estadísticamente significativas en la **tasa de conversión** y en el **gasto promedio de los usuarios que convirtieron**.

También se estudió la relación entre la conversión, la **fuente de tráfico** y el **tipo de usuario** utilizando pruebas estadísticas según cada tipo de variable.

## 🎯 Objetivo del análisis

- Comparar el desempeño de las versiones A y B.
- Validar diferencias en conversión mediante una prueba de proporciones.
- Comparar el gasto promedio entre usuarios convertidos mediante una prueba t.
- Analizar la asociación entre conversión y fuente de tráfico.
- Analizar la asociación entre conversión y tipo de usuario.

## 🛠️ Tecnologías utilizadas

| Herramienta | Uso |
|---|---|
| Python | Análisis de datos |
| Pandas | Preparación y manipulación |
| NumPy | Cálculos numéricos |
| SciPy | Pruebas estadísticas |
| Statsmodels | Análisis estadístico |
| Matplotlib | Visualización |
| Seaborn | Visualización exploratoria |
| Jupyter Notebook | Desarrollo |

## 🔬 Metodología

1. Exploración y validación de los datos.
2. Comparación del gasto promedio entre A y B mediante **prueba t**.
3. Comparación de tasas de conversión mediante **prueba de proporciones**.
4. Análisis de fuente de tráfico y conversión mediante **chi-cuadrado**.
5. Análisis de tipo de usuario y conversión mediante **chi-cuadrado**.
6. Visualización de cantidades y proporciones.
7. Interpretación de resultados y elaboración de insights de negocio.


## 📈 Resultados principales

### Página A vs. B

**Tasa de conversión**

- Página A: **12,57 %**
- Página B: **15,96 %**
- Diferencia: **3,38 puntos porcentuales**
- La diferencia fue estadísticamente significativa.

**Gasto promedio por usuario convertido**

- Página A: **61,09**
- Página B: **68,75**
- Diferencia: **7,66 unidades monetarias**
- La diferencia fue estadísticamente significativa.

### Fuente de tráfico

Se encontró evidencia estadística de una asociación entre la **fuente de tráfico y la conversión** (**p = 0,0341**).

**Organic** concentra el mayor número absoluto de conversiones debido a su volumen de usuarios, mientras que **Email** presenta la mayor proporción de conversión.

### Tipo de usuario

No se encontró evidencia estadística suficiente de una asociación entre el **tipo de usuario y la conversión** (**p = 0,4736**).

Aunque los usuarios nuevos presentan más conversiones en términos absolutos, las proporciones de conversión entre usuarios nuevos y recurrentes son muy similares.

## 💡 Implicaciones de negocio

- Las dos versiones presentaron diferencias estadísticamente significativas en las métricas evaluadas.
- La fuente de tráfico mostró una asociación estadística con la conversión, por lo que conviene profundizar en desempeño y rentabilidad por canal.
- El tipo de usuario no mostró evidencia estadística suficiente de asociación con la conversión en este análisis.

## ⚠️ Consideraciones

Los resultados deben interpretarse dentro del contexto del experimento y de las variables analizadas. La significancia estadística identifica diferencias o asociaciones observadas, pero las decisiones de inversión deben considerar también costos, ingresos y contexto de campaña.

## 📁 Archivos

- `landing-experiment-ab-testing.ipynb`: notebook del análisis.
- `landing_experiment.csv`: dataset utilizado.
- `requirements.txt`: dependencias del proyecto.
- `.gitignore`: configuración de archivos ignorados.

## ▶️ Ejecución

1. Clonar o descargar el repositorio.
2. Instalar las dependencias de `requirements.txt`.
3. Colocar `landing_experiment.csv` en la ubicación esperada por el notebook.
4. Abrir el notebook con Jupyter Notebook, JupyterLab o VS Code.
5. Ejecutar las celdas en orden.

## 🚀 Competencias demostradas

- Análisis A/B
- Pruebas de hipótesis
- Prueba t
- Prueba de proporciones
- Chi-cuadrado
- Python para Data Analytics
- Pandas y NumPy
- Visualización de datos
- Interpretación de resultados
- Comunicación de insights de negocio

## 🔗 Proyecto

**Repositorio:**
https://github.com/catalinaduquediaz-svg/sprint-9-landing-experiment

## 🎓 Contexto académico

Proyecto desarrollado durante el **Bootcamp de Análisis de Datos de TripleTen**.

---

## 👩‍💻 Autora

**Catalina Duque**

Administradora de Empresas | Data Analytics | Business Analysis | QA Functional