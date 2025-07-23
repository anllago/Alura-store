# Alura-store
Proyecto Análisis tiendas Alura 

# 🛍️ Análisis Comparativo de Tiendas - Challenge Data Science LATAM

## 📌 Objetivo

Realizar un análisis comparativo entre las tiendas **Tienda 1**, **Tienda 2**, **Tienda 3** y **Tienda 4** utilizando métricas clave como:
- Facturación total
- Ventas por categoría
- Calificación promedio de clientes
- Productos más y menos vendidos
- Costo promedio de envío

El fin de este estudio es identificar cuál de las tiendas representa la mejor opción para ser vendida, basándose en sus fortalezas y debilidades operativas.

---

## 📊 Indicadores Analizados

### ✅ Facturación Total
- **Tienda 1**: USD 1,151M (mayor facturación)
- **Tienda 2**: USD 1,116M
- **Tienda 3**: USD 1,098M
- **Tienda 4**: USD 1,038M (menor facturación)

### ✅ Calificación Promedio
- **Tienda 3**: 4.05 (mejor calificación)
- **Tienda 2**: 4.04
- **Tienda 4**: 4.00
- **Tienda 1**: 3.98 (más baja, aunque con diferencia mínima)

### ✅ Costo Promedio de Envío
- **Tienda 4**: USD 23.459 (más bajo)
- **Tienda 3**: USD 24.806
- **Tienda 2**: USD 25.216
- **Tienda 1**: USD 26.019 (más alto)

### ✅ Ranking de Productos (más vendidos vs. menos vendidos)
- **Tienda 2**: Puntaje -1 (mejor balance; tiene los productos más vendidos)
- **Tienda 4**: Puntaje -4 (buen rendimiento de productos)
- **Tienda 3**: Puntaje -6 (aceptable; evita productos "flop")
- **Tienda 1**: Puntaje -9 (peor balance; presencia de productos de baja rotación)

---

## 🛒 Resumen por Tienda

### Tienda 1
- ✅ Mayor facturación total
- ❌ Peor calificación promedio
- ❌ Mayor costo de envío
- ❌ Peor puntaje de productos
- ✅ Buena cobertura geográfica

### Tienda 2
- ✅ Alto ingreso y calificación
- ✅ Productos más exitosos
- ❌ Tiene el producto menos vendido absoluto
- ❌ Segundo mayor costo de envío

### Tienda 3
- ✅ Mejor calificación
- ✅ Costos competitivos
- ❌ No tiene productos en el Top 5
- ❌ Tercer lugar en ingresos

### Tienda 4
- ✅ Costo de envío más bajo
- ✅ Buen puntaje de productos
- ❌ Menor facturación
- ❌ Cobertura geográfica débil (con excepciones en Bogotá y Barranquilla)

---

## 🧠 Análisis Estratégico para Desinversión

### Opciones consideradas:

- **Vender Tienda 4**: Libera recursos, pero se pierde eficiencia logística.
- **Vender Tienda 3**: Riesgoso, ya que es la más estable y con mejor satisfacción.
- **Vender Tienda 2**: Se renuncia al mayor potencial en productos estrella.
- **Vender Tienda 1**: A pesar de ser la que más ingresos genera, podría representar una oportunidad para capitalizar su valor actual y evitar riesgos futuros.

---

## ✅ Recomendación Final

**Vender Tienda 1**

### Justificación:
Aunque genera los mayores ingresos, **Tienda 1** muestra debilidades estructurales significativas:
- Mayor costo operativo (envío)
- Bajo desempeño en rotación de productos
- Calificación más baja del grupo

Venderla en su punto más alto de valor permitiría al Sr. Juan obtener el mayor retorno por su activo más valioso y redirigir recursos hacia tiendas con perfiles más equilibrados como **Tienda 2** (dinámica y rentable) y **Tienda 3** (estable y bien valorada por los clientes).

---

## 🗂️ Estructura del Proyecto

 📁 base-de-datos-challenge1-latam
 │
 
 ├── tienda_1.csv
 
 ├── tienda_2.csv
 
├── tienda_3.csv

├── tienda_4.csv

│

├── análisis_visualizaciones.ipynb

└── README.md ← (este archivo)


---

## 🚀 Herramientas Utilizadas

- Python (Pandas, Matplotlib)
- Jupyter/Google Colab
- Visualización con gráficos de barras
- Análisis exploratorio de datos (EDA)
"""

# Guardar en archivo
with open("README.md", "w", encoding="utf-8") as f:
    f.write(readme_content)
