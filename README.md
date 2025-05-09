# Challenge_Alura_Store
# Análisis de Rendimiento de Tiendas del Sr. Juan

**Proyecto:** Análisis comparativo del rendimiento de cuatro tiendas propiedad del Sr. Juan con el objetivo principal de identificar la tienda con menor desempeño general y proporcionar información clave para la toma de decisiones estratégicas.

## 🎯 Objetivo Principal

Identificar la tienda con el rendimiento general más bajo para informar decisiones estratégicas, potencialmente incluyendo la optimización de operaciones o la reconsideración de la viabilidad de dicha tienda.

## 💾 Datos

Los datos utilizados para este análisis provienen de archivos CSV ubicados en la carpeta `base-de-datos-challenge1-latam` del repositorio público de Alura Latam en GitHub: [alura-es-cursos/challenge1-data-science-latam](https://github.com/alura-es-cursos/challenge1-data-science-latam). Estos archivos contienen información detallada sobre:

* **Ventas:** Registros de transacciones de cada tienda.
* **Productos:** Detalles de los artículos ofrecidos.
* **Calificaciones:** Feedback y puntuaciones de los clientes para cada tienda.
* **Costos de Envío:** Gastos asociados a la logística de cada tienda.

## 🛠️ Análisis Detallado

El análisis se estructuró en las siguientes etapas para evaluar el rendimiento de cada tienda desde diversas perspectivas:

1.  **Análisis de Facturación:** Cálculo y comparación del ingreso total generado por cada una de las cuatro tiendas, visualizado mediante un gráfico de pastel para facilitar la comparación de la contribución de cada tienda al ingreso total.
2.  **Análisis de Ventas por Categoría:** Evaluación del volumen de ventas (cantidad) y el valor total de las ventas por categoría de producto en cada tienda, utilizando gráficos de barras para identificar las categorías de productos más y menos exitosas en cada ubicación.
3.  **Evaluación de la Calificación Promedio:** Cálculo de la calificación promedio otorgada por los clientes a cada tienda, proporcionando una perspectiva sobre la satisfacción del cliente en cada ubicación.
4.  **Identificación de Productos Destacados y de Bajo Rendimiento:** Determinación de los productos con la mayor y menor cantidad de unidades vendidas en cada tienda, ofreciendo insights sobre las preferencias de los clientes y posibles áreas de optimización del inventario.
5.  **Análisis de Costos de Envío:** Cálculo y visualización del costo de envío promedio por tienda a través de un gráfico de línea, permitiendo comparar la eficiencia logística entre las diferentes ubicaciones.

## 🐍 Métodos de Python Utilizados

Para llevar a cabo este análisis de manera eficiente y efectiva, se utilizaron las siguientes funcionalidades clave de Python:

* **Listas:** Estructuras de datos fundamentales para almacenar y manipular colecciones ordenadas de elementos, utilizadas en diversas etapas del procesamiento de datos.
* **Tuplas:** Estructuras de datos inmutables para almacenar secuencias de elementos, garantizando la integridad de datos que no deben ser modificados.
* **Funciones Lambda:** Funciones anónimas y de una sola expresión, empleadas para realizar transformaciones de datos rápidas y concisas dentro de otras funciones.
* **Pandas DataFrames:** La librería Pandas proporcionó la estructura de datos DataFrame, esencial para la manipulación, limpieza, transformación y análisis tabular de los datos provenientes de los archivos CSV.

## 💡 Recomendaciones Clave

Basado en el análisis realizado, se sugiere una **evaluación exhaustiva de la viabilidad de la Tienda 4**, la cual presenta un rendimiento financiero significativamente menor en comparación con las otras tiendas. A pesar de su buena calificación por parte de los clientes y costos de envío competitivos, su baja facturación general podría indicar problemas subyacentes en la estrategia de ventas, la oferta de productos o la eficiencia operativa.

Se recomienda **mantener un monitoreo continuo del rendimiento de todas las tiendas** y realizar análisis más profundos en áreas específicas (como las categorías de productos de bajo rendimiento en la Tienda 4 o las estrategias de venta exitosas en las tiendas con mayor facturación) para informar futuras decisiones estratégicas.

## ⚙️ Herramientas

* **Python:** Lenguaje de programación principal utilizado para la manipulación y el análisis de datos.
* **Pandas:** Librería fundamental para la creación y manipulación de DataFrames.
* **Matplotlib:** Librería para la generación de visualizaciones de datos estáticas.
* **Folium:** Librería para la creación de mapas interactivos (aunque no se mencione explícitamente en el análisis, podría haber sido utilizada para visualizar la ubicación de las tiendas o datos geográficos relacionados).

## 🚀 Cómo Ejecutar el Análisis

1.  **Acceder al Proyecto:** `cd challenge1-data-science-latam/base-de-datos-challenge1-latam` (o la ubicación del notebook)
2.  **Abrir en Google Colab:** Abrir el archivo `Análisis de Tiendas.ipynb` utilizando Google Colab ([https://colab.research.google.com/](https://colab.research.google.com/)).
3.  **Ejecutar el Notebook:** Ejecutar secuencialmente todas las celdas del cuaderno para replicar el análisis y visualizar los resultados.

