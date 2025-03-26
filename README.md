# Crear un README.md basado en el contenido del notebook, usando una estructura común para repositorios de análisis de datos

readme_content = """
# 🌍 Análisis Global de Calidad del Aire y Clima Actual con Python

Este proyecto explora datos globales de contaminación atmosférica y clima en tiempo real usando Python, Google BigQuery y OpenWeather API. Se generan visualizaciones interactivas para identificar zonas críticas en el mundo afectadas por partículas contaminantes como **PM2.5, PM10, NO₂, CO, SO₂ y O₃**.

---

## 📊 Herramientas y Librerías

- `pandas`, `numpy` — manejo y análisis de datos
- `matplotlib`, `seaborn` — visualización estática
- `folium` + `HeatMap` — visualización geoespacial interactiva
- `Google BigQuery` — consulta de datos públicos de calidad del aire
- `OpenWeather API` — extracción de datos meteorológicos actuales

---

## 🌐 Datos Utilizados

1. **Global Air Quality**: extraído desde el dataset público `bigquery-public-data.openaq.global_air_quality`.
2. **Clima actual**: recuperado mediante `OpenWeather API` para ubicaciones específicas.

---

## 🗺️ Visualización principal

Se genera un mapa mundial interactivo (`.html`) con una capa de calor (HeatMap) basada en la concentración de contaminantes atmosféricos. Se incluye una leyenda personalizada para facilitar la interpretación.

---

## 🧪 Clima Actual

Se consulta el clima en tiempo real (temperatura, humedad, lluvia, presión, viento, nubosidad) y se visualiza en un gráfico tipo `scatter`.

---

## 📂 Estructura del Proyecto

