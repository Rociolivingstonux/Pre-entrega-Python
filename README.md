** 📊 Análisis de Datos: Proyecto Talento Tech **

Nota: Este proyecto es parte de la pre-entrega para el curso de Ciencia de Datos en Talento Tech.

📑 Tabla de Contenidos

Descripción del Proyecto

Estructura del Notebook

Datasets Utilizados

Tecnologías Utilizadas

Resultados del Análisis

Instalación y Uso

Autor

📖 Descripción del Proyecto

Este repositorio contiene un análisis exploratorio de datos (EDA) integral que simula un escenario de negocio real. El objetivo es procesar y analizar información de Clientes, Ventas y Marketing para extraer insights valiosos sobre el rendimiento de productos y el comportamiento del consumidor.

El flujo de trabajo abarca desde la conexión con fuentes de datos en la nube (Google Drive) hasta la limpieza, transformación y visualización inicial de los datos utilizando Python en un entorno de Google Colab.

📂 Estructura del Notebook

El desarrollo se divide en 4 fases principales, documentadas paso a paso en el código:

Configuración y Carga de Datos:

Conexión con Google Drive (drive.mount).

Importación de librerías (os, pandas).

Lectura de múltiples fuentes de datos (csv, xlsx).

Transformación de Datos:

Aplicación de filtros para segmentar información.

Identificación de productos con "alto rendimiento" en ventas.

Estructuras de Datos (Lógica de Python):

Implementación de algoritmos para almacenar datos de ventas.

Toma de decisiones sobre el uso eficiente de Listas vs Diccionarios para el almacenamiento en memoria.

Introducción a Pandas (EDA):

Análisis exploratorio profundo de los DataFrames generados.

Uso de funciones clave: head(), tail(), describe(), info(), shape.

📊 Datasets Utilizados

Los datos se encuentran alojados en una carpeta de Google Drive y se cargan dinámicamente. Los archivos principales son:

clientes.csv: Información demográfica y de contacto de la cartera de clientes.

ventas.csv / ventas.xlsx: Registro transaccional de ventas (Producto, Precio, Cantidad).

marketing.csv: Datos relacionados con campañas y canales de adquisición.

(Opcional) netflix_titles.csv: Dataset complementario para prácticas de manipulación.

🛠️ Tecnologías y Herramientas

Entorno: Google Colab

Lenguaje: Python 3

Librerías Clave:

pandas: Para la manipulación de DataFrames y análisis estadístico.

google.colab: Para la integración con almacenamiento en la nube.

os: Para la navegación del sistema de archivos.

🔍 Resultados del Análisis Exploratorio

Durante la ejecución del notebook se obtuvieron los siguientes insights técnicos:

✅ Verificación de Calidad: Se validaron los tipos de datos (dtypes) para asegurar que las columnas numéricas y de texto sean correctas.

📏 Dimensiones: Se identificó el volumen total de registros (shape) para dimensionar el alcance del análisis.

📈 Estadísticas Descriptivas: Se generó un resumen estadístico (describe) para entender la distribución de valores numéricos en ventas y clientes (promedios, máximos, mínimos).

🚀 Cómo Ejecutar este Proyecto

Clonar/Descargar: Descarga el archivo .ipynb de este repositorio.

Abrir en Colab: Sube el archivo a Google Colab.

Cargar Datos: Asegúrate de tener los archivos CSV/Excel en tu Google Drive dentro de una carpeta My Drive/DataSets/ o ajusta la ruta en el código.

Ejecutar: Corre todas las celdas secuencialmente (Runtime > Run all).

✒️ Autor

Rocio Livingston

Estudiante de Data Science - Talento Tech

💼 LinkedIn

💻 GitHub
