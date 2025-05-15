# Análisis de Ventas por Tienda "Alura Store Challenge"

Este proyecto realiza un análisis detallado de los datos de ventas provenientes de cuatro tiendas, identificando patrones, métricas clave y proporcionando recomendaciones estratégicas para optimizar la rentabilidad.

## Descripción del Proyecto

El análisis incluye:
- Exploración inicial de los datos.
- Generación de métricas descriptivas (ingresos, ventas, calificaciones promedio, etc.).
- Visualización gráfica para comprender patrones clave.
- Identificación de productos más y menos vendidos.
- Evaluación de costos y rentabilidad por categoría de productos.
- Recomendaciones estratégicas basadas en los hallazgos.

El proyecto se desarrolló en Python y se documentó utilizando Google Colab. Los resultados finales se comparten en forma de gráficos y texto dentro del notebook y a través de este repositorio.

## Estructura del Proyecto

- `data/`: Contiene los archivos CSV utilizados como base de datos.
- `notebooks/`: Notebook principal en Google Colab con el análisis completo.
- `visualizations/`: Gráficos generados durante el análisis.
- `README.md`: Este archivo, que describe el propósito y estructura del proyecto.

## Herramientas Utilizadas

- **Lenguaje:** Python  
- **Librerías principales:**
  - `pandas` para el procesamiento de datos.
  - `matplotlib` y `seaborn` para visualización de datos.
  - `numpy` para cálculos adicionales.
- **Entorno de desarrollo:** Google Colab  
- **Control de versiones:** Git y GitHub.

## Resultados Principales

### Facturación por Tienda
| Tienda | Facturación Total | Contribución (%) |
|--------|-------------------|------------------|
| Tienda 1 | $1,150,880,400.00 | 26.1% |
| Tienda 2 | $1,116,343,500.00 | 25.4% |
| Tienda 3 | $1,098,019,600.00 | 24.9% |
| Tienda 4 | $1,038,375,700.00 | 23.6% |

### Productos Más y Menos Vendidos
| Tienda | Más Vendido          | Menos Vendido        |
|--------|----------------------|----------------------|
| Tienda 1 | Muebles (465)        | Artículos para el hogar (171) |
| Tienda 2 | Muebles (442)        | Artículos para el hogar (181) |
| Tienda 3 | Muebles (499)        | Instrumentos musicales (177)  |
| Tienda 4 | Muebles (480)        | Instrumentos musicales (170)  |

### Recomendaciones Clave
- **Cierre de la Tienda 4:** Redistribuir operaciones para maximizar la rentabilidad.
- **Eliminación de categorías menos vendidas:** Artículos para el hogar e Instrumentos musicales.
- **Optimización de inventarios:** Priorizar Electrónicos y Muebles por su alta rentabilidad.
