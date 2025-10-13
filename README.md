# Power BI – Análisis y Visualización de Datos

## Descripción del proyecto
En este proyecto se trabajó con **Power BI** para crear paneles interactivos de análisis empresarial a partir de una base de datos de una empresa de **ventas online**.  
El objetivo fue **aplicar los conocimientos de modelado, DAX y visualización** para obtener una lectura clara, estética y funcional de los datos.

Se desarrollaron tres paneles (uno por nivel), cada uno centrado en objetivos específicos de negocio, aplicando **buenas prácticas de diseño y análisis**.

---

## Nivel 1 – Indicadores y análisis general de ventas

### Procesos realizados
1. **Importación y modelado del conjunto de datos** previamente trabajado en MySQL.  
   - Ajuste de relaciones y validación de la integridad del modelo.  
   - Limpieza de datos y creación de columnas calculadas.

2. **Creación de indicadores KPI:**
   - Suma total del *amount* anual con meta de **2.600.000 $ por año**.  
   - Promedio de transacciones del **2021** y **2022**, con objetivos de **260 $** en ambos casos.  
   - Cantidad de empresas por país (mínimo **3 empresas por país**).

3. **Análisis temporal:**
   - Gráfico de columnas agrupadas con el total de ventas mensuales de los últimos 5 años.  
   - Objetivo: **220.000 $ por mes**.

4. **Análisis de usuarios:**
   - Columna combinada de nombre completo.  
   - Cálculo de edad.  
   - Conversión de montos (€ → $).  
   - Detección de usuarios con promedios ≥ 300 € o ≥ 320 $.

---

## Nivel 2 – Tendencias y análisis geográfico

### Procesos realizados
1. **Análisis de tendencia mensual (2018–2019):**
   - Creación de medidas DAX para calcular variaciones de ventas.  
   - Identificación de meses que no alcanzaron el objetivo de **220.000 $**.  
   - Visualización comparativa entre los dos años.

2. **Focalización en Alemania:**
   - Cálculo de la media de pedidos y comparación con la meta de **260 $**.  
   - Representación mediante indicadores configurados con valores mínimos y máximos (200–300 $).  
   - Panel dedicado al análisis específico del mercado alemán.

---

## Nivel 3 – Enriquecimiento del modelo y análisis avanzado

### Procesos realizados
1. **Integración de nuevas tablas:**
   - Incorporación de **usuarios** y **productos** desde archivos CSV mediante Power Query.  
   - Creación de relaciones con la tabla de hechos `transactions`.  
   - Desglose de la columna `product_ids` para normalizar la relación entre transacciones y productos.

2. **Visualizaciones desarrolladas:**
   - Medidas estadísticas clave sobre las variables más relevantes.  
   - Cantidad total de productos comprados por usuario.  
   - Media de compras por usuario (destacando quienes superan los 260 $).  
   - Producto más caro y más barato adquirido por cada cliente.  
   - Distribución geográfica de usuarios mediante mapa dinámico.

3. **Optimización visual:**
   - Ajustes en formato, colores y títulos descriptivos para mejorar la legibilidad.  
   - Panel limpio, con foco en **claridad y eficiencia comunicativa**.

---

## Herramientas utilizadas
- **Power BI Desktop**
- **Power Query**
- **Lenguaje DAX (Data Analysis Expressions)**
- **Modelado relacional SQL**
- **CSV Data Imports**

---

## Resultados
El trabajo final consistió en tres paneles independientes, cada uno en una sola página de Power BI, donde se integraron:
- Indicadores clave (KPIs) con metas empresariales.  
- Gráficos de barras, columnas y medidores.  
- Medidas DAX personalizadas.  
- Visualizaciones interactivas y coherentes con objetivos de negocio.  

El proyecto permitió aplicar una visión **analítica, estructurada y visualmente profesional** de los datos.

