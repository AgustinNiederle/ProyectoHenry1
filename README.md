# ProyectoHenry1
Proyecto individual 1 Henry Cohorte PT09

Contextualización y Motivación: 
En este trabajo se busca realizar un MVP para poder montar una API y deployarla en Render, usando un data set con columnas anidadas, valores repetidos, altas proporcion de NAN o en formatos inadecuados. Se buscará utilizar métodos de limpieza y carga de datos (ETL), para poder entender el valor de los mismos con un EDA, lograr algun insight útil para finalmente crear un modelo con Machine Learning para implementar un sistema de recomendación de películas al estilo de las plataformas de contenido.

Descripción
Este proyecto tiene como objetivo analizar los datos de un dataset con datos de largometrajes internacionales a lo largo de los 100 primeros años de la industria. Podemos entender cómo crece la cantidad de estrnenos por año, el comportamiento de la popularidad en función de los géneros y el efecto que tuvieron las plataformas de contenido y la pandemia en la actividad económica del cine.

Requisitos:
Python 3.10 
uvicorn
pandas
numpy
numpy
matplotlib
scikit-learn
wordcloud
fastAPI
Render

Pasos de instalación:
Clonar el repositorio: git clone (https://github.com/AgustinNiederle/ProyectoHenry1.git)
Crear un entorno virtual: python -m venv venv

Activar el entorno virtual:
Windows: venv\Scripts\activate
macOS/Linux: source venv/bin/activate

Instalar las dependencias: pip install -r requirements.txt

Estructura del Proyecto
data/: Contiene los archivos de datos utilizados en el proyecto.
notebooks/: Incluye los notebooks de Jupyter con el análisis y modelos.
src/: Código fuente del proyecto, incluyendo scripts y módulos.
reports/: Guarda los informes y visualizaciones generados.
README.md: Archivo de documentación del proyecto.

Uso y Ejecución
Para ejecutar el análisis EDA, abrir el notebook EDA.ipynb en la carpeta EDA.
El notebook guiará a través de las diferentes etapas del análisis, incluyendo carga de datos, visualizaciones y una nube de palabras para entender mejor.

Para entender cómo se generaron los endpoints que se pueden aplicar en FastAPI y/o Render, abrir el script main.py.

Datos y Fuentes
Los datos utilizados en este proyecto provienen de la base de datos otorgada por Henry para este período de examen. Los datos incluyen más de 18 columnas de las cuáles resultaron útiles son útiles la mitad, sobre todo "release_date" de donde se pudo obtener la cantidad de estrenos a lo largo de los años. También tenemos  el overview, que es una sinopsis corta, más taglines (frases de venta). Estas dos fueron combinadas para generar el set de palabras con el que si hizo la nube de palabras y luego para aplicar el modelo de recomendación que funciona el método Similitud del Coseno.

Metodología
Se utilizaron técnicas de análisis exploratorio de datos para identificar patrones y tendencias en los datos de ventas. Se aplicaron modelos de aprendizaje automático, como regresión lineal y árboles de decisión, para predecir las ventas futuras. También se realizaron análisis de segmentación de clientes y optimización de estrategias de marketing.

Resultados y Conclusiones

Autores:
Este proyecto fue realizado por: Agu Nieder (Agustin Niederle)
