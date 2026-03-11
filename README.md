# Análisis Cuantitativo del S&P 500: Dinámica de Mercado y Tendencias Tecnológicas (2015-2025)

![Status](https://img.shields.io/badge/Status-Completado-success)
![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Analysis](https://img.shields.io/badge/Sector-Financiero-gold)

Este proyecto presenta un análisis integral de datos históricos del índice **S&P 500**, centrándose en la extracción de señales de mercado, evaluación de riesgos asimétricos y el impacto del sector tecnológico en la economía global. Mediante un pipeline de datos robusto (**ELT**), se procesaron más de 1.2 millones de registros para transformar datos crudos en inteligencia financiera accionable.

## 🎯 Objetivos y Preguntas de Negocio
El análisis se diseñó para resolver interrogantes críticos de inversión:
1. **Dominancia de Liquidez:** ¿Cómo influyen las empresas "Big Tech" en el volumen transaccional total del índice?
2. **Análisis de Riesgo de Cola (Tail Risk):** ¿Cuál es la probabilidad de eventos extremos en activos de alta volatilidad como Amazon y Tesla?
3. **Correlación Sectorial:** ¿Existe una dependencia excesiva del índice hacia el sector tecnológico en la última década?

## 🛠️ Stack Tecnológico
* **Lenguaje:** Python (Pandas, NumPy).
* **Visualización:** Plotly, Matplotlib, Seaborn.
* **Ingeniería de Datos:** Pipeline ELT (Extracción, Limpieza y Transformación).
* **Entorno:** Jupyter Notebooks.
* **BI:** Dashboard interactivo desarrollado en **Streamlit**.

## 📈 Hallazgos Clave (Insights)
* **Anclas de Liquidez:** Se identificó que **Tesla y Apple** actúan como los principales motores de liquidez. Su volumen de transacciones diario supera sistemáticamente al promedio del índice, funcionando como indicadores clave del sentimiento institucional.
* **Asimetría de Riesgo:** El análisis de *Tail Risk* en **Amazon** reveló que los eventos de pérdida extrema presentan una recuperación más lenta comparada con otros sectores, sugiriendo una alta sensibilidad a factores macroeconómicos negativos.
* **Concentración de Mercado:** Se confirmó una dependencia crítica: el **Top 5** de empresas del sector tecnológico determina aproximadamente el **25% de la dirección del índice**, lo que implica un riesgo de concentración para inversores pasivos.

## 📁 Estructura del Repositorio
```text
├── data/               # Archivos CSV con los datos procesados
├── notebooks/          # Proyecto_Analisis_SP500_Final.ipynb (Código principal)
├── scripts/            # Funciones de limpieza y métricas estadísticas
├── images/             # Gráficos exportados y capturas del dashboard
├── requirements.txt    # Librerías necesarias para ejecutar el proyecto
└── README.md           # Documentación principal

## 📊 Dashboard Interactivo

(Espacio para link)

## 🛠️ Instalación y Uso

1. **Clonar el repositorio:** git clone [https://github.com/tu-usuario/nombre-de-tu-repo.git](https://github.com/tu-usuario/nombre-de-tu-repo.git)

2. **Instalar las dependencias necesarias:** pip install -r requirements.txt

3. **Ejecutar el notebook ubicado en la carpeta `/notebooks`.

## 🚀 Próximos Pasos (Roadmap)

* **Machine Learning:** Implementar modelos LSTM para la predicción de volatilidad a corto plazo.

* **NLP:** Integrar análisis de sentimiento de noticias financieras para anticipar movimientos de mercado.

* **Automatización:** Migrar el flujo de datos a una arquitectura en la nube (AWS/Google Cloud) para actualizaciones en tiempo real.

---

**Autor:** Andres Camilo Mora Gomez

**Rol:** Data Analyst

