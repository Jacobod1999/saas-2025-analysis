
# 📊 Análisis de las 100 Principales Empresas SaaS – 2025

---

## 🧹 Objetivo del análisis  
Este análisis busca identificar patrones de crecimiento, valorización y atracción de inversión entre las principales empresas SaaS del mundo en 2025. Además, se evalúan tendencias por industria y geografía para detectar oportunidades emergentes y unicornios en potencia.

---

## 🔍 Preguntas guía por sección

---

### 1. 📈 Crecimiento y Valorización  
**¿Qué características comparten las empresas SaaS con mayor valuación o crecimiento?**

- 🔝 Ranking de empresas por Valuation y ARR: [`top_10_valuation.csv`](visualizaciones/top_10_valuation.csv), [`top_10_arr.csv`](visualizaciones/top_10_arr.csv)
- 📉 Scatter plot: [`Funding vs Valuation`](visualizaciones/scatter_funding_vs_valuation.png)
- 📐 Ratio promedio Valuation / ARR: **16.25**
- ⚠️ Outliers detectados: [`3 empresas`](visualizaciones/valuation_to_arr_outliers.csv)

---

### 2. 🏭 Benchmarking por Industria  
**¿Qué industrias están dominando en 2025?**

- 📊 Tabla comparativa: [`benchmark_industria.csv`](visualizaciones/benchmark_industria.csv)
- 📦 Boxplots por industria:
  - [`Valuation`](visualizaciones/boxplot_valuation_industry.png)
  - [`ARR`](visualizaciones/boxplot_arr_industry.png)
  - [`Funding`](visualizaciones/boxplot_funding_industry.png)

---

### 3. 💸 Análisis de Inversión  
**¿Cómo influyen el número de rondas e inversores en el rendimiento?**

- 📈 Relación inversores vs valuación: [`investor_count_vs_valuation.png`](visualizaciones/investor_count_vs_valuation.png)
- ✅ Empresas con VCs top: [`empresas_con_vc_top.csv`](visualizaciones/empresas_con_vc_top.csv)
- 🌍 Heatmap de funding por país: [`heatmap_funding_pais.png`](visualizaciones/heatmap_funding_pais.png)

---

### 4. 🌍 Estudio Geográfico  
**¿Qué regiones dominan el mercado SaaS global?**

- 🌎 Ranking por país: [`arr_por_pais.csv`](visualizaciones/arr_por_pais.csv)
- 🗺️ Mapa interactivo: [`mapa_arr_por_pais.html`](visualizaciones/mapa_arr_por_pais.html)

---

### 5. 🦄 Identificación de Unicornios Emergentes  
**¿Qué startups tienen perfil de convertirse en líderes?**

- ❌ No se encontraron startups con < 5 años y ARR elevado.
- 🕸️ Comparativa con gigantes: [`radar_emergentes_vs_top.html`](visualizaciones/radar_emergentes_vs_top.html)

---

## 🧠 Insights Adicionales

- Muchas empresas top tienen relaciones claras con inversores de renombre como Sequoia o a16z.
- Algunas industrias como Analytics y AI tienen valuaciones muy altas, aunque ARR modesto → posible sobrevaluación.
- Se observa diversificación geográfica creciente, aunque EE.UU. sigue dominando.

---

## 📌 Recomendaciones Finales

1. Observar el ratio Valuation / ARR para evitar sobrevaluaciones.
2. Analizar industrias emergentes con alta eficiencia (ARR alto y funding bajo).
3. Priorizar startups con múltiples inversores top y rápido crecimiento ARR.

---

## 📁 Entregables

- `reporte_saas_2025.md` (este archivo)
- `analisis_saas_2025.ipynb`
- Carpeta `visualizaciones/` con gráficos `.png` y `.html`
- `data_limpio.csv` (proporcionado por el usuario)

---
