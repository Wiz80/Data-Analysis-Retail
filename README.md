# Data-Analysis-Retail - Análisis de ventas en línea

Este proyecto realiza un análisis de ventas en línea utilizando datos de ventas de dos años consecutivos.

El código fuente está escrito en Python y utiliza las bibliotecas `pandas`, `matplotlib` y `seaborn` para el análisis y visualización de los datos.

## Datos

Los datos utilizados en este análisis provienen de dos archivos de Excel 'online_retail.xlsx', que contienen las ventas en línea para los años 2009-2010 y 2010-2011.

## Análisis

Se lleva a cabo un análisis exploratorio de los datos, respondiendo las siguientes preguntas:

- ¿Qué país consume más productos?
- ¿Cuáles son los productos más populares en términos de ventas y ganancias?
- ¿Cuáles son las tendencias de ventas mensuales?
- ¿Existe alguna correlación entre el precio de un producto y la cantidad vendida?

### País que más productos consume

Para determinar el país que consume más productos, se agrupan los datos por país y se suman las cantidades de productos.

### Productos más populares

Para determinar los productos más populares, se agrupan los datos por descripción de producto y se suman las cantidades de productos vendidos y las ganancias (Precio * Cantidad).

### Tendencias de ventas

Para analizar las tendencias de ventas, se agrega una columna 'Month' a los datos, se agrupan los datos por mes y se suman las cantidades de productos vendidos.

### Correlación entre el precio de un producto y la cantidad vendida

Para analizar la correlación entre el precio de un producto y la cantidad vendida, se calcula el coeficiente de correlación entre estas dos variables.

## Resultados

El análisis muestra que no hay una correlación significativa entre el precio de un producto y la cantidad vendida. Además, las ventas tienden a aumentar entre julio y noviembre, posiblemente debido a compras de vacaciones, ventas del "Black Friday" y "Cyber Monday", y promociones y descuentos de temporada.
