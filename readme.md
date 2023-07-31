# Jupyter Notebook para reportes de documentos de investigación usando modelos LLM

Este Jupyter Notebook analiza una colección de documentos de investigación para identificar los temas y autores principales. El cuaderno utiliza el formato BibTeX para extraer los metadatos de cada documento, y utiliza SerpAPI para buscar la URL de descarga de cada documento. Los documentos se descargan y se resumen utilizando LLMChain.  Los autores, instituciones así como otros documentos principales asociados con el tema de cada documento se identifican utilizando SerpAPI. Se genera un reporte final.

## Uso

Para utilizar este cuaderno, primero asegúrate de haber instalado todas las librerías requeridas que se listan en el archivo requirements.txt. Puedes hacerlo ejecutando el siguiente comando:

```
pip install -r requirements.txt
```

Luego, abre el cuaderno resumen_y_reporte_literatura_con_LLMs.ipynb en Jupyter y ejecuta cada celda en orden. Asegúrate de actualizar las variables path_bibtex_file y path_download_files para que apunten a las rutas de archivo correctas en tu sistema. En la carpeta test-data encontraras ficheros bibtex de prueba.


## Requerimientos

Estas son las librerias necesarias para ejecutar el notebook:

	bibtexparser==1.4.0
	fqdn==1.5.1
	google-search-results==2.4.2
	httptools==0.6.0
	isoduration==20.11.0
	jsonpointer==2.4
	langchain==0.0.234
	openai==0.27.8
	pip==22.0.2
	PyMuPDF==1.22.5
	python-dotenv==1.0.0
	requests==2.31.0
	setuptools==59.6.0
	tiktoken==0.4.0
	uri-template==1.3.0
	uvloop==0.17.0
	watchfiles==0.19.0
	webcolors==1.13
	websockets==11.0.3

## Licencia

Este notebook tiene licencia MIT. Revisa el archivo LICENSE para más información.
