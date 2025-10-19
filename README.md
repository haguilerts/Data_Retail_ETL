<<<<<<< HEAD
=======

>>>>>>> 05a6e38d65c7eacac3695b5351b847f474eaf772
# [NOMBRE DEL PROYECTO] | Análisis de Ventas Retail (2021-2023) 📈
<img src="img/Tendencia_ventas_mensuales.png" alt="Venta anual por genero" width="500" height="300" style="display: block; margin: 0 auto;">
Este proyecto implementa un flujo de **ETL (Extracción, Transformación y Carga)** y posterior **Análisis de Datos Descriptivo** sobre transacciones de venta de múltiples centros comerciales, con el objetivo de identificar patrones clave de consumo, demografía de clientes (género y edad) y rendimiento de productos.
## 📋 Tabla de Contenidos

1.  [Fuente de Datos](#3-fuente-de-datos)
2.  [Requisitos e Instalación](#4-requisitos-e-instalación)
3.  [Fases del Proyecto (ETL)](#5-fases-del-proyecto-etl)
    * [3.1 Extracción y Combinación](#31-extracción-y-combinación)
    * [3.2 Limpieza y Estandarización](#32-limpieza-y-estandarización)
    * [3.3 Carga (Load) a Base de Datos](#33-carga-load-a-base-de-datos)
4.  [Resultados Clave del Análisis](#6-resultados-clave-del-análisis)

## 📁 Fuente de Datos

El análisis se basa en un dataset que comprende transacciones de venta de 10 centros comerciales en Estambul entre 2021 y 2023. El proyecto consume inicialmente dos archivos CSV que fueron combinados:

* **`sales_data.csv`**: Contiene detalles de la transacción (categoría, precio, fecha, centro comercial).
* **`customer_data.csv`**: Contiene información demográfica (ID de cliente, género, edad).

**Estructura de la Tabla Final:** `ventas_clientes_clean` (almacenada en la DB `ispc`).

## ⚙️ Requisitos e Instalación

Para ejecutar el *notebook* y el flujo de ETL completo, se requiere:

### 1. Entorno de Base de Datos
* **Motor:** MySQL / MariaDB.
* **Servidor Local:** Se utilizó **XAMPP** para iniciar los servicios Apache y MySQL.
* **Base de Datos:** `ispc` (configurada para recibir la tabla `ventas_clientes_clean`).

### 2. Librerías de Python
Instalar las dependencias usando `pip`:
<img src="img/Tendencia_ventas_mensuales .png" alt="Venta Mensual" width="500" height="300" style="display: block; margin: 0 auto;">

```bash
pip install pandas sqlalchemy pymysql matplotlib seaborn jupyter
## 📈 Resultados Clave del Análisis Descriptivo

El análisis arrojó conclusiones importantes sobre el comportamiento de compra (ver carpeta `images/` para todos los gráficos):

* **Dominio de Género:** El género **Femenino** es el principal motor de ingresos, contribuyendo con el **59.7%** del monto total de ventas.
* **Cliente Activo:** El grupo de edad **+66 años** registra la mayor **frecuencia de transacciones** para ambos géneros.
* **Impacto de Categoría:** La categoría **Shoes** es la más vendida por frecuencia, mientras que **Technology** tiene el precio promedio más alto ($3,157).
* **Ubicación Clave:** La mayoría de las transacciones se concentran en **Mall of Istanbul** y **Kanyon**.
<<<<<<< HEAD
<img src="img/Tendencia_ventas_mensuales .png" alt="Venta Mensual" width="500" height="300" style="display: block; margin: 0 auto;">
=======

>>>>>>> 05a6e38d65c7eacac3695b5351b847f474eaf772
