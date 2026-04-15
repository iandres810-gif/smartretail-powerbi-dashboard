# SmartRetail Power BI Dashboard

Proyecto de análisis y visualización en Power BI orientado al monitoreo de ventas, inventario y cumplimiento de metas para la empresa ficticia SmartRetail.

## Objetivo
Construir una solución visual que permita apoyar la toma de decisiones gerenciales mediante reportes interactivos, KPIs ejecutivos, filtros, jerarquías y alertas sobre indicadores críticos.

## Componentes desarrollados
El proyecto se organizó en tres niveles:

- **Reporte de ventas**: análisis por categoría, tienda y evolución temporal de las ventas.
- **Reporte de inventario**: seguimiento de stock disponible, productos con bajo stock y detalle por producto y tienda.
- **Dashboard ejecutivo**: integración de indicadores clave para una lectura gerencial rápida.

## KPIs principales
- Total ventas
- Productos con stock bajo
- Margen promedio estimado

## Interactividad implementada
- Segmentadores por fecha, tienda y categoría
- Jerarquía de fechas para exploración por año, trimestre, mes y día
- Filtros cruzados entre visuales
- Alerta visual de stock crítico cuando el stock es menor a 30 unidades

## Modelo de datos
El modelo fue construido con una lógica de dimensiones y hechos:

- `Dim_fecha`
- `Dim_tienda`
- `Dim_productos`
- `hechos_ventas_combinacion`
- `hechos_inventario`
- `Medidas_KPI`

## Medidas destacadas
- `VentasTotales`
- `StockTotalDisponible`
- `ProductosStockBajo`
- `PorcentajeStockBajo`
- `MargenPromedioEstimado`
- `AlertaStock`

## Archivos del proyecto
- `PRUEBA.docx`: informe explicativo completo del desarrollo
- `.pbix`: archivo de Power BI
- Carpeta `img/`: capturas de los dashboards y del modelo de datos
- Carpeta `data/`: archivos de datos utilizados

## Autor
**Ignacio Pizarro Hurtado**  
Ingeniero Civil Industrial | Análisis de datos, BI y control de gestión | Power BI, Excel, Python y SQL

## Contacto
- LinkedIn: https://www.linkedin.com/in/ipizarroh/
