 Alura Store Challenge

## Descripción
Desarrollo de ejercicio practico "Alura Store", analizando datos de rendimiento de cuatro tiendas para informar al Señor Juan nuestro analisis y que el tome la mejor Desición Informada sobre cual tienda podria vender.
<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/2503/2503734.png" alt="Tienda Icono" width="32" height="32">
</p>

## Tabla de Contenidos
* [Descripción](#descripción)
* [Objetivos del Proyecto](#objetivos-del-proyecto)
* [Tecnologías Utilizadas](#tecnologías-utilizadas)
* [Instalación](#instalación)
* [Uso](#uso)
* [Análisis de Datos](#análisis-de-datos)
* [Conclusiones](#conclusiones)
* [Autor](#autor)
* [Licencia](#licencia)

## Objetivos del Proyecto
* Analizar datos de rendimiento de cuatro tiendas.
* Proporcionar un informe claro y conciso para facilitar la toma de Decisiones Informadas.
* Desarrollar habilidades en análisis de datos y presentación de informes.

## Tecnologías Utilizadas
* Jupiter Notebook (Colab)
* Python
  - Pandas
  - Matplotlib
  - Numpy
  - Contextily
  - Geopandas
* Markdown

## Instalación
Para ejecutar este proyecto, sigue estos pasos:

1.  Clona este repositorio:

    ```bash
    git clone [https://github.com/RafaelRomeroTechDev/Challenge_Alura_Store.git](https://github.com/RafaelRomeroTechDev/Challenge_Alura_Store.git)
    ```

2.  Navega al directorio del proyecto:

    ```bash
    cd Challenge_Alura_Store
    ```

3.  Instala las dependencias (asegúrate de tener Python y pip instalados):

    ```bash
    pip install -r requirements.txt
    ```

    Si no tienes un archivo `requirements.txt`, puedes instalar las bibliotecas individualmente:

    ```bash
    pip install pandas jupyter [otras_librerías]
    ```

## Uso
1.  Abre el notebook de Jupyter:

    ```bash
    jupyter notebook
    ```

2.  Navega al archivo del notebook (`.ipynb`) que contiene el análisis.
3.  Ejecuta las celdas del notebook para realizar el análisis de datos y ver los resultados.

## Análisis de Datos
En este repositorio, encontrarás un análisis detallado de los datos de rendimiento de las cuatro tiendas. El análisis incluye:

* Análisis de facturación con el cual determino los ingresos totales de cada tienda y los represento en un gráfico de barras horizontal.
* Ventas por Categoría con el cual determino la cantidad de ventas por cada categoría de producto junto con el ingreso total obtenido y represento las cantidades de venta por categorías en un gráfico de barras horizontal y el valor total vendido por categoría en cada tienda.
* Valoración Media por Tienda con el cual analizo las calificaciones obtenidas en cada categoría por tienda y represento las calificaciones por categoría en un gráfico de barras horizontales y represento el promedio de calificación general de las cuatro tiendas para cada categoría, adicionalmente genero un gráfico de torta con el promedio de calificaciones general por tienda.
* Productos más vendidos y productos menos vendidos con el cual analizo cuales son los tres productos más vendidos y los tres productos menos vendidos por tienda, genero un gráfico de torta con los seis productos por tienda resaltando el producto más vendido y el producto menos vendido.
* Gastos de Envío con el cual determino el gasto total de envío por cada tienda, calculo el valor promedio de envío y represento en un gráfico de barras horizontal el gasto total de envío por tienda contrastado con el promedio de gastos de envío de las cuatro tiendas, adicionalmente agrego el grafico de barras horizontal del ingreso neto de la tienda restando el gasto de envío del ingreso total.
* Localización de las Ventas con el cual genero gráficos por cada tienda de la ubicación geográfica de cada venta realizada montando estos puntos en una tesela de Colombia obtenida de Open Street Map.
* Informe con el cual redacto el informe para el Señor Juan del análisis realizado a partir de la información obtenida en cada tienda, genero un archivo pdf con el respectivo informe.

## Conclusiones
Basado en el análisis, las principales conclusiones son:

* El promedio de ventas netas de las cuatro tiendas es de $1042.2 millones, la tienda con mayor ingreso es la tienda uno con ventas por $1089.5 millones y la tienda con menor ingreso es la tienda 4 con ventas por $983.1 millones.
* La tienda mejor calificada fue la tienda tres con una calificación promedio de 4.05 mientras que la tienda con menor calificación fue la tienda uno con una calificación promedio de 3.98.

## Autor
Rafael Romero

* [Tu perfil de GitHub](https://github.com/rojidruyard)
