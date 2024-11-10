![image](https://github.com/user-attachments/assets/98622e2c-5814-4bf7-84d5-127531a5c2ef)

# ⚡ Proyecto Detección de Fraude Bancario para Pontia.tech ⚡
La empresa Pontia Bank S.L. necesita desarrollar un sistema de detección de transacciones fraudulentas.

Esta compañía, tramita miles de transacciones diarias de todos sus clientes entre las cuales se quiere diferenciar entre las que son fraudulentas de las que no lo son. Para ello, se han extraído las transacciones realizadas en los últimos 30 días (más de 6 millones) e identificado (manualmente) aquellas que son fraudulentas. 

Sin embargo, resulta muy costoso e ineficiente necesitar una revisión manual de la transacción para su validación, por lo que se quiere automatizar esta tarea. 

La empresa carece de un sistema adecuado para almacenar y gestionar sus datos de las transacciones, por lo que no solo necesita ser capaz de identificar el fraude, sino que es necesario llevar a cabo una transformación digital completa alrededor de estos datos: empezando por su almacenamiento, pasando por su procesamiento y finalizando con la generación de resultados y cálculo de KPIs útiles para el negocio.

## 🎯 Objetivos:
### 💡 Diseño e Implementación del Modelo Relacional
•	Análisis de los archivos JSON: Revisar los archivos (alarma_fraude.json, balances.json, etc.) para entender la estructura de los datos.  
•	Diseño del modelo de datos: Crear un esquema relacional en SQL, identificando entidades, relaciones, claves primarias y claves foráneas.  
•	Implementación en SQL: Crear el modelo en una base de datos MySQL e insertar los datos.  
•	Cálculo de KPIs: Crear las consultas SQL necesarias para obtener los KPIs solicitados por el proyecto, como la media diaria de las transacciones, los clientes que han transferido más y menos, y el balance neto de los clientes.  


### ⭕ Identificación de Errores e Incidencias en los Datos
•	Definición de reglas de negocio: Aplicar las reglas proporcionadas (por ejemplo, límite de 2000 € para retiradas diarias en efectivo, y no más de tres transferencias por hora).  
•	Detección de errores en SQL: Escribir sentencias SQL para detectar transacciones que violen estas reglas y analizar los resultados.  
•	Reporte de errores e incidencias: Documentar todos los datos erróneos encontrados, incluyendo valores nulos, y características comunes entre ellos.  

### 🖥️ Detección de Fraude con Machine Learning
•	Conexión de Python con la BBDD: Extraer datos de MySQL para el análisis.  
•	Análisis exploratorio de los datos: Realizar un análisis inicial (estadísticos, outliers, correlaciones) para entender la naturaleza de los datos y definir las características relevantes.  
•	Preparación de los datos: Limpiar el dataset según los problemas detectados.  
•	Entrenamiento y Evaluación de Modelos: Probar al menos dos modelos de ML (uno de ellos de deep learning) y documentar el rendimiento.  
•	Aplicación a datos en producción: Aplicar el modelo a datos no etiquetados y generar predicciones.  

### 🤖 Propuesta de Valor con IA Generativa

•	Investigación de casos de uso: Identificar procesos de Pontia Bank que podrían beneficiarse de IA Generativa.  
•	Propuesta de arquitectura de IA: Describir la solución técnica y los beneficios que aportaría a los procesos internos del banco.  
•	Documentación: Crear un documento detallado que exponga los casos de uso y la arquitectura propuesta, con métricas que justifiquen la implementación.  

### ✅ Presentación de Resultados

•	Dashboard de KPIs: Utilizar Power BI o Tableau para diseñar dashboards que visualicen los KPIs clave, resultados de fraude y análisis de incidencias.  
•	Informe ejecutivo del proyecto: Crear un resumen que incluya los objetivos, el modelo relacional, la limpieza de datos, la metodología de ML, y la comparación de modelos.  
•	Documentación final y presentación: Organizar todo el trabajo en un archivo ejecutable (Jupyter Notebook o similar) y preparar la presentación del proyecto.  
