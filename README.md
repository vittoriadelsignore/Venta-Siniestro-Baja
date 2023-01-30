# Venta-Siniestro-Baja
Seguimiento de productos

Creado por: Vittoria Del Signore.

Descripción: la carpeta contiene un dashboard creado en Power BI, y los archivos bases que se usaron. 
En este caso, corresponde a información de ventas de diferentes productos del rubro de seguros.  Hay infomración de ventas, siniestros y bajas. 
Lo que se busca es hacer:
1) Análisis exploratorio
2) Análisis de cada variable
  - edad promedio de los clientes
  - provincia o zona donde compran
  - producto más vendido
  - cantidad de ventas
  - cantidad de siniestros
  - cantidad de bajas
3) Encontrar relaciones entre estas 3 instancias por las que pasa un cliente (venta, siniestro y baja).

Objetivo: luego de analizar las variables, tomar acciones estratégicas basadas en información histórica real.

El primer paso fue hacer un dashboard separando las 3 principales variables, empezando por evaluar las ventas. Allí se puede ver que en los últimos dos años (2021 y 2022) hubo 987 ventas en total, donde el producto más vendido fue el de Salud, seguido por protección en Cajeros Automáticos, y la protección de artículos de Tecnología.
Adicionalmente, la provincia con más ventas fue Catamarca, ya que allí está la casa matriz de la compañía. Los clientes tienen un rango etario que va entre 46-60 años en su mayoría, es relativamente equitativo entre hombres y mujeres.
Compran de forma indistinta los diferentes planes que ofrece la compañía, y prefieren comprar en los canales denominados A y Z:

![Gráficos de Ventas](https://github.com/vittoriadelsignore/Venta-Siniestro-Baja/blob/master/TableroVentas.png)

Se siguió desarrollando en dashboard, pero en distintas hojas para ver diferentes variables, primero por separado. Entonces se hizo otro análisis de Siniestros. El producto con más siniestros es "Robo en Cajeros", a diferencia de la venta, que se centraba en productos de salud. Nuevamente la provincia con mayor volumen es Catamarca, lo cual tiene sentido, ya que también es la provincia con más ventas. Y algo a destacar es que el género con más siniestralidad es el femenino, principalmente los grupos de 36-45 y 18-24; y en contraparte, el resto de grupos tiene mayoría de género masculino. Los canales donde se reportan los siniestros están concentrados en los denominados P y C:

 ![Gráficos de Siniestros](https://github.com/vittoriadelsignore/Venta-Siniestro-Baja/blob/master/TableroSiniestros.png)
