# Análisis Comparativo de Tiendas de Alura Store - Challenge Data Science ONE Latam

## 🚀 Descripción del Proyecto

Este proyecto forma parte del **Challenge de Data Science de Alura Latam y Oracle Next Education (ONE)**. El objetivo principal es realizar un análisis comparativo del rendimiento de cuatro tiendas de la cadena ficticia "Alura Store" para ayudar al propietario, el Sr. Juan, a decidir qué tienda vender para poder invertir en un nuevo emprendimiento.

El análisis se basa en datos de ventas, productos, clientes y envíos proporcionados para cada una de las cuatro tiendas.

## 🎯 Objetivo del Análisis

Identificar la tienda de Alura Store con el **menor rendimiento general**, considerando métricas clave como ingresos, satisfacción del cliente y eficiencia operativa, para proporcionar una recomendación fundamentada al Sr. Juan.

## 📊 Dataset Utilizado

Los datos provienen de cuatro archivos CSV distintos, uno por cada tienda (`Tienda 1.csv`, `Tienda 2.csv`, etc.), obtenidos del repositorio de GitHub proporcionado por Alura Latam.

Las columnas principales analizadas incluyen:
*   `Producto`: Nombre del artículo vendido.
*   `Categoría del Producto`: Clasificación del producto.
*   `Precio`: Valor de la venta.
*   `Costo de envío`: Gasto asociado al envío.
*   `Fecha de Compra`: Información temporal.
*   `Lugar de Compra`: Información geográfica general.
*   `Calificación`: Evaluación del cliente (1-5).
*   `Método de pago`: Forma de pago utilizada.
*   `Cantidad de cuotas`: Número de pagos (si aplica).
*   `lat`, `lon`: Coordenadas geográficas de la compra.

## 🛠️ Análisis Realizado

Se llevaron a cabo los siguientes análisis comparativos entre las cuatro tiendas:

1.  **Ingreso Total por Tienda:** Cálculo de la facturación total (`Precio`).
2.  **Ventas por Categoría:** Conteo de unidades vendidas por `Categoría del Producto`.
3.  **Calificación Promedio de Clientes:** Cálculo del promedio de `Calificación`.
4.  **Productos Más y Menos Vendidos:** Identificación y conteo de unidades por `Producto`.
5.  **Costo Promedio y Distribución de Envío:** Cálculo del promedio y análisis de la distribución del `Costo de envío`.
6.  **(Opcional) Análisis Geográfico:** Visualización de ventas (`lat`, `lon`) por tienda, densidad y calificación.

## 💡 Hallazgos Clave y Recomendación

*   **Menor Ingreso:** La **Tienda 4** presentó consistentemente el menor ingreso total.
*   **Peor Calificación:** La **Tienda 1** obtuvo la calificación promedio más baja por parte de los clientes.
*   **Mayor Costo de Envío:** La **Tienda 1** también registró el costo promedio de envío más alto.
*   **Menor Costo de Envío:** La **Tienda 4** demostró ser la más eficiente en costos de envío (promedio más bajo).
*   **Categoría Dominante:** "Muebles" fue la categoría más vendida en unidades en todas las tiendas.
*   **Productos Estrella:** Los productos más vendidos variaron entre tiendas, indicando posibles nichos.

**Recomendación Final:** Basado en el análisis, se recomienda al Sr. Juan considerar la venta de la **Tienda 4**, principalmente debido a su significativamente menor generación de ingresos en comparación con las demás, a pesar de su eficiencia en envíos.

## 📈 Visualizaciones Generadas

Se utilizaron diversos tipos de gráficos para visualizar los resultados:

*   **Gráficos de Barras:** Para comparar Ingresos Totales, Calificación Promedio y Volumen del Producto Más Vendido.
*   **Gráficos Circulares (Pie Charts):** Para mostrar la distribución porcentual de Ventas por Categoría.
*   **Diagramas de Caja (Box Plots):** Para analizar la distribución y variabilidad de los Costos de Envío.
*   **(Opcional) Gráficos de Dispersión y Densidad:** Para el análisis geográfico (ubicación de ventas, concentración y calificación por zona).


![17445986909028645478869345026250](https://github.com/user-attachments/assets/f9c7cc3b-49a9-4c4f-aa44-990281a8148b)
Distribución de Costos de Envío por Tienda (Box Plot)

## 💻 Tecnologías Utilizadas

*   **Lenguaje:** Python 3
*   **Bibliotecas:** Pandas, Matplotlib, Seaborn
*   **Entorno:** Google Colaboratory (Colab)
*   **Control de Versiones:** Git y GitHub

## ▶️ Cómo Ejecutar el Proyecto

1.  **Clonar o Descargar:** Obtén los archivos de este repositorio, principalmente el cuaderno de Jupyter (`.ipynb`).
    ```bash
    git clone https://github.com/thecat065/data-science-challenge-alura.git
    ```
    O descarga el ZIP desde GitHub.
2.  **Abrir en Google Colab:**
    *   Ve a [colab.research.google.com](https://colab.research.google.com/).
    *   Selecciona `Archivo` -> `Subir cuaderno...`
    *   Sube el archivo `.ipynb` descargado.
3.  **Ejecutar Celdas:** Ejecuta las celdas de código en orden secuencial. La primera celda se encarga de importar las librerías y cargar los datos directamente desde las URLs de los archivos CSV originales proporcionados por Alura. No se necesita subir los CSV manualmente.
4.  **Ver Resultados:** Los resultados de los análisis (textos, tablas) y las visualizaciones (gráficos) se mostrarán debajo de cada celda correspondiente. El informe final está en una celda de texto al final.

## 👤 Autor

*   **Carlos, Victorio Puma**
*   **LinkedIn:** https://www.linkedin.com/in/carlosvictoriopuma
*   **GitHub:** https://github.com/thecat065

---
*Proyecto realizado como parte del Challenge Data Science ONE (Oracle Next Education + Alura Latam).*



-----
