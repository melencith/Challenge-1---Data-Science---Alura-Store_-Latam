# 📊 Proyecto Alura Store

## 📌 Descripción del Proyecto

Este proyecto realiza un análisis completo del desempeño de cuatro tiendas (Tienda 1, Tienda 2, Tienda 3 y Tienda 4) a partir de sus datos de ventas.
Incluye:
- Limpieza y unificación de datos
- Análisis estadístico y descriptivo
- Visualización de métricas de negocio
- Comparaciones entre tiendas
- Análisis geográfico utilizando coordenadas (latitud y longitud)
- Gráficos de dispersión y mapas de calor para ubicar y evaluar la concentración de ventas

El objetivo principal es **identificar patrones de comportamiento, zonas de alto rendimiento y áreas de oportunidad** para cada tienda.

---

## 📂 Estructura del Proyecto

```plaintext
/Proyecto-Alura-Store
│
├── data/
│   ├── tienda1.csv
│   ├── tienda2.csv
│   ├── tienda3.csv
│   └── tienda4.csv
│
├── AluraStoreLatam.ipynb
└── README.md
```


## 🧪 Acerca de los Datos
Cada archivo contiene información de ventas por producto, ubicación (lat/lon), valores de envío, calificación del cliente y otros atributos relevantes para el análisis.

Las cuatro tiendas se analizan tanto **por separado** como **unificadas** en un solo DataFrame para el análisis geográfico.

---

## 🛠️ Tecnologías utilizadas
- **Python 3.x**
- **Pandas** → manejo y transformación de datos  
- **Matplotlib** → visualizaciones  
- **Seaborn** → análisis estadístico  
- **Folium** (opcional) → mapas interactivos  
- **Google Colab** → desarrollo del proyecto  
- **Jupyter Notebook** (si se desea ejecutar localmente)

---

## 📥 Instalación

### 1. Clonar el repositorio
```bash
git clone https://github.com/usuario/nombre-del-proyecto.git
```
### 2. Instalar dependencias:
```bash
pip install pandas matplotlib seaborn folium jupyter
```
### 3. Abrir el proyecto:
```bash
jupyter notebook
```

## ☁️ En Google Colab:
1. Abrir Colab → “Archivo” → “Subir notebook”
2. Cargar AluraStoreLatam.ipynb

## 🚀 Cómo Ejecutar el Proyecto
Dentro del notebook encontrarás secciones dedicadas a:
- Importación de datos
- Análisis de facturación
- Ventas por categoría
- Calificación promedio de la tienda
- Productos más y menos vendidos
- Envío promedio por tienda
- Generando gráfico
- Informa Final
- Análisis Geográfico
- Análisis del Desempeño Geográfico

## 📌 Conclusiones Generales
- La Tienda 1 lidera en facturación, pero tiene el costo de envío más alto.
- La Tienda 4 tiene menor facturación, pero ofrece menor costo logístico.
- El análisis geográfico muestra áreas clave de crecimiento y zonas donde el rendimiento no coincide con el potencial.
- Existen patrones espaciales que influencian los ingresos y la satisfacción del cliente.

## ✍️ Autor
#### Milagros Coronado Castro
Proyecto realizado como parte del curso Alura Latam – Data Science
