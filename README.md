# Análisis de ventas para Costa Centro Comercio (CCC)

## Antecedentes y visión general


En el corazón de la península ibérica, donde la vibrante costa mediterránea se encuentra con la energía del centro, emerge Costa Centro Comercio (CCC), una compañía líder en la oferta de productos y servicios diversificados. Con una fuerte presencia en tres de los nodos urbanos más dinámicos de España - Barcelona, Madrid y Valencia - CCC se posiciona como el puente perfecto entre la innovación costera y la solidez del centro, brindando a sus clientes una experiencia de compra única y integral.

La compañía tiene cantidades masivas de información detallada e informativa de sus ventas. Este proyecto analiza detalladamente esa información para producir un reporte anual que determine áreas para mejorar.

Los descubrimientos y recomendaciones son proporcionadas en las siguientes áreas claves:

- Rendimiento general de ventas: ofrece métricas como el total de los ingresos, costo de venta, utilidad y % utilidad en el transcurso del año.

- Análisis por línea de producto: ofrece las métricas anteriores por línea de producto, por género y línea de producto.

- Análisis de patrones de los clientes: ofrece la distribución de ventas por tipo de cliente.

- Análisis de medios de pagos: ofrece la distribución de ventas por tipo de medio de pago.

Para poder facilitar la toma de decisiones de la compañía al entender mejor sus ventas, se creó un dashboard, que ofrece distintos gráficos y métricas claves relevantes para las partes interesadas.


## Estructura de datos y exploraciones iniciales
 
Se utilizó un conjunto de datos que contiene las transacciones de ventas de la compañía a lo largo del año 2019. Contiene los siguientes campos de información:


**Tabla de Campos y Propósitos**
| **Campo** | **Propósito** |
| --- | --- |
| **Fecha** | Registra la fecha en la que se realizó la transacción, permitiendo el análisis temporal de las ventas |
| **Sucursal** | Identifica la ubicación geográfica (Barcelona, Madrid o Valencia) donde se llevó a cabo la transacción, facilitando análisis regionales y de desempeño por sucursal |
| **Línea de producto** | Clasifica el producto vendido en una de las categorías predefinidas (Accesorios de moda, Accesorios electrónicos, Comidas y bebidas, Deportes y viajes, Hogar y estilo de vida, Salud y belleza), permitiendo el análisis de ventas por tipo de producto y la identificación de tendencias en diferentes sectores |
| **Medio de pago** | Registra el método utilizado por el cliente para realizar el pago (Efectivo, Tarjeta de Crédito, etc.), ayudando a entender las preferencias de pago de los clientes y a optimizar los métodos de pago disponibles |
| **Precio unitario** | Especifica el precio de venta de un solo artículo, necesario para calcular totals y analizar la rentabilidad por unidad |
| **Cantidad** | Indica la cantidad de unidades vendidas en una transacción, crucial para calcular el total de la venta y analizar volúmenes de ventas |
| **Total venta** | Muestra el monto total de la transacción, resultante de multiplicar el precio unitario por la cantidad vendida, utilizado para el cálculo de ingresos y análisis de ventas |
| **Costo de venta** | Registra el costo asociado a la producción o adquisición del producto vendido, esencial para calcular la utilidad y el margen bruto, y evaluar la rentabilidad de los productos |
| **Margen Bruto (%)** | Calcula el porcentaje de ganancia sobre el total de la venta, después de restar el costo de venta, proporcionando una medida rápida de la rentabilidad de cada transacción |
| **Utilidad** | Muestra la ganancia neta obtenida en una transacción, resultante de restar el costo de venta del total de la venta, utilizado para evaluar la rentabilidad y tomar decisiones de precios y de producción |

## Resumen ejecutivo

### Visión general de descubrimientos


El análisis integral del desempeño comercial durante 2021 revela un panorama empresarial
estable con áreas estratégicas de oportunidad para Costa Centro Comercio (CCC). Con unas
ventas totales de €164,998 y un beneficio de €7,857, la empresa mantuvo un margen de
beneficio del 4.76%, destacándose la categoría de Deportes y Viajes como la líder en
ventas con €30,078. La segmentación por género mostró patrones de consumo diferenciados,
con los hombres prefiriendo Deportes y viajes (€15,568) y las mujeres inclinándose hacia Comida y
bebidas (€15,728). Los métodos de pago reflejan una transición gradual hacia
la digitalización, con el efectivo liderando con un 37%, seguido por las
billeteras electrónicas (33%) y las tarjetas de crédito (30%). La base de
clientes muestra un notable equilibrio entre usuarios regulares (50.09%) y
miembros (49.91%), mientras que la distribución semanal de ventas identifica
los martes, viernes y sábados como los días de mayor actividad comercial, con
picos de hasta €27,018, en contraste con los jueves que registran el volumen
más bajo (€17,608). Las siguientes secciones explorarán factores y resaltar áreas de oportunidad
claves para mejorar.

