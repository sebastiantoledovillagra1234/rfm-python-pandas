# rfm-python-pandas
Segmentación de clientes RFM automatizada con Python y pandas
# Optimización comercial: Segmentación de clientes (RFM) con Python
## Contexto del negocio
En canales B2B de consumo masivo, gestionar eficientemente la cartera de clientes es clave para la rentabilidad. Este proyecto migra un modelo de segmentación RFM (Recencia, Frecuencia, Monto) originalmente construido en Excel, hacia un entorno automatizado con **Python (pandas)**.
## Objetivos del proyecto
1. **Automatización:** reemplazar tablas dinámicas y fórmulas manuales de Excel por un flujo reproducible en código.
2. **Análisis de datos:** aplicar segmentación basada en reglas de negocio (RFM) para clasificar la cartera, estableciendo la base analítica para futuros modelos predictivos de fuga de clientes (Churn) y sistemas de recomendación (Cross-sell).
3. **Escalabilidad (en desarrollo):** sumar SQL para estructurar el flujo como un proceso ETL completo (Extract, Transform, Load).
##  Herramientas utilizadas
* **Lenguaje:** Python
* **Librerías:** pandas
* **Entorno:** Jupyter Notebook / VS Code
* **Próximamente:** SQL (SQLite)
## Estructura del repositorio
* `/data`: dataset de ejemplo (sintético, sin información real de clientes ni de empresas).
* `/notebooks`: cuadernos con la carga, limpieza y segmentación de datos usando pandas.
## Resultados (Fase 1 — Python/pandas)
Segmentación de una base de ejemplo (3.100+ registros) en 5 categorías RFM, con cálculo de promedio, suma y conteo por segmento ejecutado en 2 segundos reemplazando un proceso que antes tomaba varios minutos de trabajo manual en Excel.
## Próximos pasos (Fase 2)
* Migrar el cálculo de Recencia/Frecuencia/Monto desde transacciones crudas (no solo el resumen ya calculado).
* Incorporar SQL como capa de almacenamiento del resultado final.
* Armar el flujo completo como un mini proceso ETL.
