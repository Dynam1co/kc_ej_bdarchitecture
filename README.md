# Práctica Big Data Architecture BootCamp Big Data & Machine Learning

Este repositorio pretende servir de guía paso a paso para explicar el procedimiento que he seguido para hacer la práctica del módulo Big Data Architecture para el BootCamp de Big Data & Machine Learning que estoy cursando en [Keep Coding](https://keepcoding.io/es/)

## Objetivo

Mi práctica consta de usar un csv ya existente con apartamentos de Airbnb para encontrar restaurantes cercanos a cada uno de ellos usando las coordenadas GPS. Para ello, crearé un programa escrito en Python 3 que se apoyará en el framework [Scrapy](https://scrapy.org/) y obtendrá los restaurantes de la web [El Tenedor](https://www.eltenedor.es/). Este mismo programa, subirá a Google Storage el csv de Airbnb y el de los restaurantes que se ha obtenido scrapeando la web de El tenedor.

Montaré en Google Cloud un clúster [Hadoop](https://hadoop.apache.org/) para procesar datos de forma distribuida, que también tendrá [Hive](https://hive.apache.org/) integrado para facilitar el cruce y extracción de datos. La conexión con Hive y la visualización de datos la haré en un proyecto Python 3 que usará la librería [PyHive](https://pypi.org/project/PyHive/) para consulta, y el framework [Django](https://www.djangoproject.com/) Para la visualización de datos vía web.

### Esquema del ejercicio

<img src="Diagrama práctica BD Architecture.png" alt="Esquema">

## Enlaces proyecto

- [Proyecto Scrapy](https://github.com/Dynam1co/kc_ej_bdarchitecture_scrapy_tenedor)
- [Proyecto PyHive/Django](https://github.com/Dynam1co/kc_ej_bdarchitecture_scrapy_pyhive)
- [Vídeo explicativo funcionamiento]

## Herramientas utilizadas

* [Typora](https://www.typora.io/) como editor markdown
* [Python 3](https://www.python.org/) como lenguaje de programación
* [PyCharm](https://www.jetbrains.com/pycharm/) como IDE para Python y Django
* [Django](https://www.djangoproject.com/) para visualización de datos vía web
* [Git Hub](https://github.com/) para el control de código fuente y exposición
* [YouTube](https://www.youtube.com/) para vídeo de demostración
* [iMovie](https://www.apple.com/es/imovie/) para edición de vídeo
* [OBS Studio](https://obsproject.com/es) para grabar pantalla
* [Google Cloud Platform]([https://cloud.google.com/gcp/?hl=es&utm_source=google&utm_source=google&utm_medium=cpc&utm_medium=cpc&utm_campaign=emea-es-all-es-dr-bkws-all-all-trial-e-gcp-1007176&utm_campaign=emea-es-all-es-dr-bkws-all-all-trial-e-gcp-1003963&utm_content=text-ad-none-any-DEV_c-CRE_220078264478-ADGP_Hybrid%20%7C%20AW%20SEM%20%7C%20BKWS%20~%20EXA_M:1_ES_ES_General_Cloud_Foreign%20Language%20Build%203.3.17-KWID_43700018611253608-kwd-26415313501-userloc_20267&utm_content=text-ad-cretactr-any-DEV_c-CRE_220078264478-ADGP_Hybrid%20%7C%20AW%20SEM%20%7C%20BKWS%20~%20EXA_M:1_ES_ES_General_Cloud_Foreign%20Language%20Build%203.3.17-KWID_43700018611253608-kwd-26415313501-userloc_20267&utm_term=KW_google%20cloud%20platform-ST_google%20cloud%20platform&utm_term=KW_google%20cloud%20platform-ST_google%20cloud%20platform&ds_rl=1242853&ds_rl=1245734&ds_rl=1245734&gclid=CjwKCAjwtuLrBRAlEiwAPVcZBvVY2sqlbdfTXsjZIplAahiPWr-3xWi-07prCr7MWnz0eLi-1IHg0RoC-e4QAvD_BwE](https://cloud.google.com/gcp/?hl=es&utm_source=google&utm_source=google&utm_medium=cpc&utm_medium=cpc&utm_campaign=emea-es-all-es-dr-bkws-all-all-trial-e-gcp-1007176&utm_campaign=emea-es-all-es-dr-bkws-all-all-trial-e-gcp-1003963&utm_content=text-ad-none-any-DEV_c-CRE_220078264478-ADGP_Hybrid | AW SEM | BKWS ~ EXA_M:1_ES_ES_General_Cloud_Foreign Language Build 3.3.17-KWID_43700018611253608-kwd-26415313501-userloc_20267&utm_content=text-ad-cretactr-any-DEV_c-CRE_220078264478-ADGP_Hybrid | AW SEM | BKWS ~ EXA_M:1_ES_ES_General_Cloud_Foreign Language Build 3.3.17-KWID_43700018611253608-kwd-26415313501-userloc_20267&utm_term=KW_google cloud platform-ST_google cloud platform&utm_term=KW_google cloud platform-ST_google cloud platform&ds_rl=1242853&ds_rl=1245734&ds_rl=1245734&gclid=CjwKCAjwtuLrBRAlEiwAPVcZBvVY2sqlbdfTXsjZIplAahiPWr-3xWi-07prCr7MWnz0eLi-1IHg0RoC-e4QAvD_BwE)) para almacenamiento y procesamiento
* [Hive](https://hive.apache.org/) para maejo de datos de forma distribuida
* [Hadoop](https://hadoop.apache.org/) para procesamiento de forma distribuida
* [Scrapy](https://scrapy.org/) para obtención de datos de terceros
* [El Tenedor](https://www.eltenedor.es/) como origen de datos externo
* [Google Drawing](https://docs.google.com/drawings/d/1ENKMAf_j07Q6wZSYerfNG0i2gDprGymR6HXmMmmYZQA/edit) para creación de esquemas

## Expresiones de Gratitud 🎁

- Comenta a otros sobre este proyecto 📢
- Da las gracias públicamente 🤓
- Sígueme en [Twitter](https://twitter.com/AsensiFj) 🐦