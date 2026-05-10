# 📊 ConnectaTel - Telecom Customer Usage Analysis

## 📌 Objetivo del Proyecto

Este proyecto tiene como objetivo analizar el comportamiento de uso de clientes de telecomunicaciones en México y Colombia utilizando información de planes, usuarios y consumo real de llamadas y mensajes.

El análisis busca identificar patrones de uso, detectar comportamientos atípicos, segmentar usuarios y generar recomendaciones comerciales basadas en datos.

---

# 🛠️ Herramientas Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 📂 Datasets Utilizados

El proyecto utiliza tres fuentes principales de información:

| Dataset | Descripción |
|---|---|
| plans.csv | Información de planes móviles y beneficios |
| users_latam.csv | Datos demográficos y de registro de usuarios |
| usage.csv | Historial de llamadas y mensajes |

---

# 🔎 Etapas del Análisis

## 1. Carga y exploración de datos
- Revisión de estructura
- Tipos de datos
- Exploración inicial

## 2. Limpieza y calidad de datos
- Detección de nulos
- Corrección de sentinels
- Tratamiento de fechas inválidas
- Validación de columnas

## 3. Ingeniería y agregación
- Construcción de métricas por usuario
- Total de llamadas
- Total de mensajes
- Total de minutos

## 4. Análisis estadístico
- Medidas descriptivas
- Distribuciones
- Comparación por tipo de plan

## 5. Visualización de datos
- Histogramas
- Boxplots
- Countplots
- Análisis de distribuciones

## 6. Detección de outliers
- Método IQR
- Identificación de usuarios extremos

## 7. Segmentación de clientes
- Segmentación por edad
- Segmentación por nivel de uso

## 8. Insights ejecutivos
- Recomendaciones comerciales
- Oportunidades de negocio
- Patrones de comportamiento

---

# 📈 Visualizaciones Principales

## Distribución de mensajes por plan

![Mensajes](images/hist_mensajes_plan.png)

---

## Distribución de minutos por plan

![Minutos](images/hist_minutos_plan.png)

---

## Boxplot de minutos de llamada

![Boxplot](images/boxplot_minutos.png)

---

## Segmentación de clientes por nivel de uso

![Segmentos](images/countplot_segmentos.png)

---

# 📊 Principales Hallazgos

- La mayoría de usuarios pertenece al segmento de uso medio.
- Los clientes Premium presentan mayor consumo de mensajes y minutos.
- Se identificaron usuarios con consumo extremo que podrían representar clientes de alto valor.
- Existen diferencias claras de comportamiento según edad y plan contratado.
- Se detectaron problemas de calidad de datos como sentinels, fechas futuras y valores faltantes.

---

# 💡 Recomendaciones de Negocio

- Diseñar planes personalizados según nivel de uso.
- Crear estrategias de upselling para usuarios de uso medio.
- Implementar validaciones automáticas de calidad de datos.
- Desarrollar campañas diferenciadas por segmento etario.
- Monitorear usuarios de consumo extremo para oportunidades premium.

---
# ▶️ Cómo Ejecutar el Proyecto

## 1. Clonar el repositorio

Clone the repository:

```bash
git clone https://github.com/TDRenteria/connectatel-telecom-analysis.git
cd connectatel-telecom-analysis

## 2. Instalar dependencias

```bash
pip install pandas numpy matplotlib seaborn
```

## 3. Abrir el notebook

Abrir el archivo:

```text
notebooks/connectatel_analysis.ipynb
```

Puedes ejecutarlo en:
- Jupyter Notebook
- VS Code
- Google Colab

---

# 🔁 Guía de Reproducción

1. Descargar o clonar el repositorio.
2. Verificar instalación de librerías.
3. Colocar los datasets en la carpeta correspondiente.
4. Ejecutar el notebook en orden.
5. Revisar visualizaciones e insights finales.

---

# 👨‍💻 Autor

Tito Daniel Renteria Velez
