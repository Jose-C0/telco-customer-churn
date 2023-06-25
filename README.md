# Sistema de Predicción de Abandono de clientes (Customer Churn)

## Planteamiento del problema

La palabra "abandono" hace referencia a un cliente que ha decidido poner fin a su relación con la empresa y ya no utiliza sus productos o servicios. Las razones pueden ser desde productos defectuosos hasta servicios de postventa inadecuados. 
Para contrarrestar el abandono de los clientes, muchas compañías están comenzando a predecir la rotación de clientes y están tomando medidas para detener esa tendencia con la ayuda del machine learning.

Mediante el uso de tecnologías Big Data y procesamiento distribuido en la nube (Cloud Computing Clúster) este proyecto tiene como objetivo:<p>
* Desarrollar una propuesta de predicción de abandono de clientes para identificar de manera anticipada aquellos clientes que tienen una alta probabilidad de abandonar la empresa.

## Acerca del conjunto de los datos

El dataset proviene de IBM, es una empresa de telecomunicaciones. Cada registro de este conjunto de datos muestra la información de un suscriptor, el dataset contiene información sobre:<p>

- Tenure: Tiempo en el que el cliente ha estado en la empresa.
- Churn: Indica si el cliente es suscriptor o no.
- Información del cliente (Servicios contratados, genero, método de pago, antigüedad, entre otros).

## Conceptos generales relevantes

**La pérdida de clientes**<p>
La pérdida de clientes es el porcentaje de clientes que dejaron de usar el producto o servicio de su empresa durante un período de tiempo determinado. Amaresan (2018).

 <p>

**La satisfacción del cliente** <p>
Kotler & Keller (2003) declaran que “la satisfacción del cliente es determinada por el grado en el que alguien está feliz o decepcionado con el comportamiento observado de un producto con relación a sus expectativas” (p. 60). 

**Big Data** <p>
Cuando hablamos de Big Data nos referimos a conjuntos de datos o combinaciones de conjuntos de datos cuyo tamaño (volumen), complejidad (variabilidad) y velocidad de crecimiento (velocidad) dificultan su captura, gestión, procesamiento o análisis mediante tecnologías y herramientas convencionales, tales como bases de datos relacionales y estadísticas convencionales o paquetes de visualización, dentro del tiempo necesario para que sean útiles. (Power data, 2005).
<p>

**Modelo de machine Learning** <p>
Un modelo de machine learning es la salida de información que se genera cuando entrena su algoritmo de machine learning con datos. Después del entrenamiento, al proporcionar un modelo con una entrada, se le dará una salida. Por ejemplo, un algoritmo predictivo creará un modelo predictivo. (IBM, 2021).

**Aprendizaje no supervisado**<p>
El aprendizaje no supervisado tiene lugar cuando no se dispone de datos “etiquetados”  para el entrenamiento. Sólo conocemos los datos de entrada, pero no existen datos de salida que correspondan a un determinado input. Por tanto, sólo podemos describir la estructura de los datos, para intentar encontrar algún tipo de organización que simplifique el análisis. Por ello, tienen un carácter exploratorio. (Blogthinkbig, 2017)

**Regresión logística**<p>
El aprendizaje automático utiliza conceptos estadísticos para permitir que las máquinas (computadoras) "aprendan" sin programación explícita. Un enfoque logístico se adapta mejor cuando la tarea que la máquina está aprendiendo se basa en dos valores o en una clasificación binaria. Usando el ejemplo anterior, su computadora podría usar este tipo de análisis para tomar decisiones sobre la promoción de su oferta y tomar acciones por sí misma. Y, a medida que se proporcionen más datos, podría aprender a hacerlo mejor con el tiempo. (IBM, 2019).<p>

**Apache Spark**<p>
Apache Spark es un framework de programación para procesamiento de datos distribuidos diseñado para ser rápido y de propósito general. Como su propio nombre indica, ha sido desarrollada en el marco del proyecto Apache, lo que garantiza su licencia Open Source. (ESIC, 2018).<p>

**Databricks**<p>
Databricks, es el nombre de la plataforma analítica de datos basada en Apache Spark desarrollada por la compañía con el mismo nombre. Permite hacer analítica Big Data e inteligencia artificial con Spark de una forma sencilla y colaborativa. (Singh P, 2018).


## Desarrollo
 
El proyecto consta de los siguientes pasos:

- Paso 1: Crear el objeto de sesión Spark
- Paso 2: Lectura del Conjunto de Datos
- Paso 3: Análisis Exploratorio de Datos
- Paso 4: Ingeniería de Características
- Paso 5: Dividir el Conjunto de Datos
- Paso 6: Construir y Entrenar el Modelo de Regresión Logística
- Paso 7: Evaluación del modelo de regresión lineal en los datos de prueba

