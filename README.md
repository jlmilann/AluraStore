# Análisis de Rendimiento de Sucursales - Alura Store 📊

## 🎯 Propósito del Proyecto
Este proyecto de análisis de datos fue desarrollado para asistir al Sr. Juan en una toma de decisión estratégica: **identificar cuál de las 4 sucursales de su cadena "Alura Store" debe vender** para financiar un nuevo emprendimiento. 

A través de un análisis exploratorio de datos (EDA) utilizando Python y la librería Pandas, se evaluaron métricas clave como facturación total, volumen de ventas por categoría, calificaciones de satisfacción al cliente, rotación de inventario y costos logísticos.

---

## 📂 Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

* `Analisis_Alura_Store.ipynb`: El Jupyter Notebook principal que contiene todo el código fuente, dividido en 5 bloques de análisis lógico y visualizaciones.
* `tienda_1 .csv`: Base de datos histórica de ventas de la Sucursal 1.
* `tienda_2.csv`: Base de datos histórica de ventas de la Sucursal 2.
* `tienda_3.csv`: Base de datos histórica de ventas de la Sucursal 3.
* `tienda_4.csv`: Base de datos histórica de ventas de la Sucursal 4.
* `README.md`: Este documento de documentación e instrucciones.

---

## 💡 Ejemplos de Insights Obtenidos

El análisis se dividió en 5 bloques fundamentales, revelando los siguientes hallazgos estratégicos:

1.  **Facturación (Gráfico Circular):** Se descubrió que la **Tienda 4 es la menos eficiente**. A pesar de procesar el mismo volumen de pedidos que el resto (~2,359 transacciones), generó la facturación más baja (\$1,038 millones frente a los \$1,150 millones de la líder).
2.  **Ventas por Categoría (Gráfico de Barras):** El patrón de consumo es similar en todas las tiendas, destacando las categorías de *Muebles* y *Electrónicos* como las de mayor volumen de salida.
3.  **Calificación Promedio:** La Tienda 3 lidera en satisfacción del cliente (4.05/5.0), mientras que la Tienda 1 tiene la calificación más baja (3.98/5.0).
4.  **Rotación de Productos:** Se identificó que la rentabilidad reducida de la Tienda 4 se debe a que sus productos más vendidos (*Cama box*, *Cubertería*) tienen un menor ticket promedio en comparación con los productos estrella de la Tienda 1 (*Armario*, *TV LED UHD 4K*).
5.  **Envío Promedio (Gráfico de Barras):** La Tienda 4 ofrece el costo logístico más bajo (\$23,459). Sin embargo, esto no se tradujo en una ventaja competitiva de ventas o reputación.

**Recomendación Final:** Se aconseja liquidar la **Tienda 4**, ya que permite al Sr. Juan obtener capital limpio deshaciéndose de su activo menos eficiente, conservando sus sucursales más rentables y queridas por el público.
