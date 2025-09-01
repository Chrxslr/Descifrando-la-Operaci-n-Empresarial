# 📊 Proyecto M1 – Descifrando la Operación Empresarial

**Alumno:** Christian Daniel Lara Larios  
**Bootcamp:** Data Analytics – SoyHenry  

Este proyecto tuvo como objetivo analizar la **eficiencia operativa de Global Superstore** a partir de sus datos de ventas en línea entre el **1 de enero de 2013 y el 31 de diciembre de 2014**.  

A través de un proceso de limpieza, transformación y modelado, se construyeron **KPIs, dashboards y tablas dinámicas** que permiten evaluar ventas, costos y rentabilidad desde distintas dimensiones.

---

## 🛠️ Procesos aplicados

1. **Limpieza y normalización de datos**  
   - Eliminación de filas en blanco y columnas irrelevantes.  
   - Corrección de valores atípicos y unificación de formatos.  

2. **Definición de claves primarias**  
   - `ID_Transaction`: clave única compuesta de *OrderID + ProductID*.  

3. **Cálculo de demoras de entrega**  
   - Diferencia entre fecha de pedido y fecha de envío real.  

4. **Generación de variables financieras**  
   - `Cost`: costo unitario.  
   - `Total Cost`: costo unitario × cantidad.  
   - `Total Sales`: ingreso por transacción.  
   - `Margin Profit`: rentabilidad por venta.  

5. **Tablas Dinámicas**  
   Configuradas en una hoja especial (`TD`) para explorar KPIs:  
   - Ventas por Categoría.  
   - Ventas por Sub-categoría.  
   - Ventas y Unidades por Mercado y Región.  
   - Comparativo Anual (2013 vs 2014).  
   - Estacionalidad de Ventas (Unidades por Mes).  
   - Ventas por Método de Envío.  

---

## 🗂️ Navegación en el informe

- **Menú Principal**  
  Interfaz inicial con hipervínculos a cada sección clave:  
  - Resumen de Ventas, Resumen de Costos, Productos, Base de Datos, Estadística Predictiva, Tablas Dinámicas, Tablero de Control.  
  - Mejora la usabilidad con acceso directo a cualquier módulo del proyecto.  

---

## 📊 Dashboards creados

### 🔹 Tablero de Control  
- Facturación por Categoría (pastel).  
- Facturación vs Mercado (columnas agrupadas).  
- Facturación por Año (pastel).  
- Facturación por Sub-Categoría (barras horizontales).  
- Facturación por Región (columnas).  
- Facturación por Método de Envío (líneas).  
➡️ Incluye segmentadores (slicers) para filtrar por año.  

### 🔹 Dashboard de Ventas  
- **KPIs:** costos totales ($456M) y total de transacciones (31,330).  
- **Filtros dinámicos:** Year, Region, Category.  
- **Visualizaciones:**  
  - Ventas mensuales (línea).  
  - Ventas por categoría (pastel).  
  - Ventas por sub-categoría (barras).  
  - Ranking de mercados (tabla dinámica).  
  - KPI adicional: total de ventas por mercado ($455M).  

### 🔹 Dashboard de Costos  
- **KPI:** costos totales consolidados ($306M).  
- **Filtros dinámicos:** Year, Region, Category.  
- **Visualizaciones:**  
  - Costos mensuales (línea).  
  - Costos por prioridad de orden (columnas).  
  - Costos por tipo de envío (columnas).  
  - Tabla dinámica de costos por mercado.  

---

## 🚀 Tecnologías y herramientas
- **Excel / Google Sheets** (limpieza, cálculos y dashboards).  
- **Tablas dinámicas, fórmulas avanzadas y segmentadores**.  
- **Diseño de dashboards interactivos** para análisis financiero y comercial.  

---

## 📌 Conclusiones
- La categoría **Technology** y los mercados **North America** y **LATAM** son los principales generadores de ingresos.  
- Los **costos logísticos** muestran diferencias significativas según el modo de envío.  
- Existe una marcada **estacionalidad mensual**, con picos de ventas en determinados meses.  
- Los dashboards permiten evaluar de manera rápida la rentabilidad, costos y desempeño por región, facilitando la **toma de decisiones estratégicas**.  

---

✍️ *Este proyecto representó un ejercicio integral de análisis de datos y storytelling en Excel, combinando limpieza, modelado y visualización para entender la operación de una empresa global.*
