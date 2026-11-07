# Segmentación de Clientes en E-commerce (Olist) - Machine Learning

## 📊 Descripción del Proyecto
Este proyecto implementa un pipeline completo de Análisis Exploratorio de Datos (EDA) y Machine Learning no supervisado utilizando Python y Pandas. El objetivo principal es segmentar a más de 96.000 clientes de la plataforma brasileña **Olist** basándose en el modelo **RFM (Recencia, Frecuencia y Monetario)** para optimizar estrategias comerciales y de marketing.

## 🛠️ Tecnologías y Librerías Utilizadas
* **Lenguaje:** Python 3
* **Manipulación y Análisis:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (K-Means Clustering, StandardScaler)
* **Visualización:** Matplotlib, Seaborn

## 🔍 Fases del Proyecto
1. **Limpieza y Unificación:** Cruce de bases de datos relacionales (pedidos, clientes y pagos) y tratamiento de valores nulos.
2. **Construcción de Métricas RFM:** Cálculo automatizado de la Recencia (días desde la última compra), Frecuencia (volumen de pedidos) y Valor Monetario por cliente único.
3. **Modelado (K-Means):** Aplicación de transformación logarítmica para manejo de *outliers*, escalado de variables y clustering en 4 perfiles de clientes diferenciados (VIPs, recientes, inactivos y ocasionales).
4. **Visualización y Storytelling:** Gráficos de dispersión optimizados para la toma de decisiones de negocio.

## 📈 Principales Hallazgos (Insights)
* **Clúster VIP (Fieles):** Representan el núcleo más rentable con alta frecuencia y ticket elevado.
* **Clientes Inactivos / Churned:** Gran volumen de compradores que no han interactuado en más de 300 días, identificando una oportunidad directa para campañas de *re-engagement*.
