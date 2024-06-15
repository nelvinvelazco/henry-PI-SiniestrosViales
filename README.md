![Logo](_src/assets/logo_OMSV.jpg)

 # **PROYECTO INDIVIDUAL - SINIESTROS VIALES**

 ##  `Tabla de Contenido`
1. [Información General](#Información-General)
2. [Tecnologías Utilizadas](#tecnologías-Utilizadas)
3. [EDA](#eda)
4. [Visualización](#visualización)
5. [Conclusiones](#conclusiones)

## `Informacion General`

#### El Observatorio de Movilidad y Seguridad Vial (OMSV) de la ciudad de Buenos Aires ha pedido analizar los accidentes de transito ocurridos durante los años 2016 al 2021. Para esto se me proporcionó unos datasets recopilados en hojas de excel. El ojetivo principal es identificar las tendencias de accidentes mortales tomando en cuenta el tipo de vías, ubicación, horas en que ocurren y tipos de vehiculos involucrados, para tomar decisiones que ayuden a disminuir los accidentes mortales. 

#### Se realizó un Analisis exploratorio (EDA) y un dasboard en Power BI para mostrar los datos y llegar a las conclusiones que se requieren.

## `Tecnologias Utilizadas`

#### - Se utilizó Python version 3.11 y varias librerias como: *`Pandas, Matplotlib, Seaborn, Numpy, Geopandas, Request`*. Se utilizó el entornos en cuadernos de *'jupyter'* para codificar y editar. 

#### - Tambien se utilizó Power BI Desktop v.2.130 para construir un dasboard mostrando graficos y KPIs


## `EDA`

#### Se realizó un analisis exploratorio para comprender los datos, identificar y corregir valores atipicos, imputar o eliminar valores faltantes y nulos e identificar outliers. Tambien se hicieron analisis de las variables para entontrar relaciones entre ellas y se usaron tecnicas estadisticas para identificar y graficar patrones que nos ayuden a tomar desiciones.

#### El EDA de realizó en 2 archivos separados debido a cantidad de lines de codigo que tomó:
#### - Analisis del dataset de accidentes mortales [EDA_homicidios.ipynb](EDA_homicidios.ipynb)
#### - Analisis del dataset de accidentes con lesionados [EDA_lesionados.ipynb](EDA_Lesionados.ipynb)


## `Visualización`

#### Se realizó un Dashboard mostrando los datos y los KPIs graficamente. Para eso se eligio Power BI Desktop como herramienta de visualización
#### Se grafican 3 KPI:
- #### *Reducir un 10% la tasa de homicidios en siniestros viales de los últimos seis meses, en comparación con la tasa de homicidios en siniestros viales del semestre anterior.*
- #### *Reducir un 7% la cantidad de accidentes mortales de motociclistas en el último año, respecto al año anterior.*
- #### *Redicir un 5% la cantidad de accidentes mortales de peatones con respecto al trimestre anterior*

#### Puede ver el dashboard en el siguiente link: [Siniestros viales](https://app.powerbi.com/view?r=eyJrIjoiYWM2Zjk3YjgtN2QxNC00NGE3LThmYzUtOWY3Y2MwYzM3YjllIiwidCI6IjlkNzhlNzFmLTc1ZWItNDFhOC1hNTJjLTA5NmYzZjJhN2Y0MiJ9)

## `Conclusiones`

#### Los mayores porcentajes de victimas de accidentes mortales son personas en `Moto, Peatones, Autos y bicicletas`. Al filtrar los accidentes por estas categorias se muestra que:
- #### *Los accidentes mortales de **Motorizados** son causados en su mayoria por choques con Autos (28%), vehiculos de Carga (26%) y vehiculos de pasajeros (15%)*
- #### *Las muertes de **Peatones** son causados en su mayoria por vehiculos de pasajeros (39%) y autos particulares (29%)*
- #### *Las accidentes mortales de personas en **Autos** particulares son causados en sus mayoria por colisiones con otros Autos (36%) y con objetos fijos (26%)*
- #### *La muertes de **Ciclistas** en accidentes viales son causadas en su mayoria por vehiculos de carga (34%), vehiculos de pasajeros(27%) y autos particulares (27%)*

#### Como todos sabemos la mayoria de los accidentes en las vias son causados por imprudencia al manejar, no respetar las señales de transito y conducir a exceso de velocidad. 

#### Para reducir los accidentes mortales de Motorizados y poder cumplir con el KPI plantado de reducir en un 7% segun el año anterior, es necesario exigir el uso obligatorio de cascos tanto el conductor como el pasajero y poner multas por exceder limites de velocidad. Para cumplir con el KPI de reducir en 5% la cantidad de muertes de peatones en accidentes viales, se recomienda habilitar puentes peatonales y semaforos en las ubicaciones donde se detectó mas densidad de muertes. Para reducrir los accidentes mortales de personas en vehiculos particulares es necesario que los fiscales de transito exijan a estos condutores que use el cinturon de seguridad. Para disminuir los ciclistas muertos por atropellamiento es recomendable restringir el transito de bicicletas en avenidas con mucho trafico o habilitando espacios de la via exclusivas para bicicletas.
