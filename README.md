📋 Descripción general

Este proyecto forma parte del programa de análisis de datos de TripleTen.
El objetivo fue evaluar hipótesis de negocio y analizar un experimento A/B para identificar oportunidades que aumenten los ingresos de una tienda en línea.

El análisis incluyó la priorización de hipótesis (ICE y RICE), el procesamiento de datos de visitas y pedidos, y la evaluación estadística de los resultados para determinar la validez del experimento.

🎯 Objetivos del proyecto

Priorizar hipótesis utilizando los frameworks ICE y RICE.

Analizar el comportamiento de usuarios en el experimento A/B.

Calcular métricas clave: ingresos acumulados, tamaño promedio de pedido y tasa de conversión.

Detectar anomalías y evaluar significancia estadística de los resultados.

Emitir una recomendación final sobre la prueba y su continuidad.

🧮 Dataset utilizado

hypotheses_us.csv → Contiene las hipótesis con sus valores Reach, Impact, Confidence y Effort.

orders_us.csv → Registro de pedidos (ID de transacción, usuario, fecha, ingresos, grupo de prueba).

visits_us.csv → Número de visitas por fecha y grupo (A/B).

📊 Tamaño total de los datos: 7,000+ registros combinados
📅 Periodo: varios meses de actividad comercial de la tienda

🧰 Tecnologías y herramientas
Categoría	Herramientas
Lenguaje	Python
Librerías	pandas, numpy, matplotlib, scipy
Visualización	matplotlib, seaborn
Entorno	Jupyter Notebook
Control de versiones	Git, GitHub
📈 Visualizaciones clave

Ingreso acumulado por grupo (A/B)

Diferencia relativa del tamaño de pedido promedio

Tasa de conversión diaria

Dispersión de número de pedidos por usuario

Detección de anomalías en precios de pedidos

🔍 Principales hallazgos

El grupo B presentó una tasa de conversión superior al grupo A (~+14%).

No hubo diferencias significativas en el tamaño promedio del pedido, pero sí en número de pedidos.

El modelo RICE modificó las prioridades respecto al ICE, destacando hipótesis con mayor alcance y menor esfuerzo.

Se identificaron outliers que afectaban el promedio y fueron filtrados antes del test final.

Con base en la evidencia, se recomendó detener la prueba y declarar ganador al grupo B.

📊 Métricas destacadas
Indicador	Valor
Diferencia relativa en conversión	+14%
P-Value (conversión)	< 0.05
Incremento esperado en ingresos	+10–12%
Tiempo total de análisis	2 días
🧾 Conclusiones

El análisis demostró cómo la experimentación basada en datos permite validar hipótesis de negocio con precisión.
Aplicar métricas estructuradas como ICE/RICE ayuda a priorizar acciones de alto impacto y optimizar recursos.
