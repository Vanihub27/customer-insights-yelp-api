# 🍽️ Customer 360° Analytics
### Integración de datos de usuarios y restaurantes para generar insights de negocio

## 📌 Descripción

Este proyecto simula un desafío técnico para el rol de Data Scientist Jr. en una empresa ficticia de marketing analítico (InsightReach).

El objetivo consiste en integrar múltiples fuentes de datos para comprender el comportamiento de los clientes, enriquecer la información mediante la API de Yelp y generar recomendaciones estratégicas para optimizar campañas de marketing y segmentación comercial.

Durante el proyecto se aplicaron técnicas de limpieza, integración, análisis exploratorio de datos (EDA) y comunicación de resultados, utilizando Python y diversas librerías de análisis de datos.

---

## 🎯 Objetivos

- Analizar una base de usuarios con más de 30.000 registros.
- Limpiar y transformar datos para mejorar su calidad.
- Integrar información proveniente de la API de Yelp.
- Analizar patrones de consumo y preferencias alimenticias.
- Identificar oportunidades comerciales mediante visualizaciones e insights.
- Elaborar recomendaciones estratégicas basadas en evidencia.

---

## 🛠 Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Requests
- FuzzyWuzzy
- Git
- GitHub

---

## 📂 Estructura del proyecto

```
Fintech_AnalisisComportamientoDelCliente/

│
├── Avances/
│   ├── Avance_1
│   ├── Avance_2
│   └── Avance_3
│
├── Documentación/
│
└── README.md
```

---

# ⚙ Flujo de trabajo

## 1️⃣ Limpieza y exploración del dataset

Se realizó un análisis exploratorio del dataset inicial, identificando inconsistencias, valores faltantes y registros fuera de rango.

Principales tareas:

- Exploración de variables
- Limpieza de datos
- Imputación de valores
- Corrección de inconsistencias
- Normalización

Output:

- Dataset limpio
- Dataset filtrado para Chicago

---

## 2️⃣ Integración con API Yelp

Se consumió la API de Yelp para enriquecer la información con datos reales de restaurantes.

Información obtenida:

- Categorías
- Rating
- Precio
- Ubicación
- Cantidad de reseñas

Posteriormente se normalizó la respuesta JSON y se construyó un nuevo dataset para el análisis.

---

## 3️⃣ Integración y análisis

Finalmente se combinaron ambas fuentes de datos para analizar:

- Perfil demográfico
- Preferencias alimenticias
- Distribución geográfica
- Oferta gastronómica
- Demanda potencial
- Oportunidades comerciales

---

# 📊 Principales hallazgos

✔ Los usuarios premium presentan mayor gasto y frecuencia de visitas.

✔ Los usuarios jóvenes muestran preferencias por restaurantes fast casual.

✔ Existen zonas donde la demanda de restaurantes veganos supera la oferta.

✔ La integración de datos permitió identificar oportunidades para campañas de marketing segmentadas.

---

# 💼 Recomendaciones de negocio

A partir del análisis se propusieron estrategias como:

- Segmentación por ingresos.
- Segmentación por edad.
- Segmentación por preferencias alimenticias.
- Campañas geolocalizadas.
- Programas de fidelización.
- Recomendaciones personalizadas.

---

# 📈 Competencias demostradas

Durante el desarrollo del proyecto se aplicaron:

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Data Integration
- API Consumption
- Feature Engineering
- Data Visualization
- Business Intelligence
- Storytelling con datos
- Recomendaciones estratégicas

---

# Esquema del flujo del proyecto

                📄 Dataset inicial
              (30.000 usuarios)
                      │
                      ▼
          🧹 Limpieza y EDA
                      │
                      ▼
          📊 Dataset limpio
                      │
                      │
                      ├────────────────────────────┐
                      │                            │
                      ▼                            ▼
              🌐 API Yelp                Restaurantes Chicago
                      │
                      ▼
           📥 Extracción de datos
                      │
                      ▼
          🧹 Limpieza y transformación
                      │
                      ▼
            📊 Dataset Yelp limpio
                      │
                      ▼
        🔗 Integración de ambas fuentes
                      │
                      ▼
      📈 Análisis y visualización de datos
                      │
                      ▼
        💡 Insights de negocio
                      │
                      ▼
   🎯 Recomendaciones de segmentación



---



# 📄 Documentación

El repositorio incluye:

- Informe técnico completo.
- Documento de recomendaciones estratégicas.
- Notebooks de desarrollo.
- Datasets procesados.

---

# 🚀 Próximas mejoras

- Dashboard interactivo con Power BI o Plotly.
- Modelos de segmentación mediante Clustering.
- Sistema de recomendación personalizado.
- Modelos predictivos para gasto y frecuencia de visitas.

---

# 👩‍💻 Autora

**Vanina Cavallin**

Dra. en Ciencias Biológicas

Data Scientist | Data Analyst

LinkedIn: https://linkedin.com/in/vanina-cavallin
