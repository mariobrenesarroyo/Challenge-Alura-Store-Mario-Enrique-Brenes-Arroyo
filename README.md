# 🛍️ Alura Store - Análisis de Rendimiento de Tiendas

Este proyecto tiene como objetivo analizar el rendimiento de cuatro tiendas con el fin de ayudar al Sr. Juan a tomar una decisión estratégica: vender la tienda con menor desempeño para invertir en un nuevo negocio.

## 📌 Propósito del Análisis

A través de un estudio de datos de ventas, productos y clientes, este análisis busca identificar:

- 📊 **La facturación total de cada tienda.**
- 🏷️ **Las categorías más populares en cada tienda.**
- ⭐ **El promedio de evaluación de los clientes por tienda.**
- 📦 **Los productos más y menos vendidos por tienda.**
- 🚚 **El costo promedio de envío de cada tienda a sus clientes.**

Con esta información, será posible tomar una decisión fundamentada sobre qué tienda vender.

## 📂 Estructura del Proyecto


Alura_Store_Analisis/
├── data/
│   ├── ventas_tienda_A.csv
│   ├── ventas_tienda_B.csv
│   ├── ventas_tienda_C.csv
│   └── ventas_tienda_D.csv
├── notebooks/
│   ├── analisis_exploratorio.ipynb
│   └── informe_rendimiento.ipynb
├── scripts/
│   ├── procesamiento_datos.py
│   └── visualizaciones.py
├── resultados/
│   ├── informe_final.pdf
│   ├── facturacion_por_tienda.png
│   ├── categorias_populares_por_tienda.png
│   ├── promedio_evaluacion_por_tienda.png
│   ├── productos_vendidos_por_tienda.png
│   └── costo_envio_promedio_por_tienda.png
└── README.md

**Descripción de las carpetas y archivos:**

* `data/`: Contiene los archivos de datos brutos para cada tienda.
* `notebooks/`: Alberga los cuadernos de Jupyter utilizados para el análisis.
* `scripts/`: Incluye scripts de Python para procesamiento y visualización.
* `resultados/`: Contiene el informe final y los archivos de las visualizaciones generadas.
* `README.md`: Este archivo, con la descripción general del proyecto.

## 📊 Visualizaciones Clave

Esta sección describe brevemente los gráficos generados durante el análisis y sus principales hallazgos.

* **`facturacion_por_tienda.png`:** Este gráfico de barras compara la facturación total de cada una de las cuatro tiendas. Permite identificar rápidamente cuál o cuáles tiendas generan mayores ingresos. *(Aquí podrías añadir un hallazgo específico si ya lo tienes, por ejemplo: "Se observa que la Tienda C es la que presenta la mayor facturación.")*

* **`categorias_populares_por_tienda.png`:** A través de gráficos de barras agrupados o gráficos de pastel, se visualizan las categorías de productos más vendidas en cada tienda. Esto ayuda a entender las preferencias de los clientes en cada ubicación. *(Ejemplo de hallazgo: "La categoría 'Electrónica' es consistentemente popular en todas las tiendas, aunque con variaciones en su proporción.")*

* **`promedio_evaluacion_por_tienda.png`:** Un gráfico de barras muestra el promedio de las evaluaciones de los clientes para cada tienda. Esto proporciona una perspectiva sobre la satisfacción del cliente en cada ubicación. *(Ejemplo: "La Tienda B tiene el promedio de evaluación más alto, lo que sugiere una mayor satisfacción de sus clientes.")*

* **`productos_vendidos_por_tienda.png`:** Este conjunto de gráficos (podrían ser barras o incluso tablas resumidas en imágenes) muestra los productos más y menos vendidos en cada tienda. Esto puede revelar tendencias de demanda específicas por ubicación. *(Ejemplo: "El producto 'Artículo X' es el más vendido en la Tienda A, pero se encuentra entre los menos vendidos en la Tienda D.")*

* **`costo_envio_promedio_por_tienda.png`:** Un gráfico de barras compara el costo promedio de envío a los clientes de cada tienda. Esta información es relevante para entender los costos operativos asociados a cada ubicación. *(Ejemplo: "El costo promedio de envío es significativamente mayor para la Tienda D, lo que podría ser un factor a considerar.")*

## ⚙️ Cómo Empezar

1.  **Clonar el repositorio (si aplica):**
    ```bash
    git clone [https://github.com/tu_repositorio/alura_store_analisis.git](https://github.com/tu_repositorio/alura_store_analisis.git)
    cd Alura_Store_Analisis
    ```
2.  **Instalar las dependencias:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Explorar los notebooks:**
    Abre los notebooks en la carpeta `notebooks/` para seguir el proceso de análisis y ver la generación de los gráficos.
4.  **Visualizar los resultados:**
    Las imágenes de los gráficos se encuentran en la carpeta `challenge1-data-science-main/`.

## 🛠️ Herramientas Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
