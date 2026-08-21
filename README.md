# Estimación de gases contaminantes según el tipo de vehículos en las comunas del gran concepción
Este repositorio contiene el proyecto de análisis de datos e interpretación de emisiones de gases vehiculares y permisos de circulación del **Gran Concepción (Región del Bío-Bío, Chile)** correspondiente a los años 2022 hasta el 2024.

# Contexto
El objetivo principal de este proyecto es estimar las emisiones de gases contaminantes generadas por el tipo de vehículo en las distintas comunas del Gran Concepción (Región del Bío-Bío, Chile).
Para lograr esto, el proyecto integra dos fuentes de datos clave:

* Registro de Permisos de Circulación (Microsoft Access): Permite caracterizar y dimensionar el vehicular local, clasificando los vehículos por tipo y su tipo de combustible o propulsión (gasolina, diésel, gas, eléctrico, etc.).

* Dataset de Factores de Emisión: Aporta la información técnica necesaria relacionando cada tipo de vehículo y emisor con los contaminantes específicos emitidos (identificados por ID de contaminante, nombre del contaminante y categoría de emisor vehicular).

Al cruzar los datos del volumen y tipo de vehículos en circulación con los perfiles de emisión correspondientes, esta herramienta permite calcular qué comunas del Gran Concepción concentran mayores niveles de contaminación, qué tipos de vehículos o combustibles son los principales responsables y generar información relevante para la gestión ambiental y la toma de decisiones en transporte regional.

 # Tecnologías y Librerías Utilizadas
* **Lenguaje:** Python 3.x
* **Entorno de desarrollo:** Visual Studio Code / Jupyter Notebooks (`.ipynb`)
* **Procesamiento de datos:** `pandas`, `numpy`
* **Conexión a Base de Datos:** `pyodbc` (Microsoft Access ODBC Driver)
* **Visualización de Datos:** `matplotlib`, `seaborn`
* **Modelamiento y ML:** `scikit-learn` (Árboles de Decisión, Evaluación de Métricas)
* **Análisis Espacial:** `geopandas` de comunas del Gran Concepción.

 # Estructura del Repositorio:                                   
 ┣ data/                                                                                            
 ┣ notebooks/ analisis_emisiones.ipynb                                     # Cuaderno principal con el procesamiento y análisis                                 
 ┣ README.md/                                # Descripción general del proyecto                                                       
 ┗ requirements.txt/                         # Dependencias de Python para replicar el entorno                                                 
