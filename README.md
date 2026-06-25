# Dashboard de Empleos en Datos con Power BI

<a href="TU_LINK_DE_POWER_BI_SERVICE_ACA" target="_blank">
  <img src="Resources/images/Project1_Dashboard_Overview.gif" alt="GIF del Dashboard de Empleos en Datos">
</a>

## Introducción

Este dashboard fue creado para **personas en búsqueda de empleo, en transición de carrera o buscando un cambio profesional**, con el fin de resolver un problema común: la información sobre el mercado laboral de datos está dispersa y es difícil de comprender. Utilizando un conjunto de datos reales de ofertas de empleo de ciencia de datos del 2024 (que incluye títulos, salarios y ubicaciones), este proyecto proporciona una interfaz única y fácil de usar para explorar las tendencias del mercado y las compensaciones.

### Archivo del Dashboard
Puedes encontrar el archivo original del dashboard aquí: [`Data_Jobs_Dashboard.pbix`](Data_Jobs_Dashboard.pbix).  

## Habilidades Demostradas

Este proyecto representó un recorrido completo a través de las funcionalidades clave de Power BI. A continuación, se detallan las herramientas y conceptos dominados:

- **⚙️ Transformación de Datos (ETL) con Power Query:** Limpieza, modelado y preparación de los datos crudos para el análisis mediante la gestión de valores en blanco, cambio de tipos de datos y creación de nuevas columnas calculadas.
  
- **🧮 Medidas Implicitas y Explícitas (DAX):** Formulación de medidas para derivar insights clave y KPIs fundamentales como la `Mediana Salarial Anual` y el `Recuento de Empleos`.
  
- **📊 Gráficos Esenciales:** Uso estratégico de gráficos de **Columnas, Barras, Líneas y Áreas** para comparar la cantidad de puestos y realizar el seguimiento de tendencias a lo largo del tiempo.
  
- **🗺️ Análisis Geoespacial:** Implementación de **Mapas** para visualizar la distribución global de las ofertas laborales.
  
- **🔢 Indicadores KPI y Tablas:** Uso de **Tarjetas** para resaltar métricas clave y **Tablas** para proporcionar datos detallados y ordenables.
  
- **🎨 Diseño de Dashboards:** Creación de una interfaz intuitiva y visualmente atractiva, explorando estructuras de gráficos tanto comunes como avanzadas para contar la historia de los datos de la mejor manera.
  
- **🖱️ Reportes Interactivos:**
  - **Segmentadores (Slicers):** Filtros dinámicos para segmentar el reporte por Título de Trabajo.
  - **Botones y Marcadores (Bookmarks):** Configuración de una experiencia de navegación fluida y amigable.
  - **Obtención de Detalles (Drill-Through):** Permite al usuario navegar desde un resumen general hasta una vista contextual y detallada.

---

## Estructura del Dashboard

*Este reporte se divide en dos páginas distintas para proporcionar tanto un resumen de alto nivel como un análisis en profundidad.*

### Página 1: Vista General del Mercado

![Dashboard Página 1](Resources/images/Project1_Dashboard_Page1.gif)  

Este es el centro de control del mercado laboral de datos. Muestra KPIs clave como el total de ofertas de empleo, medianas salariales y los títulos de trabajo más demandados para ofrecer una comprensión rápida y de un solo vistazo de lo que está ocurriendo en el sector.

### Página 2: Detalle por Título (Drill Through)

![Dashboard Página 2](Resources/images/Project1_Dashboard_Page2.gif)  

Esta es la página de análisis profundo. Desde el dashboard principal, puedes aplicar *drill-through* a esta vista para obtener detalles específicos de un solo puesto de trabajo, incluyendo rangos salariales, estadísticas de trabajo remoto (Home Office), las plataformas de reclutamiento más populares y un mapa global con la ubicación de las vacantes.

---

## Conclusión

Este dashboard demuestra cómo Power BI puede transformar datos brutos de ofertas de empleo en una herramienta analítica de gran valor para el desarrollo profesional. Permite a los usuarios segmentar, filtrar y profundizar en los datos para tomar decisiones informadas sobre su futuro laboral.
