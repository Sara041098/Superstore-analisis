# Superstore-analisis

Análisis de ventas y creación de un dashboard e informe interactivo en Power BI utilizando el dataset Superstore

## 📊 Descripción del proyecto

Proyecto de análisis de datos desarrollado en Power BI a partir del dataset Superstore.

El objetivo del proyecto es analizar el comportamiento de las ventas, los beneficios y los márgenes desde diferentes perspectivas, identificando patrones por categoría de producto, región y cliente, así como la relación entre los descuentos aplicados y los resultados obtenidos.

El proyecto combina un **dashboard ejecutivo de una página** con un **informe interactivo de análisis detallado**, incorporando navegación entre páginas, filtros e interacción entre visualizaciones.

## 📝 Nota metodológica

El dataset proporciona información sobre ventas, descuentos y beneficios, pero no incluye el detalle de la estructura de costes ni de la inversión realizada por la empresa.

Por ello, las conclusiones se centran en el análisis del beneficio y del margen de beneficio observados.

Las referencias a costes o eficiencia económica deben interpretarse como **hipótesis de negocio derivadas de los patrones detectados en los datos y no como hechos demostrados**.

## 🎯 Objetivos del análisis

- Analizar la evolución de las ventas y los beneficios a lo largo del tiempo.
- Comparar el rendimiento de las diferentes categorías y subcategorías de productos.
- Analizar las ventas, beneficios y márgenes por región.
- Identificar clientes con mejores y peores resultados.
- Analizar el comportamiento de los descuentos y su relación con el beneficio.
- Detectar patrones y oportunidades de mejora a partir de los datos.
- Transformar los resultados obtenidos en insights y posibles hipótesis de negocio.

## 🛠️ Herramientas utilizadas

- **Power BI**
- **Power Query** – preparación y transformación de los datos.
- **DAX** – creación de medidas y cálculos.
- **Visualización y análisis de datos**

## 📈 Estructura del proyecto

### 1. Dashboard

Dashboard ejecutivo de una página diseñado para ofrecer una visión general y rápida de los principales indicadores del negocio.

Incluye:

- Ventas totales.
- Beneficio total.
- Margen de beneficio.
- Número de pedidos únicos.
- Número de clientes únicos.
- Evolución temporal de ventas y beneficio.
- Ventas y beneficio por categoría.
- Ventas y beneficio por región.
- Margen de beneficio por categoría y región.
- Descuento medio por región.
- Top 5 clientes por beneficio.

### 2. Informe interactivo

El informe profundiza en los resultados obtenidos a través de diferentes perspectivas de análisis.

#### Resumen general

Análisis global de:

- Evolución temporal de las ventas y el beneficio.
- Ventas por categoría.
- Beneficio por categoría.
- Margen de beneficio por categoría.

#### Análisis por categoría – Furniture

Análisis detallado de la categoría Furniture, incluyendo:

- Beneficio y margen por subcategoría de Furniture.
- Ventas y beneficio por subcategoría de Furniture.
- Ventas por región.
- Descuento medio de Furniture por región.

Esta página permite analizar con mayor detalle cómo se comportan las diferentes subcategorías y cómo varían los resultados según la región.

#### Análisis de clientes y beneficio

Análisis centrado en el comportamiento de los clientes:

- Distribución del beneficio por segmento.
- Top 5 clientes con mayores beneficios.
- Clientes con mayores pérdidas.
- Descuento medio de los clientes con mejores resultados.
- Descuento medio de los clientes con peores resultados.

#### Análisis regional – Región Central

Análisis específico de la región Central mediante:

- Ventas totales.
- Beneficio total.
- Margen de beneficio.
- Beneficio por subcategoría.
- Descuento medio por subcategoría.

## 🔎 Principales insights

### 1. Relación entre descuentos y beneficio

El análisis muestra que los descuentos elevados pueden estar asociados a una reducción significativa del beneficio en determinadas subcategorías.

En algunos casos, la aplicación de descuentos muy agresivos llega a generar márgenes negativos, lo que indica que el descuento no siempre se traduce en un incremento suficiente del volumen de ventas como para compensar su impacto sobre el beneficio.

### 2. Comportamiento de productos con márgenes reducidos

Algunas subcategorías presentan una mayor sensibilidad frente a los descuentos: incluso reducciones moderadas del precio pueden deteriorar significativamente el margen observado.

Este patrón podría ser compatible con una estructura de costes elevada, aunque el dataset disponible no proporciona información suficiente para confirmar esta hipótesis.

### 3. Región Central

La región Central destaca por su elevado volumen de ventas, pero presenta un margen de beneficio inferior al de otras regiones.

El análisis de los descuentos y del beneficio por subcategoría permite identificar posibles áreas de mejora en la gestión comercial de la región.

### 4. Diferencias entre ventas y beneficio

El análisis muestra que un mayor volumen de ventas no implica necesariamente un mayor beneficio.

Por ello, resulta importante analizar conjuntamente las ventas, el beneficio y el margen para evaluar el rendimiento de las diferentes categorías y regiones.

### 5. Clientes

El análisis de clientes permite identificar aquellos que generan mayores beneficios y aquellos que presentan resultados negativos, proporcionando una perspectiva adicional para evaluar el rendimiento comercial.

## 💡 Recomendaciones de negocio

A partir de los patrones observados en los datos, se plantean las siguientes hipótesis y posibles líneas de actuación:

- Revisar la aplicación de descuentos especialmente elevados en las subcategorías donde generan márgenes negativos.
- Evitar aplicar descuentos de forma indiscriminada y analizar su impacto individual por producto o subcategoría.
- Analizar las causas del menor margen observado en la región Central a pesar de su elevado volumen de ventas. Descuentos, productos con altos costes...
- Priorizar el seguimiento de clientes con resultados negativos y analizar las condiciones comerciales asociadas.
- Evaluar las estrategias comerciales sobretodo de la región Central utilizando conjuntamente ventas, beneficio y margen, en lugar de utilizar únicamente el volumen de ventas como indicador de rendimiento.

Estas recomendaciones deben interpretarse como **hipótesis de negocio derivadas del análisis de los datos** y no como conclusiones causales definitivas.


## 🖼️ Vista previa

### Dashboard

![Dashboard](images/dashboard.png)

### Resumen general

![Resumen general](images/resumen-general.png)

### Análisis por categoría (Furniture)

![Análisis por categoría](images/analisis-categoria.png)

### Análisis de clientes y beneficio

![Análisis de clientes](images/analisis-clientes.png)

### Análisis regional

![Análisis regional](images/analisis-regional.png)


## 📁 Archivo Power BI

El proyecto completo está disponible en el archivo:

**`Superstore_Analisis.pbix`**

El archivo contiene tanto el dashboard ejecutivo como el informe interactivo desarrollado en Power BI.


## 👩‍💻 Sobre el proyecto

Este proyecto forma parte de mi portfolio de análisis de datos y tiene como objetivo demostrar el uso de Power BI para transformar datos en información útil para la toma de decisiones.

El análisis combina preparación de datos, creación de medidas, visualización interactiva y generación de insights de negocio.
