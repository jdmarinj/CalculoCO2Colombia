# Cálculo emisiones de CO2 del SIN - Colombia

<p align="center"> 
<img src="https://github.com/GAMACO-MIoT/prueba1/blob/main/Logo%202.png">
</p>

 ## Índice
1. [Importación de librerías requeridas](#section1)
2. [Factor de emisión equivalente de CO2](#section2)
3. [Cálculo máximo, mínimo y promedio del precio de bolsa nacional](#section3)
4. [Cálculo de Emisiones en una Industria Manufacturera](#section4)
5. [Importación de datos de consumo](#section5)

<a id='section1'></a>
## Importación de librerías requeridas
Este repositorio se crea con el fin de compartir herramientas de consulta para extraer información relevante del Mercado de Energía Mayorista colombiano usando la API XM. El uso del repositorio se especificar para ser ejecutado en Python o la plataforma Google Colab.

<a id='section2'></a>
## Factor de emisión equivalente de CO2
De la API de XM se utilizan únicamente los factores: factorEmisionCO2e (factor de emisión de CO2 eqivalente del Sistema Interconectado Nacional) y PrecBolsNaci (precio de generación de bolsa).

<a id='section3'></a>
## Cálculo máximo, mínimo y promedio del precio de bolsa nacional
En el archivo Datos_CO2_XM.ipynb se presentan los comandos para graficar los precios de bolsa en periodos que pueden ser ajustados por el usuario.

<a id='section4'></a>
## Cálculo de Emisiones en una Industria Manufacturera /Factor de emisión diario
factorEmisionCO2e con diferentes periodos de análisis.

<a id='section5'></a>
## Importación de datos de consumo
Se recomienda al usuario descargar el archivo llamado: MatrizdeConsumo_1041208.csv (se encuentra en el repositorio). Dicho archivo deberá ser subido a Google Colab para permitir simular el consumo de una industria.








   
