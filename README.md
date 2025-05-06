# Análisis de Opiniones de Películas - Trabajo de Máster

Este proyecto forma parte del trabajo de máster y tiene como objetivo realizar un análisis de sentimientos sobre opiniones de películas, utilizando técnicas de procesamiento de lenguaje natural (NLP) y visualización de datos.

## Contenidos

- **IMDb.ipynb**: Notebook principal que realiza el análisis de datos, procesamiento de opiniones y visualización de resultados.
- **movies.db**: Base de datos SQLite que contiene la información de las películas y opiniones.
  
## Tecnologías utilizadas

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- TextBlob
- Requests
- python-dotenv
- SQLite

## Instalación

Crea un entorno virtual e instala las dependencias:

```bash
python -m venv venv
source venv/bin/activate  # En Windows usa `venv\Scripts\activate`
pip install -r requirements.txt
```

## Uso

Abre el notebook `IMDb.ipynb` para explorar el análisis paso a paso.

Para ejecutar el análisis es necesario tener el archivo `movies.db` en la misma carpeta.

## Notas

- No se deben incluir archivos sensibles como `.env` ni bases de datos en producción en el repositorio público.
- Este proyecto es para fines educativos y de investigación.

## Licencia

Este proyecto está bajo la Licencia MIT.
