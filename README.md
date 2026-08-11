# ⛏️ Data Science aplicada a Metalurgia Extractiva

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-EDA-150458?logo=pandas)
![scikit--learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?logo=scikitlearn&logoColor=white)
![SQLite](https://img.shields.io/badge/SQL-SQLite-003B57?logo=sqlite)
![Excel](https://img.shields.io/badge/Datos-Excel-217346?logo=microsoftexcel&logoColor=white)

Portafolio de **Jhon Aguila** — ejercicios resueltos de análisis de datos aplicados a procesamiento de minerales: flotación, gravimetría, lixiviación (cianuración), clasificación con hidrociclones, oro refractario, balances metalúrgicos, machine learning y SQL.

> 📌 **Todos los datos son simulados.** Las minas, plantas y lugares (Cerro Kori, San Jacinto, Pukamayu, Valle Kollpa, Qorimayo, Wayra, Apumarca, Río Suri, Nevado Kachi, región de Altomayo) son **ficticios**. Ningún dato corresponde a operaciones reales.

---

## 📚 Ejercicios

| # | Nivel | Ejercicio | Temas | Datos |
|---|-------|-----------|-------|-------|
| 1 | 🟢 Básico | [Análisis exploratorio de leyes de oro](notebooks/01_basico_leyes_oro.ipynb) | pandas, estadística, distribución lognormal, ley ponderada | [Excel](data/01_leyes_mina_cerro_kori.xlsx) |
| 2 | 🟢 Básico | [Balance metalúrgico de flotación](notebooks/02_basico_balance_metalurgico.ipynb) | Fórmulas de dos productos, recuperación, ratio de concentración | [Excel](data/02_balance_flotacion_san_jacinto.xlsx) |
| 3 | 🟡 Intermedio | [Circuito Rougher–Scavenger–Cleaner](notebooks/03_intermedio_circuito_flotacion.ipynb) | Balance por nodos, recuperación por etapa, upgrade de ley | [Excel](data/03_circuito_flotacion_pukamayu.xlsx) |
| 4 | 🟡 Intermedio | [Hidrociclones: curva de partición](notebooks/04_intermedio_hidrociclones.ipynb) | d50 corregido, bypass, modelo de Plitt, `scipy.curve_fit` | [Excel](data/04_hidrociclon_valle_kollpa.xlsx) |
| 5 | 🔴 Avanzado | [Oro refractario: diagnóstico de recuperación](notebooks/05_avanzado_oro_refractario.ipynb) | Au <20 µm encapsulado en sulfuros, remolienda vs pre-oxidación, regresión | [Excel](data/05_oro_refractario_qorimayo.xlsx) |
| 6 | 🔴 Avanzado | [ML: predicción de recuperación de flotación](notebooks/06_avanzado_ml_recuperacion.ipynb) | Random Forest, train/test, importancia de variables, simulador | [Excel](data/06_flotacion_ml_wayra.xlsx) |
| 7 | 🔴 Avanzado | [SQL desde cero con datos de planta](notebooks/07_avanzado_sql_planta.ipynb) | SQLite, SELECT, WHERE, GROUP BY, JOIN, Pareto de paradas | [Excel](data/07_planta_turnos_apumarca.xlsx) |
| 8 | 🟢 Básico | [Concentración gravimétrica](notebooks/08_basico_gravimetria.ipynb) | Criterio de concentración, balance de mesa Wilfley, distribución de Au | [Excel](data/08_gravimetria_rio_suri.xlsx) |
| 9 | 🟡 Intermedio | [Cianuración: cinética de lixiviación](notebooks/09_intermedio_lixiviacion.ipynb) | Bottle roll, modelo de primer orden, consumo de NaCN, óxido vs sulfuro | [Excel](data/09_lixiviacion_nevado_kachi.xlsx) |

Cada notebook es **autocontenido**: teoría → código comentado → gráficos → conclusiones metalúrgicas. Los gráficos ya están ejecutados y se ven directamente en GitHub.

## 🎯 Habilidades demostradas

- **Python / pandas** — lectura de Excel, limpieza, agrupaciones, vectorización
- **Metalurgia** — balances de masa, flotación multietapa, gravimetría, cinética de cianuración, clasificación, refractariedad del oro
- **Visualización** — matplotlib: series de tiempo, boxplots, curvas de partición, matrices de correlación
- **Machine Learning** — scikit-learn: regresión lineal, Random Forest, validación honesta
- **SQL** — consultas sobre base de datos de planta con SQLite
- **Estadística** — regresión, correlación, ajuste de modelos no lineales (Plitt)

## 🚀 Cómo ejecutar

```bash
git clone https://github.com/jhonaguila/data-science-metalurgia.git
cd data-science-metalurgia
pip install pandas numpy matplotlib scipy scikit-learn openpyxl jupyter
jupyter lab notebooks/
```

## 📁 Estructura

```
├── data/        # 9 archivos Excel con datos simulados
├── notebooks/   # 9 notebooks resueltos (básico → avanzado)
└── README.md
```

---
*Elaborado por Jhon Aguila · Ingeniería Metalúrgica + Data Science*
