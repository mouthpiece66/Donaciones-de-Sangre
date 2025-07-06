# Donaciones-de-Sangre

## Detección de valores atípicos en donaciones de sangre
Este proyecto fue desarrollado para profundizar habilidades en análisis y manipulación de datos orientados al sector salud. Se utilizaron datos reales del "Blood Transfusion Service Center" con el objetivo de identificar valores atípicos en variables clave que describen el comportamiento de donantes.

Objetivo: Detectar perfiles atípicos de donantes de sangre mediante técnicas estadísticas y visualización exploratoria. Esto permite mejorar la segmentación y diseñar estrategias más efectivas para campañas de donación.

Tecnologías utilizadas
•	Python – lenguaje principal para análisis de datos
•	Pandas – manipulación de datos
•	Seaborn – visualización exploratoria (pairplot)
•	Matplotlib – apoyo en gráficos personalizados
•	Scikit-learn – escalado de variables (StandardScaler)
•	Método estadístico IQR – detección de valores atípicos

Conclusiones
•	Las variables Monetary y Frequency concentran la mayoría de los outliers, lo que indica que algunos donantes contribuyen significativamente más que otros.
•	El escalado de variables permite una mejor comparación entre métricas con diferentes unidades.
•	Estos hallazgos pueden ayudar a identificar donantes recurrentes con alto valor estratégico para campañas específicas.
