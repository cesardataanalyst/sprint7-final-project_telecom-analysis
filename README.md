# sprint7-final-project_telecom-analysis

**ConnectaTel - Análisis del Comportamiento de Clientes**

**Objetivo del proyecto**

Analizar el comportamiento de los clientes de ConnectaTel mediante técnicas de análisis exploratorio de datos (EDA), con el fin de identificar patrones de consumo, detectar problemas de calidad en los datos, segmentar usuarios y proponer recomendaciones para mejorar la oferta de planes y las estrategias de retención.

**Datasets utilizados**

El proyecto utiliza tres archivos CSV:

•	plans.csv: información de los planes (precio, minutos, mensajes y GB incluidos).             •	users_latam.csv: datos de los clientes (edad, ciudad, plan, fecha de registro y churn). 
•	usage.csv: historial de uso de llamadas y mensajes de cada usuario.

**Etapas del análisis**

•	Carga y exploración de los datos. 
•	Identificación y limpieza de valores nulos, sentinels y fechas inválidas.
•	Creación de métricas de uso por usuario. 
•	Análisis estadístico y visualización de distribuciones. 
•	Detección de valores atípicos (outliers). 
•	Segmentación de clientes por nivel de uso y grupo de edad. 
•	Elaboración de conclusiones y recomendaciones para el negocio. 

**Cómo ejecutar el proyecto**

1.	Descarga o clona este repositorio.
2.	Abre el archivo .ipynb en Google Colab o Jupyter Notebook.
3.	Coloca los archivos plans.csv, users_latam.csv y usage.csv en la carpeta datasets (o ajusta las rutas de lectura).
4.	Ejecuta todas las celdas en orden.
	
**Guía de reproducción**

El análisis puede reproducirse ejecutando el notebook de principio a fin. El flujo incluye la carga de datos, limpieza, análisis exploratorio, segmentación de clientes y generación de insights para ConnectaTel.

**Herramientas utilizadas**

•	Python
•	Pandas
•	NumPy
•	Matplotlib
•	Seaborn
•	Jupyter Notebook / Google Colab
