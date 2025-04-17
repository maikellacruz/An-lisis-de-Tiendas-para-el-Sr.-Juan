
# Análisis de Ventas y Geolocalización de Tiendas

Este proyecto tiene como objetivo analizar los datos de ventas de diferentes tiendas en relación con las coordenadas geográficas de las ventas. El análisis permite comprender cómo las ubicaciones geográficas influyen en los ingresos, las calificaciones de los clientes y otros factores clave. 

A lo largo del proyecto, se generaron visualizaciones y métricas como:
- **Ingresos Totales por Tienda**
- **Distribución de Productos Vendidos por Categoría**
- **Calificación Promedio de los Clientes por Tienda**
- **Análisis de Patrones Geográficos de las Ventas**

## Descripción

El proyecto se desarrolla en un entorno de Python, utilizando bibliotecas como `pandas`, `matplotlib`, `seaborn` y `folium` para el análisis y visualización de datos. Los datos proporcionados contienen información sobre productos vendidos, precios, métodos de pago, calificaciones de clientes, entre otros.

### Objetivos del Proyecto:
- **Evaluar las tiendas** basándose en sus ingresos, productos vendidos y satisfacción del cliente.
- **Identificar patrones geográficos** de ventas utilizando las coordenadas (latitud y longitud) de cada venta.
- **Generar gráficos** para visualizar insights clave como la distribución de ventas, calificaciones, y categorías de productos.

## Herramientas Utilizadas

- **Python 3.x**: Lenguaje de programación utilizado para el análisis de datos.
- **pandas**: Manipulación y análisis de datos.
- **matplotlib**: Creación de gráficos estáticos.
- **seaborn**: Visualización avanzada de datos estadísticos.
- **folium**: Generación de mapas interactivos y heatmaps.

## Instalación

1. **Clona este repositorio**:
    ```bash
    git clone https://github.com/tu-usuario/analisis-ventas-geografico.git
    cd analisis-ventas-geografico
    ```

2. **Crea un entorno virtual**:
    ```bash
    python -m venv venv
    ```

3. **Activa el entorno virtual**:
    - En Windows:
      ```bash
      .env\Scriptsctivate
      ```
    - En MacOS/Linux:
      ```bash
      source venv/bin/activate
      ```

4. **Instala las dependencias**:
    ```bash
    pip install -r requirements.txt
    ```

## Uso

1. **Carga los datos**:
    El proyecto incluye un archivo de datos que contiene información sobre las ventas realizadas en diferentes tiendas. Se carga en el script Python utilizando la librería `pandas`.

2. **Genera los análisis y visualizaciones**:
    El código genera una serie de análisis y gráficos:
    - Ingresos totales por tienda.
    - Calificaciones promedio de las tiendas.
    - Distribución de las categorías de productos más vendidas.
    - Mapa de calor para visualizar las concentraciones de ventas por ubicación.

3. **Explora las ubicaciones geográficas**:
    Utilizando `folium`, se genera un mapa interactivo que muestra las zonas con mayor concentración de ventas y otros patrones geográficos.

4. **Ejecuta el análisis**:
    Para ejecutar el análisis, simplemente ejecuta el archivo `analisis_ventas.py`:
    ```bash
    python analisis_ventas.py
    ```

5. **Explora el mapa interactivo**:
    El mapa de calor generado se guarda como un archivo HTML llamado `ventas_heatmap.html`, el cual puedes abrir en cualquier navegador para explorar las concentraciones geográficas de las ventas.

## Resultados del Análisis

### 1. **Ingresos por Tienda**
El análisis de los ingresos por tienda muestra que la tienda **Juan Fernandez** tiene el mayor volumen de ventas, seguido por **Maria Alfonso**, **Pedro Gomez** y **Beatriz Morales**.

### 2. **Calificación Promedio de los Clientes**
La tienda **Maria Alfonso** tiene la calificación promedio más alta (5.0), lo que indica una alta satisfacción de los clientes. En contraste, **Beatriz Morales** tiene la calificación más baja (1.0).

### 3. **Distribución de Categorías de Productos**
Se observa que la tienda **Juan Fernandez** tiene una mayor diversidad en las categorías de productos vendidos, lo que puede explicar su alto rendimiento en ventas.

### 4. **Mapa Geográfico de las Ventas**
El mapa de calor muestra que las zonas cercanas a **Medellín** y **Bogotá** tienen una alta concentración de ventas, lo que sugiere que estas ubicaciones son más rentables.

## Contribuciones

Si deseas contribuir al proyecto, por favor haz un **fork** del repositorio y abre un **pull request** con tus mejoras o nuevas funcionalidades.

## Licencia

Este proyecto está bajo la Licencia MIT. Para más detalles, consulta el archivo [LICENSE](LICENSE).

---

**Creado por Maikel La Cruz**
