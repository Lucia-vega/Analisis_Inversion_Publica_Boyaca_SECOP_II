# 📊 Análisis de Inversión Pública en Boyacá — SECOP II (2023–2026)

**Analista:** Elva Lucía Vega Díaz  
**Herramientas:** Python · Pandas · Seaborn · Matplotlib · API Socrata · Jupyter Notebook  
**Periodo analizado:** Enero 2023 – Abril 2026  
**Registros procesados:** +186,000 contratos públicos

---

## 🎯 Objetivo

Analizar la distribución de la inversión pública en el departamento de Boyacá durante el periodo 2023–2026, identificando patrones de asignación presupuestal, concentración del gasto, estacionalidad en la contratación y posibles ineficiencias administrativas.

---

## 🔍 Principales Hallazgos

### 1. Alta concentración geográfica de la inversión
Tunja lidera la inversión departamental con aproximadamente **$7.7 billones de pesos**, superando casi 5 veces al segundo municipio (Sogamoso). Esto evidencia una fuerte centralización de los recursos en la capital, asociada a proyectos de gran escala y contratación institucional.

### 2. Estacionalidad marcada en la ejecución del gasto
Se identifica un patrón recurrente donde la mayor parte de la contratación se concentra en el **último trimestre del año** (especialmente octubre), lo cual sugiere acumulación de procesos hacia el cierre fiscal y riesgo de cuellos de botella administrativos.

### 3. Aceleración atípica en 2026
El primer trimestre de 2026 registra el **nivel más alto de ejecución temprana** en los últimos años: **$2.61 billones adjudicados en 112 días** (equivalente a $23,342 millones/día). Este comportamiento atípico está asociado a una ejecución masiva bajo modalidad de **Régimen Especial**.

### 4. Predominio de contratación no competitiva
La inversión de 2026 está liderada por:
- Régimen Especial
- Contratación Directa

Esto requiere mayor seguimiento en términos de transparencia y control ciudadano.

### 5. Priorización en salud y educación
El gasto se concentra en la **red hospitalaria pública** (Hospital San Rafael de Tunja, Hospital Regional de Sogamoso y Duitama) y la **educación superior (UPTC)**, reflejando una priorización social del presupuesto departamental.

---

## 🗂️ Estructura del Proyecto

```
📁 Analisis_Inversion_Publica_Boyaca_SECOP_II
│
├── 📓 Analisis_Inversion_Publica_Boyaca_SECOP_II.ipynb   # Notebook principal
├── 📄 README.md
└── 📊 Contrataciones_2026_Boyaca.xlsx                    # Export de datos 2026
```

---

## ⚙️ Metodología

```
API Socrata (SECOP II)
        ↓
Extracción de +186,000 registros filtrados por Boyacá (2023–2026)
        ↓
ETL: conversión de tipos · limpieza de texto con Regex · imputación de nulos · normalización de unidades
        ↓
EDA: análisis temporal · concentración geográfica · distribución sectorial · detección de anomalías
        ↓
Visualización con Matplotlib / Seaborn
        ↓
Conclusiones y recomendaciones
```

---

## 🛠️ Tecnologías Utilizadas

| Categoría | Herramientas |
|---|---|
| Lenguaje | Python 3 |
| Manipulación de datos | Pandas, NumPy |
| Visualización | Matplotlib, Seaborn |
| Extracción de datos | API Socrata (sodapy) |
| Entorno | Jupyter Notebook |
| Control de versiones | Git, GitHub |

---

## 🚀 Cómo ejecutar el proyecto

1. Clona el repositorio:
```bash
git clone https://github.com/Lucia-vega/Analisis_Inversion_Publica_Boyaca_SECOP_II.git
```

2. Instala las dependencias:
```bash
pip install pandas numpy matplotlib seaborn sodapy jupyter
```

3. Abre el notebook:
```bash
jupyter notebook Analisis_Inversion_Publica_Boyaca_SECOP_II.ipynb
```

> **Nota:** La extracción de datos se conecta directamente a la API pública de SECOP II. No se requiere API key.

---

## 📌 Trabajo Futuro

- Implementar modelos de Machine Learning para detección automática de anomalías en precios contractuales
- Análisis predictivo de tendencias de gasto anual
- Dashboard interactivo en Power BI conectado a la misma API

---

## 👤 Autora

**Elva Lucía Vega Díaz**  
Analista de Datos | Ingeniería Industrial | Especialización en Analítica Estratégica de Datos (UPTC)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-luciavegadiaz-blue)](https://www.linkedin.com/in/luciavegadiaz)
[![GitHub](https://img.shields.io/badge/GitHub-Lucia--vega-black)](https://github.com/Lucia-vega)
[![Portafolio](https://img.shields.io/badge/Portafolio-Power%20BI-yellow)](https://bit.ly/Portafolio_Lucia_Vega)

