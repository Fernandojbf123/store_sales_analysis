# Analizador de Ventas de Tienda [Español / English (down below)]

## Descripción del Proyecto 
**Analizador de Ventas de una Tienda** desarrollado en Python. Utiliza técnicas de ciencia de datos para analizar y visualizar información relevante sobre las ventas registradas en dos archivos CSV. El análisis incluye limpieza de datos, agrupaciones, y respuestas a preguntas clave como el producto más vendido y el mes con mayores ventas.

### Tecnologías Usadas
- **Python**: Lenguaje principal para el análisis de datos.
- **Pandas**: Manipulación, limpieza y análisis de datos tabulares.
- **Jupyter Notebook**: Entorno interactivo para ejecutar y documentar el análisis paso a paso.

## Objetivo del Proyecto
El objetivo es crear un programa que lea, fusione y analice datos de ventas de una tienda (que se encuentran en dos archivos .csv separados), proporcionando información útil como:
- Producto más vendido
- Mes con más ventas
- Ventas agrupadas por categoría
- Exportación de resultados a un archivo CSV

## Datos 

Los archivos de datos contienen información tabular sobre las ventas realizadas en la tienda. Cada fila representa una transacción y las columnas principales son:

| Fecha       | Producto    | Cantidad | Precio Unitario | Total Venta |
|-------------|-------------|----------|-----------------|-------------|
| 1/17/2023   | Electrónic  | 7        | 200             | 1400        |
| 9/1/2023    | Electrónic  | 8        | 200             | 1600        |
| 7/29/2023   | Juguetes    | 3        | 30              | 90          |
| ...         | ...         | ...      | ...             | ...         |

**Descripción de las columnas:**
- **Fecha**: Día en que se realizó la venta (formato MM/DD/AAAA).
- **Producto**: Categoría o tipo de producto vendido (Ej: Electrónic, Juguetes, Alimentos, Ropa, Libros).
- **Cantidad**: Número de unidades vendidas en la transacción.
- **Precio Unitario**: Precio de una sola unidad del producto.
- **Total Venta**: Importe total de la venta (Cantidad x Precio Unitario).

Ambos archivos (`Datos_Ventas_Tienda.csv` y `Datos_Ventas_Tienda2.csv`) tienen la misma estructura y se combinan para el análisis.


## Instalación del Proyecto
Puedes instalar y ejecutar este proyecto usando **Anaconda** o un ambiente virtual con **pip**.

### Opción 1: Usando Anaconda
1. Descarga e instala Anaconda desde [anaconda.com](https://www.anaconda.com/products/distribution).
2. Abre Anaconda Prompt y navega a la carpeta del proyecto:
   ```sh
   cd ruta/del/proyecto
   ```
3. Crea un nuevo entorno:
   ```sh
   conda create -n ventas_tienda python=3.11
   conda activate ventas_tienda
   ```
4. Instala las dependencias:
   ```sh
   conda install pandas jupyter
   ```
5. Inicia Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
6. Abre el archivo `store_sales_analysis.ipynb` y ejecuta las celdas.

### Opción 2: Usando ambiente virtual + pip
1. Instala Python desde [python.org](https://www.python.org/downloads/).
2. Abre una terminal y navega a la carpeta del proyecto:
   ```sh
   cd ruta/del/proyecto
   ```
3. Crea un ambiente virtual:
   ```sh
   python -m venv ventas_tienda
   ventas_tienda\Scripts\activate
   ```
4. Instala las dependencias:
   ```sh
   pip install pandas notebook
   ```
5. Inicia Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
6. Abre el archivo `store_sales_analysis.ipynb` y ejecuta las celdas.

**Recomendación:** Si eres principiante, se recomienda usar Anaconda por su facilidad de uso y gestión de entornos.
**Nota:** El bloque de código que comienza con ```sh indica que los comandos deben ejecutarse en la terminal o consola de tu sistema operativo.

---
# Store Sales Analyzer (ENGLISH)

## Project Description
This project is a **Store Sales Analyzer** developed in Python. It uses data science techniques to analyze and visualize relevant information about sales recorded in two CSV files. The analysis includes data cleaning, grouping, and answers to key questions such as the best-selling product and the month with the highest sales.

### Technologies Used
- **Python**: Main language for data analysis.
- **Pandas**: For manipulation, cleaning, and analysis of tabular data.
- **Jupyter Notebook**: Interactive environment to execute and document the analysis step by step.

## Project Objective
The goal is to create a program that reads, merges, and analyzes store sales data (found in two separate .csv files), providing useful information such as:
- Best-selling product
- Month with the highest sales
- Sales grouped by category
- Exporting results to a CSV file

## Data
Datos_Ventas_Tienda.csv
Datos_Ventas_Tienda2.csv

The data files contain tabular information about store sales. Each row represents a transaction and the main columns are:

| Date       | Product     | Quantity | Unit Price      | Total Sale   |
|------------|-------------|----------|-----------------|--------------|
| 1/17/2023  | Electronic  | 7        | 200             | 1400         |
| 9/1/2023   | Electronic  | 8        | 200             | 1600         |
| 7/29/2023  | Toys        | 3        | 30              | 90           |
| ...        | ...         | ...      | ...             | ...          |

**Column Description:**
- **Date**: Day the sale was made (format MM/DD/YYYY).
- **Product**: Category or type of product sold (e.g., Electronic, Toys, Food, Clothing, Books).
- **Quantity**: Number of units sold in the transaction.
- **Unit Price**: Price of a single unit of the product.
- **Total Sale**: Total amount of the sale (Quantity x Unit Price).

Both files (`Datos_Ventas_Tienda.csv` and `Datos_Ventas_Tienda2.csv`) have the same structure and are combined for analysis.

## Installation
You can install and run this project using **Anaconda** or a virtual environment with **pip**.

### Option 1: Using Anaconda
1. Download and install Anaconda from [anaconda.com](https://www.anaconda.com/products/distribution).
2. Open Anaconda Prompt and navigate to the project folder:
   ```sh
   cd path/to/project
   ```
3. Create a new environment:
   ```sh
   conda create -n store_sales python=3.11
   conda activate store_sales
   ```
4. Install dependencies:
   ```sh
   conda install pandas jupyter
   ```
5. Start Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
6. Open the `store_sales_analysis.ipynb` file and run the cells.

### Option 2: Using virtual environment + pip
1. Install Python from [python.org](https://www.python.org/downloads/).
2. Open a terminal and navigate to the project folder:
   ```sh
   cd path/to/project
   ```
3. Create a virtual environment:
   ```sh
   python -m venv store_sales
   store_sales\Scripts\activate
   ```
4. Install dependencies:
   ```sh
   pip install pandas notebook
   ```
5. Start Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
6. Open the `store_sales_analysis.ipynb` file and run the cells.

**Recommendation:** If you are a beginner, it is recommended to use Anaconda for its ease of use and environment management.
**Note:** The code block starting with ```sh means that the commands should be executed in your system's terminal or command prompt.