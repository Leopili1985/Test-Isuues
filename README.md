# Scraping y Procesamiento de Datos de INDEC
Esta Jupyter Notebook proporciona un script para la extracción y procesamiento de datos del Instituto Nacional de Estadística y Censos de Argentina (INDEC). El script extrae datos sobre los precios promedio de varios productos del sitio web del INDEC, limpia y procesa los datos, y los presenta en formato CSV.

## Dependencias
- Python 3.x
- pandas
- numpy
- requests
- BeautifulSoup

## Uso
1. Instala las dependencias necesarias:
pip install pandas numpy requests beautifulsoup4
2. Clona el repositorio o descarga el archivo del cuaderno de Jupyter.
3. Abre el archivo del cuaderno de Jupyter en Jupyter Notebook o JupyterLab.
4. Ejecuta las celdas del cuaderno una por una, asegurándote de tener una conexión a internet activa ya que el script extrae datos del sitio web del INDEC.
5. Una vez que el script haya terminado de ejecutarse, generará un archivo CSV que contiene los datos procesados.

## Descripción
- El script extrae datos del sitio web del INDEC, específicamente apuntando a los precios promedio de varios productos.
- Procesa los datos extraídos, los limpia y los transforma en un formato estructurado ("wide to long format").
- Los datos procesados incluyen información como la fecha, región, producto, unidad y precio.
- La salida final se guarda como un archivo CSV para su análisis o uso posterior.
