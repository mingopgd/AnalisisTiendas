# Análisis de Desempeño de Tiendas

Este repositorio contiene el análisis de desempeño de varias tiendas, realizado como parte del **Challenge 1 de Data Science Latam**. El objetivo principal fue identificar cuál es la tienda con peor desempeño para que el Sr. Juan pueda venderla y emprender un nuevo negocio.

## Contenido del repositorio

- `analisis_tiendas.ipynb` : Notebook de Google Colab con todo el análisis, incluyendo:
  - Carga y limpieza de datos.
  - Cálculo de métricas clave:
    - Facturación total por tienda.
    - Ventas por categoría de productos.
    - Calificación promedio de clientes por tienda.
    - Productos más y menos vendidos.
    - Costo de envío promedio por tienda.
  - Visualizaciones de los resultados (5 gráficos).
  - Informe final con conclusión sobre la tienda con peor desempeño.

- Datos utilizados (CSV):
  - `tienda_1.csv`
  - `tienda_2.csv`
  - `tienda_3.csv`
  - `tienda_4.csv`

> Los datos se cargan directamente desde URLs públicas, por lo que no es necesario descargarlos manualmente.

## Gráficos incluidos

1. **Facturación por tienda** – gráfico de barras.  
2. **Ventas por categoría** – gráfico circular (pie chart) con porcentajes y leyenda clara.  
3. **Calificación promedio por tienda** – gráfico de dispersión mostrando relación con facturación.  
4. **Productos más vendidos** – gráfico de barras horizontales.  
5. **Costo de envío promedio por tienda** – gráfico de barras.  

## Conclusión del análisis

Tras analizar todas las métricas, la tienda **Valledupar** fue identificada como la de peor desempeño. Presenta la facturación más baja, pocas ventas y rotación limitada de productos. La recomendación es que el Sr. Juan venda esta tienda para liberar recursos y enfocarse en un nuevo emprendimiento con mayor potencial.

## Cómo ejecutar el proyecto

1. Abrir `analisis_tiendas.ipynb` en Google Colab.  
2. Ejecutar todas las celdas secuencialmente; los datos se cargarán automáticamente desde las URLs públicas.  
3. Revisar los gráficos y la conclusión final dentro del notebook.  

## Herramientas utilizadas

- Python 3  
- Pandas  
- Matplotlib  
- Google Colab