Abajo esta el dashboard realizado en Excel. El dashboard interactivo completo puede ser visto [aquí](https://1drv.ms/x/s!ApUe3nTukn-rawkMI6-e0Z-Xsdo?e=zGF9zV).

<iframe width="700" height="720" frameborder="0" scrolling="no" src="https://onedrive.live.com/embed?resid=AB7F92EE74DE1E95%21107&authkey=%21AC0uTSvpVK_PwuE&em=2&wdAllowInteractivity=False&wdHideGridlines=True&wdHideHeaders=True&wdDownloadButton=True&wdInConfigurator=True&wdInConfigurator=True"></iframe>

### Análisis de las KPIs


En 2021, la empresa logró unas ventas totales de €164,998, con un costo de ventas de €157,141 y 
un beneficio resultante de €7,857. Esto se traduce en un margen de beneficio del 4.76%, que es 
bajo, pero aún así es alentador.

### Análisis de líneas de productos

Las diversas líneas de productos se analizan en un análisis detallado y muestran una tendencia 
uniforme en todas las categorías. Deportes y viajes encabezan la lista con ventas de €30,078 y 
una ganancia de €1,432. Los siguientes contendientes, Hogar y estilo de vida y Salud y belleza, 
lograron cada uno alcanzar ventas por valor de €28,487 y ganaron €1,357 cada uno en 
beneficios. Los sectores conocidos como Alimentos y bebidas lograron vender mercancías por un 
valor de €28,328 junto con un beneficio de €1,349. Los márgenes de beneficio en las diferentes 
categorías se mantienen estables entre el 4.7% y el 4.8%, lo que muestra que la empresa utiliza un enfoque de precios similar.

![distribucion-de-kpis-por-linea-de-producto](./distribucion-de-kpis-por-linea-de-producto.PNG)


### Análisis por género y producto

Los patrones de consumo son diferentes cuando se trata de género. Los niveles de género masculino 
tuvieron la mayor demanda en Deportes y Viajes con €15,568, mientras que Salud y Belleza y Accesorios 
de Moda fueron de €13,669 y €13,468 respectivamente. Las mayores ventas fueron de Alimentos y Bebidas 
entre los Niveles Femeninos con €15,728, seguidas por Hogar y Estilo de Vida con €15,142, mientras 
que Deportes y Viajes ganaron €14,510 en el mismo segmento. 

![3-lineas-de-productos-mas-vendidos-por-ingresos-y-genero](./3-lineas-de-productos-mas-vendidos-por-ingresos-y-genero.PNG)

### Análisis de métodos de pago



La distribución de los pagos muestra una preferencia significativa por el efectivo, representando el 
37% de las transacciones, seguido por las billeteras electrónicas con un 33% y las tarjetas de 
crédito con un 30%.

![distribucion-de-ventas-por-medio-de-pago](./distribucion-de-ventas-por-medio-de-pago.PNG)


### Análisis por tipo de cliente



La distribución entre clientes regulares (50.09%) y miembros (49.91%) muestra un equilibrio casi 
perfecto en la base de clientes.

![distribucion-de-ventas-por-tipo-de-clientes](./distribucion-de-ventas-por-tipo-de-clientes.PNG)


### Análisis por día de la semana



El patrón de ventas semanales muestra picos notables los martes (€27,018), viernes y 
sábados (ambos con €26,007). El domingo mantiene un volumen respetable de €23,434, 
mientras que el jueves registra el volumen más bajo con €17,608. 

![distribucion-de-ventas-por-dia-de-la-semana](./distribucion-de-ventas-por-dia-de-la-semana.PNG)


## Recomendaciones

En consideración de los hallazgos derivados del estudio, las siguientes son recomendaciones importantes clasificadas por áreas estratégicas: 

1. Optimización financiera:
  1.1 Aumentar el margen existente del 4.76% mediante un estudio de costos realizado y negociaciones con proveedores.
  1.2 Establecer un sistema de compras por volumen en las categorías de mejor rendimiento.

2. Segmentación y marketing:
  2.1 Orientar campañas a géneros específicos: Deportes/Viajes para hombres y Comida/Hogar para mujeres.

3. Optimización operativa:
  4.1 Adicionar promociones en ciertos días (especialmente jueves) que generan menos tráfico.
  4.2 Mantener un registro de los niveles de stock por categoría y reponer el stock según el pronóstico de ventas en días específicos.

4. Experiencia del cliente:
  5.1 Rediseñar el diseño de la tienda dependiendo del género objetivo.
  5.2 Establecer un sistema de re-evaluación y revisión.