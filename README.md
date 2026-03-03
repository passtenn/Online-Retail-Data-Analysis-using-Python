# 📊 Análisis de Datos de Ventas - Online Retail

### 📌 Descripción del Proyecto
Este proyecto presenta un análisis exploratorio de datos (EDA) utilizando un dataset de transacciones de una tienda en línea. El objetivo principal es limpiar, preparar y analizar los datos para identificar patrones de ventas, productos más rentables, países con mayor generación de ingresos y comportamiento temporal de las ventas.
El análisis fue realizado utilizando Python y librerías especializadas en análisis de datos.

Este proyecto demuestra habilidades clave como:
  - Limpieza y preparación de datos
  - Análisis exploratorio de datos (EDA)
  - Creación de nuevas variables
  - Agrupación y agregación de datos
  - Visualización de datos
  - Generación de insights de negocio

### 📁 Información del Dataset
El dataset contiene registros de transacciones e incluye las siguientes columnas:
  - Número de factura
  - Código y descripción del producto
  - Cantidad vendida
  - Fecha de la factura
  - Precio unitario
  - ID del cliente
  - País

Cada fila representa un producto dentro de una transacción.

### 🧹 Limpieza y Preparación de los Datos
Se realizaron los siguientes pasos:
  - Se estandarizaron los nombres de las columnas al formato snake_case
  - Se convirtió la columna invoice_date a formato datetime
  - Se creó una nueva columna llamada revenue:
      revenue = quantity * unit_price
  - Se identificaron valores faltantes:
  - Se eliminaron filas sin descripción del producto, ya que esta información es esencial
  - Se conservaron filas sin customer_id, ya que siguen siendo válidas para el análisis de ventas
  - Se eliminaron aproximadamente 5,000 registros duplicados para evitar distorsiones en los resultados

Estos pasos permiten asegurar la calidad y confiabilidad de los datos.

### 📈 Análisis Realizado
💰 Métricas Generales de Ventas
  - Promedio de ingresos por transacción: $18.17
  - Moda de ingresos: $15.00
  - Total de ingresos generados: $9,726,006.95
Debido a la presencia de valores atípicos, la moda representa mejor el valor típico de las ventas.

### 🏆 Productos con Mayores Ventas
Top 3 productos con mayor ingreso generado:
  - DOTCOM POSTAGE — $206,245.48
  - REGENCY CAKESTAND 3 TIER — $164,459.49
  - PARTY BUNTING — $98,243.88

### 🌍 Ventas por País
El país con mayor generación de ingresos es:
- Reino Unido:
  Total: $8,167,128.18
Representa el 83.97% del total de ventas
Esto indica que es el mercado principal.

### 📅 Ventas por Periodo
Se identificó un pico importante de ventas entre:
  - Septiembre 2011
  - Octubre 2011
  - Noviembre 2011
Siendo noviembre el mes con mayor ingreso generado.

### 📊 Visualizaciones Incluidas
  - Diagrama de caja de ingresos
  - Top productos por ingresos
  - Ventas por país
  - Ventas por periodo de tiempo

### 🛠 Herramientas Utilizadas
  - Python
  - Pandas
  - Matplotlib
  - Seaborn
  - Jupyter Notebook

### 📂 Estructura del Proyecto
online-retail-analysis/

├── Online_Retail.csv

├── Online_Retail_Analysis.ipynb

└── README.md

### 🚀 Habilidades Demostradas
  - Limpieza de datos
  - Análisis exploratorio de datos
  - Manipulación de datos con Pandas
  - Visualización de datos
  - Generación de insights de negocio

### 📌 Conclusión
El análisis permitió identificar los productos más rentables, el país con mayor generación de ingresos y tendencias temporales relevantes. Estos resultados pueden ser utilizados para apoyar decisiones estratégicas como optimización de inventario, enfoque de marketing y planificación de ventas.
