# Práctica Big Data Architecture BootCamp Big Data & Machine Learning

Este repositorio pretende servir de guía paso a paso para explicar el procedimiento que he seguido para hacer la práctica del módulo Big Data Architecture para el BootCamp de Big Data & Machine Learning que estoy cursando en [Keep Coding](https://keepcoding.io/es/)

## Objetivo

Mi práctica consta de usar un csv ya existente con apartamentos de Airbnb, para encontrar restaurantes cercanos a cada apartamento usando las coordenadas GPS. Para ello,crearé un programa escrito en Python 3 que se apoyará en el framework Scrapy y obtendrá los restaurantes de la web [El Tenedor](https://www.eltenedor.es/). Este mismo programa, subirá a Google Storage el csv de Airbnb y el de los restaurantes que se ha obtenido scrapeando la web de El tenedor.

Montaré en Google Cloud un clúster [Hadoop](https://hadoop.apache.org/) para procesar datos de forma distribuida, que también tendrá [Hive](https://hive.apache.org/) integrado para facilitar el cruce y extracción de datos. La conexión con Hive y la visualización de datos la haré en un proyecto Python que usará la librería [PyHive](https://pypi.org/project/PyHive/) para consulta, y el framework [Django](https://www.djangoproject.com/) Para la visualización de datos vía web.

### Esquema del ejercicio

<img src="Diagrama práctica BD Architecture.png" alt="Esquema">

## Enlaces proyecto

- [Proyecto Scrapy](https://github.com/Dynam1co/kc_ej_bdarchitecture_scrapy_tenedor)
- [Proyecto PyHive/Django](https://github.com/Dynam1co/kc_ej_bdarchitecture_scrapy_pyhive)
- [Vídeo explicativo funcionamiento]

## Expresiones de Gratitud 🎁

- Comenta a otros sobre este proyecto 📢
- Da las gracias públicamente 🤓
- Sígueme en [Twitter](https://twitter.com/AsensiFj) 🐦