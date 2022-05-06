# Práctica 3 
Este ejercicio consiste en la actualización y explicación de los cuadernos trabajados en **Jupyter con Python**. Este archivo `.md` incluye la explicación y enlace de los archivos que componen esta práctica. Cada cuaderno podrá encontrarse en dos formatos, **html** y **ipnyb**.

## Api Pandas Folium 
En este cuaderno representamos en un mapa los accidentes de tráfico ocurridos en Zaragoza extraídos de [aquí](https://www.zaragoza.es/sede/servicio/transporte/accidentalidad-trafico/accidente.csv). Utilizamos la librería **Pandas** para el análisis de los datos y la librería **Folium** para su visualización en el mapa. Tras la instalación e importación de librerías, definimos las variables y creamos un dataframe con los datos que exploramos con distitnas funciones. Con la función `folium.Marker` señalamos el lugar de los accidentes en el mapa.
Para acceder al cuaderno en formato **html** pulse [aquí](api-pandas-folium.html).
Para acceder al cuaderno en formato **ipnyb** pulse [aquí](api-pandas-folium.ipynb).

## Python Api Covid19 Pandas
Utilizamos la api del covid para comparar la evolución de la pandemia en 3 países: España, Italia y Francia. Tras instalar e importar las librería definimos la variable y creamos el dataframe para, a partir de su exploración, visualizar la evolución de la pandemia en el tiempo y su expansión en otros países. Por último se comparan los disntintos escenarios. Primero las curvas de España e Italia y finalmente añadimos la de Francia. 
Para acceder al ejercicio en formato **html** pulse [aquí](python-api-covid19-pandas.html).
Para acceder al ejercicio en formato **ipnyb** pulse [aquí](python-api-covid19-pandas.ipnyb).
Por último guardamos los datos de la compración de los casos en Italia y España que puede encontrarse [aquí](esvsit.csv) y su representación gráfica que puede verse [aquí](esvsitvsmx.png).
