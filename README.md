# 📊 Proyecto: Análisis de Churn - Telecom X

Este proyecto forma parte de la estrategia de retención de clientes de **Telecom X**. El objetivo principal es identificar los factores críticos que influyen en la tasa de cancelación (Churn) para permitir que el equipo de Data Science desarrolle modelos predictivos y estrategias de fidelización efectivas.

## 📋 Tabla de Contenidos
1. [Descripción del Proyecto](#descripción-del-proyecto)
2. [Tecnologías Utilizadas](#tecnologías-utilizadas)
3. [Metodología (ETL)](#metodología-etl)
4. [Insights Principales](#insights-principales)
5. [Recomendaciones Estratégicas](#recomendaciones-estratégicas)

---

## 🚀 Descripción del Proyecto
Telecom X ha detectado una fuga de clientes significativa. Como parte del equipo de análisis, este repositorio documenta el **Análisis Exploratorio de Datos (EDA)** realizado para transformar datos brutos en información estratégica.

**Objetivos del desafío:**
* Extraer y procesar datos eficientemente desde una API.
* Aplicar limpieza y transformación de datos (ETL).
* Identificar patrones de comportamiento que preceden a la cancelación del servicio.

## 🛠️ Tecnologías Utilizadas
* **Python 3.x**
* **Pandas & NumPy:** Procesamiento y limpieza de datos.
* **Matplotlib & Seaborn:** Visualización de datos.
* **Google Colab:** Entorno de desarrollo colaborativo.



---

## 🔍 Insights Principales
Tras el análisis exploratorio, se han extraído las siguientes conclusiones clave:

1.  **Fuga Temprana:** Existe una tasa crítica de abandono en los **primeros 6 meses** de relación con el cliente. Si el cliente supera el primer año, la probabilidad de churn disminuye drásticamente.
2.  **Modalidad de Contrato:** El contrato **"Mes a Mes"** es el mayor predictor de abandono, comparado con contratos a largo plazo que presentan mayor estabilidad.
3.  **Valor en Riesgo:** Los clientes que cancelan tienen, en promedio, **gastos mensuales superiores** a los clientes leales, lo que impacta directamente en el ARPU (Average Revenue Per User).
4.  **Servicios de Valor Añadido:** Los clientes sin servicios de **Seguridad en Línea** y **Soporte Técnico** tienen una propensión al abandono mucho mayor.
5.  **Brecha Digital/Etaria:** Se identificó una mayor tasa de evasión en el segmento de **Adultos Mayores**.



---

## 💡 Recomendaciones Estratégicas
Basado en los hallazgos, se sugieren las siguientes acciones para el equipo de negocio:

* **Incentivos de Permanencia:** Crear promociones para migrar clientes de planes mensuales a anuales.
* **Seguimiento personalizado:** Reforzar la atención al cliente durante el primer trimestre de contrato para reducir el abandono temprano.
* **Ofertas de Seguridad:** Ofrecer servicios de Seguridad y Soporte como parte de los paquetes básicos, ya que actúan como fuertes retenedores.
* **Optimización de Pagos:** Investigar las fricciones en el método de **Cheque Electrónico**, donde se concentra un alto volumen de cancelaciones.

---

## 🏗️ Cómo ejecutar el proyecto
1.  Clona este repositorio:
    ```bash
    git clone [https://github.com/tu-usuario/telecom-churn-analysis.git](https://github.com/tu-usuario/telecom-churn-analysis.git)
    ```
2.  Instala las librerías necesarias:
    ```bash
    pip install pandas numpy matplotlib seaborn requests
    ```
3.  Abre el notebook `Challenge_TELECOMX1.ipynb` en tu entorno preferido (Jupyter o Google Colab).

---

**Desarrollado por:** [ValentinaQuinteroC]  
**Proyecto:** Challenge Telecom X - Retención de Clientes
