# Proyecto 2 – Análisis de Rentabilidad de Clientes en una Tienda Online

## 📋 Descripción general
El propósito de este proyecto es analizar la rentabilidad de los clientes de una tienda online, identificar patrones de comportamiento y determinar qué segmentos generan mayor valor a largo plazo (LTV).  
Se aplicaron métricas de retención, frecuencia de compra y análisis RFM para evaluar la fidelidad y la rentabilidad de los distintos grupos de clientes.

---

## 🎯 Objetivos
- Calcular el **Lifetime Value (LTV)** de los clientes.  
- Analizar el **CAC (Costo de Adquisición de Clientes)** y su relación con el retorno.  
- Identificar patrones de compra y segmentar usuarios según su valor.  
- Proponer estrategias para optimizar el presupuesto de marketing y fidelización.

---

## 🧮 Datos utilizados
**Archivos:** `orders_us.csv` y `visits_us.csv`

Columnas principales:
- user_id  
- order_id  
- revenue  
- date  
- source_id (canal de adquisición)

Periodo analizado: 1 año de actividad comercial.

---

## 🧰 Herramientas y librerías
- Python  
- pandas, numpy, datetime  
- matplotlib, seaborn  
- Jupyter Notebook  

---

## 📊 Etapas del análisis
1. Limpieza y transformación de datos de ventas y tráfico.  
2. Cálculo de métricas principales: **CAC, LTV, Retention Rate**.  
3. Segmentación de usuarios según frecuencia y valor.  
4. Visualización de tendencias por canal de adquisición.  
5. Análisis de rentabilidad por cohortes.  
6. Recomendaciones estratégicas.

---

## 🔍 Resultados principales
- Los clientes provenientes de **tráfico orgánico** tuvieron un **LTV 40 % mayor** que los de pago.  
- El canal de adquisición con mejor retorno fue **SEO**, con un **CAC 25 % menor**.  
- La tasa de retención promedio fue del **45 % a 3 meses**.  
- Se identificaron cohortes de clientes leales con compras recurrentes en promociones mensuales.

---

## 💡 Conclusiones y recomendaciones
- Reforzar la inversión en canales orgánicos y de referidos.  
- Diseñar estrategias de remarketing para los primeros 90 días de adquisición.  
- Implementar dashboards de seguimiento de LTV/CAC en tiempo real.  
- Priorizar campañas con mejor ratio LTV:CAC (>3:1).

---

## 🗂 Estructura del repositorio
