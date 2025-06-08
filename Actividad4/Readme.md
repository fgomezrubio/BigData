# Actividad 4 | Métricas de calidad de resultados - Big Data con PySpark

<table>
  <tr>
    <td style="width: 150px;">
      <img src="https://upload.wikimedia.org/wikipedia/commons/4/47/Logo_del_ITESM.svg" alt="ITESM Logo" width="130"/>
    </td>
    <td>
    
## 📌 Información General

**Nombre:** Francisco Gómez Rubio  
**Matrícula:** 710437  
**Escuela:** Instituto Tecnológico y de Estudios Superiores de Monterrey (ITESM)  
**Materia:** Análisis de Grandes Volúmenes de Datos

  </tr>
</table>

---

## 🧠 Descripción de la Actividad

Esta actividad tiene como objetivo aplicar técnicas de **aprendizaje supervisado** y **no supervisado** sobre un gran volumen de datos históricos de criptomonedas, utilizando herramientas de procesamiento distribuido con PySpark.

Se construyó una muestra representativa a partir de un dataset de más de 125 millones de registros, respetando criterios de estratificación, y se entrenaron modelos de regresión lineal y K-Means clustering. La evaluación del desempeño incluyó métricas como **RMSE**, **MAE**, **R²**, **Silhouette Score** e **Inertia**, complementadas con visualizaciones gráficas y un análisis crítico de los resultados.

---

## 🛠️ Tecnologías Utilizadas

- **Apache Spark (PySpark)** para procesamiento distribuido
- **Python 3.11.12**
- **Jupyter Notebooks** para documentación del análisis
- **Google Colab** como entorno de ejecución
- **Librerías**: 
  - `pyspark.sql`
  - `pyspark.ml`
  - `pandas`
  - `matplotlib`
  - `seaborn`

---

## 📊 Resultados Destacados

- Modelo de regresión con **R² = 0.99999** y **MAE ≈ 0.44**, con un **error relativo de solo 0.16%**.
- Modelo de clustering con **Silhouette Score = 1.000**, tras aplicar normalización de volumen.
- Visualizaciones interpretables que refuerzan la calidad de los modelos y su ajuste a los datos.

---

