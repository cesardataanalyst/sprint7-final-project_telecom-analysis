# sprint7-final-project_telecom-analysis

# **ConnectaTel - Análisis del Comportamiento de Clientes**

## 📌 Contexto y problema de negocio
ConnectaTel es una empresa de telecomunicaciones que ofrece diferentes planes de servicios móviles.
Para comprender mejor el comportamiento de sus clientes, es necesario analizar la información relacionada con los planes contratados, las características de los usuarios y el uso de los servicios.
Este proyecto analiza los datos de clientes y consumo de ConnectaTel con el propósito de identificar patrones de uso, problemas de calidad de datos, segmentos de clientes y oportunidades de análisis que puedan apoyar decisiones relacionadas con la oferta de planes y las estrategias de retención.

## Objetivo del proyecto
Analizar el comportamiento de los clientes de ConnectaTel mediante técnicas de análisis exploratorio de datos (EDA), con el fin de identificar patrones de consumo, detectar problemas de calidad en los datos, segmentar usuarios y proponer recomendaciones para mejorar la oferta de planes y las estrategias de retención.

## Preguntas de análisis
El proyecto busca responder preguntas como:
- ¿Cómo se distribuyen los clientes según los planes contratados?
- ¿Cómo se comporta el uso de llamadas y mensajes entre los clientes?
- ¿Qué patrones de consumo pueden identificarse?
- ¿Existen diferencias de comportamiento entre grupos de clientes?
- ¿Qué problemas de calidad se encuentran en los datos?
- ¿Qué valores atípicos aparecen en las variables de uso?
- ¿Cómo pueden segmentarse los clientes según su nivel de uso?
- ¿Qué información puede apoyar decisiones relacionadas con los planes y la retención de clientes?


## 📊 Origen de los datos
El proyecto utiliza tres archivos CSV:

**plans.csv**
Contiene información relacionada con los planes disponibles, incluyendo:
- Precio
- Minutos incluidos
- Mensajes incluidos
- GB incluidos
  
**users_latam.csv**:
  Contiene información de los clientes, incluyendo:
  - Edad
  - Ciudad
  - Plan contratado
  - Fecha de registro
  - Información relacionada con churn

**usage.csv**: 
Contiene información sobre el uso de los servicios, incluyendo:
- Llamadas
- Mensajes-
- Duración de llamadas
  
Los datasets fueron utilizados conjuntamente para analizar las características de los clientes y su comportamiento de consumo.

 ## Herramientas utilizadas
 - Python
 - Pandas
 - NumPy
 - Matplotlib
 - Seaborn
 - Jupyter Notebook
 - Google Colab

## 🔎 Metodología
El análisis siguió un flujo de trabajo de exploración, preparación y análisis de datos.
### 1. Carga y exploración inicial
Se realizó una revisión inicial de los datasets para comprender:
- Estructura de los datos
- Variables disponibles
- Tipos de datos
- Distribución de la información
  
### 2. Calidad y limpieza de datos
Se revisaron diferentes aspectos de calidad, incluyendo:
- Valores nulos
- Valores sentinela
- Fechas inválidas
- Consistencia de los datos
- Valores atípicos
Posteriormente se realizaron las transformaciones necesarias para preparar los datos para el análisis.
### 3. Creación de métricas
Se construyeron métricas de uso por usuario para facilitar el análisis del comportamiento individual de los clientes.
### 4. Análisis exploratorio
Se utilizaron métodos estadísticos y visualizaciones para analizar:
- Distribuciones
- Patrones de consumo
- Diferencias entre grupos
- Comportamiento de las variables
- Valores atípicos
### 5. Segmentación
Los clientes fueron segmentados considerando:
- Nivel de uso
- Grupo de edad
Esta segmentación permite analizar diferentes perfiles de comportamiento dentro de la base de clientes.
### 6. Interpretación de resultados
Finalmente, los resultados fueron interpretados desde una perspectiva de negocio para identificar oportunidades relacionadas con la oferta de planes y la retención de clientes.
 
## 📈Principales resultados
El análisis permitió identificar patrones relacionados con el uso de los servicios, las características de los clientes y la distribución del consumo.
Entre los aspectos analizados se encuentran:
- Comportamiento de llamadas y mensajes.
- Distribución del consumo entre los clientes.
- Diferencias entre grupos de usuarios.
- Valores atípicos presentes en las variables de uso.
- Segmentación de clientes según su nivel de utilización.
- Comportamiento de los clientes según grupos de edad.
- Relación entre las características de los clientes y el uso de los servicios.
Los resultados específicos, valores e interpretaciones se encuentran documentados en el notebook del proyecto.
	
## 📊 Gráficos e indicadores
Para facilitar la interpretación de los resultados se utilizaron diferentes recursos de análisis y visualización:
- Distribuciones de variables.
- Histogramas.
- Gráficos comparativos.
- Análisis de valores atípicos.
- Métricas de uso por cliente.
- Segmentación por nivel de uso.
- Comparaciones por grupos de edad.
Estas visualizaciones permiten identificar patrones de comportamiento que pueden ser difíciles de observar únicamente mediante tablas de datos

## 💡 Conclusiones
El análisis permite obtener una visión estructurada del comportamiento de los clientes de ConnectaTel a partir de sus características y patrones de consumo.
Los principales elementos considerados para la interpretación son:
- Nivel de utilización de los servicios.
- Diferencias entre segmentos de clientes.
- Comportamiento de llamadas y mensajes.
- Distribución de los clientes entre los planes disponibles.
- Calidad y consistencia de la información utilizada.
- Presencia de valores atípicos.
La segmentación permite complementar el análisis general y observar el comportamiento de diferentes grupos de clientes.

## 🚀 Recomendaciones de negocio
A partir del análisis realizado, las recomendaciones se orientan a utilizar la información de comportamiento para:
- Evaluar si la oferta actual de planes responde a diferentes perfiles de consumo.
- Utilizar la segmentación de clientes como apoyo para estrategias comerciales diferenciadas.
- Analizar los patrones de uso antes de definir acciones relacionadas con cambios o ajustes de planes.
- Utilizar los indicadores de consumo como insumo para estrategias de retención.
- Mantener controles de calidad sobre los datos utilizados para análisis posteriores.
- Profundizar el análisis de los segmentos que presenten comportamientos diferenciados.
Estas recomendaciones deben interpretarse dentro del alcance de los datos disponibles y de los resultados documentados en el notebook.

## ▶️ Cómo reproducir el análisis
- 1.	Clonar o descargar el repositorio.
- 2.	Abrir el archivo S7 Version-Estudiante-Project-ConnectaTel.ipynb.
- 3.	Ejecutarlo utilizando Jupyter Notebook o Google Colab.
- 4.	Verificar que los datasets estén disponibles en la ruta utilizada por el notebook.
- 5.	Ejecutar las celdas en orden.
- 6.	Revisar las visualizaciones, resultados y conclusiones generadas
 
## Autor
Proyecto desarrollado por Cesar Palacio como parte de su formación en Data Analytics, posteriormente reorganizado y documentado para su portafolio profesional en GitHub.

