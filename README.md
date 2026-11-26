# 💡 RappiPlus: De datos a decisiones de negocio

![Estado](https://img.shields.io/badge/Estado-Completado-2ea44f?style=for-the-badge)
![Tipo](https://img.shields.io/badge/Proyecto-Análisis_de_datos-295F98?style=for-the-badge)

> Análisis integral del servicio de suscripción **RappiPlus**: rentabilidad, conversión, retención y experimentación A/B, comunicado en dashboards ejecutivos.

---

## 📌 Contexto y objetivo

**RappiPlus** es un servicio de suscripción dentro del ecosistema de Rappi, diseñado para aumentar la frecuencia de compra y el valor generado por usuario.

🎯 **Objetivo:** entender el desempeño del servicio y detectar oportunidades de mejora concretas a partir de los datos.

## ❓ Preguntas clave

1. ¿Los usuarios realmente compran más?
2. ¿El modelo está generando ganancias?
3. ¿Se están perdiendo oportunidades en el proceso de compra?

## 🛠️ Herramientas

![Python](https://img.shields.io/badge/Python-357ebd?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-357ebd?style=for-the-badge&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-357ebd?style=for-the-badge&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-357ebd?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-357ebd?style=for-the-badge)
![SQL](https://img.shields.io/badge/SQL_(CTEs)-357ebd?style=for-the-badge)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

**Habilidades aplicadas:** limpieza de datos · transformación · análisis de rentabilidad · funnel de conversión · retención por cohortes · experimentación A/B · visualización y storytelling con datos

## 🗺️ Flujo del proyecto

1. 📥 **Datos crudos**
2. 🧹 **Preparación y calidad de datos** con Python
3. 💰 **Análisis de rentabilidad** del negocio con Python
4. 🔻 **Análisis del funnel de conversión** con SQL
5. 📅 **Análisis de retención por cohortes** con SQL
6. 🧪 **Evaluación de impacto (experimentación A/B)** con Python
7. 📊 **Construcción del dashboard** y comunicación de insights con Power BI

## 📂 Datasets

| Etapa | Archivo |
|---|---|
| Preparación y calidad de datos | `rappiplus_orders_raw.csv` |
| | `rappiplus_catalog.csv` |
| | `rappiplus_marketing_spend.csv` |
| Experimentación A/B | `experiment_checkout.csv` |

## 🔍 Resultados del análisis

### 1. Preparación y calidad de datos
Procesamiento de datos: limpié y validé los datos, revisando su calidad antes de cualquier análisis.

### 2. Funnel de conversión y retención (SQL)
Con **SQL (CTEs)** construí embudos multietapa para analizar conversión y retención por cohortes.

- 🔻 La mayor pérdida de usuarios ocurre entre `add_to_cart` y `begin_checkout`: **2,339 usuarios**.
- 📉 La conversión final del funnel es de **2.94 %**.
- 🔁 La retención se mantiene estable (**40 %–44 %**) en las cohortes de enero a mayo de 2025.

### 3. Experimento A/B (Python)
Evalué el impacto del tratamiento con **Pandas, Matplotlib y SciPy**.

- ⚖️ Sin mejora estadísticamente significativa en la conversión (**16.29 %** vs. **15.69 %**) ni en la duración de sesión.
- 🖥️ Desktop convierte más que mobile (**18.29 %** vs. **13.65 %**).

### 4. Dashboards en Power BI
Construí **dos dashboards interactivos** con comunicación ejecutiva basada en el método **C-F-I** (Contexto, Hallazgo, Implicación).

> 🖼️ _Overview_`![Dashboard 1](Overview.png)`
> 🖼️ _Análisis detallado_`![Dashboard 2](Análisis detallado.png)`

## ✅ Recomendaciones accionables

1. **Investigar el abandono posterior al carrito**, donde se concentra la mayor pérdida de usuarios.
2. **Analizar el funnel mobile** para cerrar la brecha de conversión frente a desktop.
3. **No basar las decisiones sobre el tratamiento únicamente en la duración de sesión**, ya que no mostró un efecto significativo.

## 📁 Contenido del repositorio

- `S12 Estudiante_Proyecto_Final.ipynb`: notebook principal con limpieza, EDA, distribuciones, outliers, consultas SQL y conclusiones.

## ▶️ Cómo reproducir el análisis

1. Abre `S12 Estudiante_Proyecto_Final.ipynb` en GitHub y haz clic en **Open in Colab**
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github.com/egomez-DA/Proyecto-Final-RappiPlus-De-datos-a-decisiones-de-negocio/blob/main/S12_Estudiante_Proyecto_Final.ipynb)
3. Ejecuta las celdas en orden.
4. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público, según corresponda.

---

👤 **Autor:** [egomez-DA](https://github.com/egomez-DA) · [LinkedIn](https://linkedin.com/in/erika-gómezle)
