# WEBSCRAPING USING REQUEST AND BEUATIFULSOUP FROM  MERCADO LIBRE COLOMBIA WEB SITE, USED PRICES CAR MARKET 

Este proyecto te mostrara como se usa webscraping con BeautifulSoup para obtener datos a gran escala y automatizado de sitios web en este caso mercado libre
Inspeccionaremos codigo HTML XML para clasificar los datos a extraer.

Escrapear la pagina de mercado libre para obtener multiples precios de carros usados en Colombia 
# EL ARCHIVO ROBOTS 
Este archivo se encuentra en la raiz del sitio web y nos dice que informacion podemos scrapear y cuales no, para proteger el sitio de sobrecargas de solicitudes y de uso de informacion restringida por los creadores de la pagina 
Check https://www.mercadolibre.com.co/robots.txt for more information on what the website allow

# Package Imports: Librerias a utilizar 
Para este proyecto vamos a utilizar: HTML,lxmml,Request,Pandas,BeautifulSoup


import requests # se va realizar web scraping a mercado libre para obtener mas de 40.000 registro de vehiculos usados
from bs4 import BeautifulSoup
from lxml import etree
import pandas as pd
from lxml import html
