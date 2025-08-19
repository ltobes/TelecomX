# 🛍️ Análisis de Abandono de clientes - TelecomX LATAM

Este proyecto explora los datos de clientes de TelecomX en LATAM,  utilizando distintas librerías de Python, como pandas, y visualizaciones con seaborn y matplotlib. A través de gráficos e insights, se identifican patrones de comportamiento de clientes, respecto de la tasa de abandono de los clientes a la compañía.

---

## 📚 Índice

1. [📌 Propósito del Análisis](#-propósito-del-análisis)
2. [📁 Estructura del Proyecto](#-estructura-del-proyecto)
3. [💻 Proceso ETL](#-proceso-ETL)
4. [📊 Ejemplos de Gráficos e Insights](#-ejemplos-de-gráficos-e-insights)

---

## 📌 Propósito del Análisis

El propósito de este análisis es:

- Realizar un proceso de extracción de la inforación y transformación de los datos de clientes de TelecomX.
- Identificar los principales factores que influencian en el abandono de los clientes.
- Identificar patrones y correlaciones relevantes para el negocio.
- Brindar **insights accionables** para la toma de decisiones comerciales.
- Preparar la base de datos para un futuro modelo predictivo

---

## 📁 Estructura del Proyecto

| Carpeta/Archivo               | Descripción                                                  |
|------------------------------|--------------------------------------------------------------|
| `TelecomX_LATAM.ipynb`      | Notebook principal con el análisis exploratorio              |
| `images/`                    | Carpeta con gráficos exportados desde el notebook            |
| `README.md`                  | Archivo con documentación del proyecto                       |

---

## 📊 Ejemplos de Gráficos e Insights

En este apartado se expondrán los principales gráficos que permiten sacar ciertos patrones a la hora de observar el abandono de los clientes al servicio prestado por la compañía.

### 📈 Ingresos Totales por Tienda

![Ingresos Totales](images/ingresos_totales.png)

> **Insight:** La tienda 1 representa el mayor volumen de ingresos, seguido por la tienda 2 y 3.

---

### 📉 Ingresos Netos por Tienda

![Ingresos Netos](images/ingresos_netos.png)

> **Insight:** A pesar de diferencias de ingresos totales, los ingresos netos, es decir contemplando los gastos en envíos, mantienen una proporción similar, lo cual puede indicar costos relativamente constantes entre las diferentes tiendas.

---

### 📉 Ingresos por categoría por Tienda

![Ingresos Netos](images/Tabla_it_por_art.png)

> **Insight:** Cuando se desagrega por categoría en todas las tiendas las ventas principalmente se dan en electrónica, seguido por electrodomésticos y muebles.

---
### 🥇🥈🥉 Calificación promedio de la tienda

![Ingresos Netos](images/cal_prom_tienda.png)

> **Insight:** Aunque la tienda 1 es la que mayor ventas tiene, es la que peor calificación promedio tiene con 3.98. La tienda 3 es la que calificación promedio tiene con 4.05 puntos.

---

### 📊 5 productos más y menos vendidos por tienda

## Los cinco productos más vendidos

![Ingresos Netos](images/Productos+vend.png)

> **Insight:** Cuando se observan los productos más vendidos por tienda se observan ciertas diferencias, respecto a la facturación y a las principales categorás de facturación. De esta manera, los productos en la tienda 1 aparecen electrodomésticos (microondas, tv y secadora de ropa) y muebles (armario y mesa de noche), mientras que en le tienda 2 el principal producto que se vende es iniciando en programación, en la tienda 3 kit de sillas y en la tienda 4 cama box.

## Los cinco productos menos vendidos

![Ingresos Netos](images/Productos-vend.png)

> **Insight:** Cuando se observan los productos menos vendidos por tienda se observan nuevamente diferencias, el producto que menos se vende en la tienda 1 es Celular ABXY, en la tienda 2 juego de mesa, en la tienda 3 bloques de construcción y en la tienda 4 la guitarra eléctrica.
---

### 🚚 Costo de envío promedio por tienda

![Ingresos Netos](images/costo_env_prom.png)

> **Insight:** El costo promedio de envío mayor se da en la tienda 1 con un monto de $26.018 y el menor en la tienda 4 $23.459.

---
