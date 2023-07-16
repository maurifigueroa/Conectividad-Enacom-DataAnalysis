
# <h1 align=center> **PROYECTO INDIVIDUAL Nº 2** </h1>

# <h1 align=center> **Conectividad a internet en la República Argentina** </h1>

![](tipos-fibra-optica-internet.jpg)

## **Introducción**

Este trabajo consiste en un análisis de la conectividad de banda ancha en la República Argentina. La fuente de datos es el ENACOM (Ente Nacional de Comunicaciones), que se encarga de la promoción y mejora de los servicios de comunicación de todo tipo, fomentando las inversiones y la competencia. Uno de sus grandes objetivos es llegar a la plena inclusión digital.

## **Objetivo**

El objetivo es obtener una visión integral del estado de las comunicaciones en el país, dónde están aquellos lugares con buena cobertura en cantidad y calidad de ofertas de servicios a internet y dónde aquellos en que se tiene que mejorar. El análisis ofrece insights que permiten tomar decisiones de forma correcta. Esta información puede ser relevante para las grandes empresas de comunicaciones que se reparten el mercado como así también para aquellas pequeñas y medianas que quieren posicionarse y ganarse un lugar.

## **Desarrollo**

Todos la información es oficial y obtenida del ENACOM.
Como principales tenemos 16 datasets con temática "internet de banda ancha". Esta se define como aquella que llega a los hogares a través de una factura fija y generalmente el volumen de tráfico es ilimitado para el cliente. Encontramos tecnologías como ADSL, cable módem, fibra óptica, wireless, etc.
Tenemos datasets con datos a nivel nacional, datos provinciales y también de localidades. La pluralidad de información es alta y bien ordenada.

Como primer paso se va a realizar ETL a los datasets que sean necesarios para corregir errores y rellenar datos faltantes y acondicionarlos para las herramientas de visualización. Luego pasamos al EDA (Exploratory Data Analysis) buscando tendencias e insights en los datos y luego pasamos a la herramienta de visualización. Usamos Matplotlib, Seaborn y Geopandas con su gran capacidad de customización.

## Material complementario.

Datasets de Eurostat, Unión Europea: 
https://ec.europa.eu/eurostat/web/main/data/database
**Broadband internet coverage by speed (isoc_cbs)**
**Broadband internet coverage by technology (isoc_cbt)**

Articulo complementario:
https://digital-strategy.ec.europa.eu/es/policies/broadband-technology-overview

