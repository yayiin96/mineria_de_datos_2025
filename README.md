# 🌍 Análisis Global de Calidad del Aire y Clima Actual con Python

Este proyecto explora datos globales de contaminación atmosférica y clima en tiempo real usando Python, Google BigQuery y OpenWeather API. Se generan visualizaciones interactivas para identificar zonas críticas en el mundo afectadas por partículas contaminantes como **PM2.5, PM10, NO₂, CO, SO₂ y O₃**.

---

## 📊 Herramientas y Librerías

- `pandas`, `numpy` — manejo y análisis de datos
- `matplotlib`, `seaborn` — visualización estática
- `folium` + `HeatMap` — visualización geoespacial interactiva
- `google-cloud-bigquery`, `google-auth` — consulta de datos públicos de calidad del aire desde BigQuery
- `requests` — extracción de datos climáticos actuales desde OpenWeather API

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

```
📁 solemne1_jose_soto
│
├── solemne1_jose_soto.ipynb             # Notebook principal con el análisis
├── mapa_pm25_mundial_ultimo_anio.html  # Mapa interactivo generado
├── README.md                            # Descripción del proyecto
├── requirements.txt                     # Dependencias del proyecto
```

---

## ▶️ Cómo usar este repositorio

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/solemne1_jose_soto.git
   cd solemne1_jose_soto
   ```

2. Instala las dependencias:
   ```bash
   pip install -r requirements.txt
   ```

3. Ejecuta el notebook:
   ```bash
   jupyter notebook solemne1_jose_soto.ipynb
   ```

---

## 📦 Requisitos

Instala las dependencias necesarias:

```bash
pip install -r requirements.txt
```

---

## 🧠 Autor

**Jose Luis Soto Pezoa**  
Estudiante de Ingeniería Física, entusiasta del análisis de datos y la física de partículas.

---

## 📝 Licencia

Este proyecto es de uso educativo y académico.
