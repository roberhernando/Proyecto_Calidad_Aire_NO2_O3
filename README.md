# Análisis de Calidad del Aire en Madrid (2019-2024)

Este proyecto analiza la evolución de la contaminación (NO2 y O3) en Madrid antes, durante y después de la pandemia, utilizando técnicas de Data Science y visualización geoespacial.

## Resultados Clave
* **Patrones:** Identificación de las "horas punta" de contaminación y su variación estacional.
* **Efecto COVID:** Se detectó una caída drástica del NO2 durante el confinamiento (Marzo-Abril 2020).
* **Paradoja del Ozono:** Se confirmó el "Efecto de Titulación", donde la reducción del tráfico (NO2) provoca un aumento del Ozono (O3) en el centro de la ciudad.

## Fuente de Datos
Los datos han sido obtenidos del **Portal de Datos Abiertos del Ayuntamiento de Madrid**:
* **Dataset:** [Calidad del aire: Datos horarios (2019-2024)](https://datos.madrid.es/portal/site/egob/menuitem.c05c1f754a33a9fbe4b2e4b284f1a5a0/?vgnextoid=f3c0f7d512273410VgnVCM1000000b205a0aRCRD&vgnextchannel=374512b9ace9f310VgnVCM1000000b205a0aRCRD&vgnextfmt=default)
* **Estaciones:** Información sobre la ubicación de las estaciones de medición.

## Tecnologías Usadas
* **Python** (Pandas)
* **Visualización:** Plotly Interactive.
* **Entorno:** Jupyter Notebook.

## Cómo ejecutarlo
1.  Clona el repositorio.
2.  Descarga los CSV anuales del enlace de arriba.
3.  Colócalos en la carpeta `/datos`.
4.  Ejecuta el notebook `analisis_madrid.ipynb`.
