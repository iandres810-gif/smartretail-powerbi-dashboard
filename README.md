# SmartRetail Power BI Dashboard

Proyecto de análisis y visualización desarrollado en **Power BI** para la empresa ficticia **SmartRetail**, orientado al monitoreo de **ventas**, **inventario** y **cumplimiento de metas** mediante reportes interactivos, KPIs ejecutivos y alertas visuales.

## Objetivo del proyecto

Desarrollar una solución visual que permita apoyar la toma de decisiones gerenciales a partir de información clave del negocio, incorporando filtros, jerarquías temporales, segmentadores, medidas DAX e indicadores críticos de seguimiento.

## Solución implementada

La solución fue organizada en tres niveles de análisis:

- **Dashboard de Ventas:** análisis por categoría, tienda y evolución temporal de las ventas.
- **Dashboard de Inventario:** monitoreo de stock disponible, productos con bajo stock, distribución del estado del inventario y detalle por producto y tienda.
- **Dashboard Ejecutivo:** integración de los principales indicadores de ventas e inventario en una sola vista para apoyar decisiones de gerencia.

## KPIs principales

- **Total ventas**
- **Productos con stock bajo**
- **Margen promedio estimado**

## Interactividad implementada

- Segmentadores por **fecha**, **tienda** y **categoría**
- Jerarquía de fechas para exploración por **año, trimestre, mes y día**
- Filtros cruzados entre visuales
- Filtros a nivel de página y de objeto visual
- Alerta visual de stock crítico cuando el stock es **menor a 30 unidades**

## Modelo de datos

El modelo fue estructurado con una lógica de **dimensiones y hechos**:

### Tablas de dimensiones
- `Dim_fecha`
- `Dim_tienda`
- `Dim_productos`

### Tablas de hechos
- `hechos_ventas_combinacion`
- `hechos_inventario`

### Tabla de medidas
- `Medidas_KPI`

## Medidas y cálculos destacados

Entre las medidas y cálculos utilizados en Power BI se encuentran:

- `VentasTotales`
- `TotalVentas`
- `StockTotalDisponible`
- `ProductosTotales`
- `ProductosStockBajo`
- `PorcentajeStockBajo`
- `CostoEstimado`
- `MargenTotalEstimado`
- `MargenPromedioEstimado`
- `AlertaStock`
- `ColorAlertaStock`

Además, se creó la columna calculada **Estado Inventario** para clasificar el stock en niveles **Bajo**, **Normal** y **Alto**.

## Archivos del repositorio

Este repositorio contiene los siguientes archivos:

- `PRUEBA.pbix`: archivo principal del proyecto en Power BI
- `INFORME SMARTRETAIL.pdf`: informe explicativo del desarrollo
- `ventas.csv`: dataset de ventas
- `inventario.xlsx`: dataset de inventario
- `DASHBOARD VENTAS.png`: captura del dashboard de ventas
- `DASHBOARD INVENTARIO.png`: captura del dashboard de inventario
- `DASHBOARD EJECUTIVO.png`: captura del dashboard ejecutivo
- `MODELO DE DATOS.png`: captura del modelo de datos implementado

## Evidencia visual

### Dashboard de ventas
![Dashboard de ventas](DASHBOARD%20VENTAS.png)

### Dashboard de inventario
![Dashboard de inventario](DASHBOARD%20INVENTARIO.png)

### Dashboard ejecutivo
![Dashboard ejecutivo](DASHBOARD%20EJECUTIVO.png)

### Modelo de datos
![Modelo de datos](MODELO%20DE%20DATOS.png)

## Herramientas utilizadas

- **Power BI**
- **DAX**
- **Excel**
- **CSV**

## Principales aprendizajes del proyecto

Este proyecto permitió aplicar conocimientos de:

- modelado de datos
- creación de medidas DAX
- construcción de dashboards
- diseño de visualizaciones ejecutivas
- uso de interactividad en Power BI
- generación de alertas orientadas a la toma de decisiones

## Autor

**Ignacio Pizarro Hurtado**  
Ingeniero Civil Industrial | Análisis de datos, BI y control de gestión | Power BI, Excel, Python y SQL

## Contacto

- **LinkedIn:** https://www.linkedin.com/in/ipizarroh/
- **GitHub:** https://github.com/iandres810-gif
