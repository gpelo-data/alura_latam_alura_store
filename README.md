# 📊 Challenge Data Science - Alura Latam 

## Análisis de Rentabilidad de tiendas de AluraStore

### 🎯 Descripción del Proyecto

Este proyecto forma parte del **Challenge de Data Science de Alura Latam**, donde se realiza un análisis exhaustivo de cuatro tiendas para determinar cuál es la menos rentable y recomendar su venta al señor Juan, quien necesita liberar capital para un nuevo emprendimiento.

### 🧩 Contexto del Desafío

El señor Juan es propietario de 4 tiendas y desea vender una de ellas para iniciar un nuevo proyecto. El objetivo es analizar los datos de ventas, costos y rendimiento de cada tienda para identificar cuál tiene el peor desempeño y debería ser vendida.

### 📁 Estructura del Proyecto

```
alura_latam_alura_store/
│
├── datos/
│   ├── tienda1.csv
│   ├── tienda2.csv
│   ├── tienda3.csv
│   └── tienda4.csv
│
└── challenge1-data-science-latam.ipynb
```

### 🛠️ Tecnologías Utilizadas

- **Python 3.11+**
- **Pandas** - Manipulación y análisis de datos
- **NumPy** - Operaciones numéricas
- **Matplotlib** - Visualización de datos
- **Seaborn** - Gráficos estadísticos
- **Plotly Express** - Visualizaciones interactivas y geográficas

### 📊 Análisis Realizados

El notebook incluye los siguientes análisis:

1. **Facturación Total por Tienda**
   - Suma total de ventas
   - Cantidad de transacciones

2. **Análisis por Categoría**
   - Ventas por categoría de producto
   - Diversificación del inventario

3. **Valoración de Clientes**
   - Calificación promedio por tienda
   - Satisfacción del cliente

4. **Productos Más y Menos Vendidos**
   - Top 5 productos más vendidos
   - Top 5 productos menos vendidos

5. **Costos de Envío**
   - Valor promedio de envío por tienda
   - Análisis de rentabilidad

6. **Margen Bruto Aproximado**
   - Cálculo de margen (Precio - Costo de envío)
   - Comparativa entre tiendas

### 🚀 Cómo Ejecutar el Proyecto

#### Requisitos Previos

Asegúrate de tener Python instalado en tu sistema. Puedes descargarlo desde [python.org](https://www.python.org/).

#### Instalación

1. Clona este repositorio:
```bash
git clone [URL_DEL_REPOSITORIO]
cd challenge1-data-science-latam
```

2. Instala las dependencias necesarias:
```bash
pip install pandas numpy matplotlib seaborn plotly
```

#### Ejecución

1. Asegúrate de que los archivos CSV estén en la carpeta `datos/`
2. Abre el notebook con Jupyter:
```bash
jupyter notebook challenge1-data-science-latam.ipynb
```
3. Ejecuta todas las celdas secuencialmente

### 📈 Resultados Principales

#### Ventas Totales
- **Tienda 1:** $1.150.880.400,00
- **Tienda 2:** $1.116.343.500,00
- **Tienda 3:** $1.098.019.600,00
- **Tienda 4:** $1.038.375.700,00 ⚠️

#### Cantidad de Transacciones
- Tienda 1, 2 y 3: 2,359 transacciones
- **Tienda 4:** 2,358 transacciones (la menor)

#### Valoración Promedio
- **Tienda 1:** 3.98 ⭐
- Tienda 2: 4.04 ⭐
- Tienda 3: 4.05 ⭐
- Tienda 4: 4.00 ⭐

#### Margen Bruto Aproximado
La Tienda 4 presenta el margen bruto más bajo entre todas las tiendas.

### ✅ Conclusión y Recomendación

**Se recomienda vender la Tienda 4** por las siguientes razones:

1. ❌ **Menor facturación total** entre las 4 tiendas
2. ❌ **Menor cantidad de transacciones**
3. ❌ **Margen bruto aproximado más bajo**
4. ❌ **Calificación promedio por debajo de la media**

Esta decisión permitirá al señor Juan liberar capital para su nuevo emprendimiento mientras mantiene las tiendas con mejor desempeño operativo y financiero.

### 📝 Notas Adicionales

- Los datos no presentan valores nulos
- Todas las tiendas tienen la misma estructura de datos
- El análisis incluye visualizaciones geográficas utilizando coordenadas de ubicación
- Se implementaron funciones personalizadas para formateo de cifras en formato argentino

### 👨‍💻 Autor

Gastón Peló
Linkedin: https://www.linkedin.com/in/gpelo-data/
Mail: gaston.pelo.contacto@gmail.com

### 📄 Licencia

Este proyecto es parte de un desafío educativo de Alura Latam.

---

