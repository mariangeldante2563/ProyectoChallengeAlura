# ProyectoChallengeAlura
# Análisis de Ventas - Alura Store Latam
# Objetivo del Proyecto
Análisis completo de datos de ventas de 4 tiendas online para identificar oportunidades de negocio y optimizar estrategias comerciales, con foco en determinar la mejor tienda para que un nuevo vendedor (Sr. João) inicie sus operaciones.
# Datos Analizados
4 tiendas (Tienda_1, Tienda_2, Tienda_3, Tienda_4)

9,436 transacciones procesadas

Período: 2020-2022

Variables analizadas: Productos, categorías, precios, costos de envío, calificaciones, lugares de compra, métodos de pago
# Análisis Realizados
1. Análisis de Facturación
Ventas totales por tienda

Ticket promedio y cantidad de transacciones

Participación en el mercado total

2. Ventas por Producto y Categoría
Top 5 productos más vendidos por tienda

Top 5 categorías más rentables

Distribución geográfica de ventas

3. Satisfacción del Cliente
Calificación promedio por tienda

Distribución de calificaciones (1-5 estrellas)

Relación entre satisfacción y ubicación

4. Eficiencia Operativa
Costos de envío promedio

Relación envío/precio

Logística por ubicación geográfica
# Hallazgos Clave
Ranking de Ventas Totales:
Tienda_1: $2.1M (31.8% participación)

Tienda_2: $1.8M (27.3%)

Tienda_3: $1.5M (22.7%) ← RECOMENDADA

Tienda_4: $1.2M (18.2%)

Calificación de Clientes:
Tienda_4: 4.3/5.0 (mejor satisfacción)

Tienda_3: 4.2/5.0 (segunda mejor)

Tienda_1: 3.9/5.0

Tienda_2: 3.8/5.0

Eficiencia en Envíos:
Tienda_3: 8.2% (mejor relación envío/precio)

Tienda_2: 9.5%

Tienda_4: 9.9%

Tienda_1: 10.7%

#  Recomendación Principal
Tienda_3 es la opción óptima para el Sr. João porque ofrece:

✅ Balance ideal entre volumen y competencia

✅ Clientes satisfechos que valoran calidad

✅ Costos logísticos eficientes

✅ Diversificación geográfica

✅ Entorno favorable para nuevos vendedores
# Cómo Ejecutar el Código
En Google Colab:
Abre Google Colab

Crea un nuevo notebook

Copia y ejecuta este código inicial:
# Instalación de librerías
!pip install pandas matplotlib seaborn numpy

# Importación
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import numpy as np

# Carga de datos
urls = [
    "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_1%20.csv",
    "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_2.csv",
    "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_3.csv",
    "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_4.csv"
]

# Las celdas siguientes contienen el análisis completo
# Estructura del Notebook:
Importación y limpieza de datos

1. Análisis de facturación por tienda

2. Ventas por producto y categoría

3. Análisis de satisfacción del cliente

4. Eficiencia operativa (costos de envío)

5. Visualizaciones y gráficos comparativos

6. Recomendaciones estratégicas
# Requisitos Técnicos

Plataforma: Google Colab (recomendado) o Jupyter Notebook

Python: 3.7+

Librerías principales: pandas, matplotlib, seaborn, numpy

Tiempo de ejecución: 2 Y 3 minutos para análisis completo
# Para Nuevos Vendedores
Comenzar en Tienda_3 para mejor balance riesgo/beneficio

Enfocarse en electrónicos y electrodomésticos (mayor margen)

Priorizar calidad sobre precio (cliente Tienda_3 lo valora)
