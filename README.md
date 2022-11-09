# Proyecto Individual 03
## Data Analytics

El proyecto individual 03 se basa en la elaboración de un dashboard donde se presentan datos referentes a accidentes aéreos desde el año 1908 hasta el año 2021 alrededor del mundo. El objetivo del proyecto es evaluar diferentes habilidades tanto de análisis de datos (EDA), visualización y hablidades blandas (softskills) como presentación y comunicación de los datos, storytelling, etc. También, se elaboró una base de datos en un motor SQL con los datos procesados.

## Notebook

En el notebook **pi03_analytics.ipynb** posee la información referente al tratamiento de los datos, su procesamiento y la visualización de las variables respectivas. También se presentan algunos gráficos preliminares que permiten visualizar la distribución de los datos y permiten extraer información valiosa para su análisis posterior.

## Base de Datos

La base datos contiene las tablas con los datos procesados que fueron utilizados para la elaboración del Dashboard.

## Tecnologías utilizadas

**Python**: Se utilizó Python para el análisis exploratorio de los datos.

**SQL**: Se elaboró una base de datos con un motor SQL.

**Power** BI: Se utilizó Power BI para la presentación de los datos en un Dashboard.

## Librerías de interés.

**Geopy**: Permite obtener las coordenadas geográficas de los sitios donde ocurrieron los accidentes. 

https://geopy.readthedocs.io/en/stable/

**Flydenity**: Permite conocer el país de origen de las diferentes aeronaves involucradas en los accidentes aereos. 

https://github.com/Collen-Roller/flydenity

## Glosario de términos.

**id**: número identificador.

**date**: fecha de accidente.

**time**: hora del accidente.

**location**: lugar del accidente.

**operator**: nombre del operador.

**route**: ruta de vuelo.

**type**: modelo de avión.

**registration**: codigo de registro del vuelo.

**aboard**: número de personas abordo del avión.

**passengers**: número de pasajeros en el avión.

**crew**: número de miembros de la tripulación del avión.

**fatalities**: cantidad de fallecidos a bordo.

**passenger_fatalities**: cantidad de pasajeros fallecidos.

**crew_fatalities**: cantidad de tripulantes fallecidos.

**ground**: cantidad de fallecidos a causa del accidente.

**summary**: resumen del accidente.

**year**: año en que ocurrió el accidente.

**month**: mes (numérico) en que ocurrió el accidente.

**day**: día (númerico) en qué ocurrió el accidente.

**military**: indica si el avión es de uso militar o de uso civil.

**crash_site**: lugar donde ocurrió el accidente (sólo el país).

**survived**: número de sobrevivientes al accidente.

**survival_rate**: porcentaje de sobrevivientes al accidente.

**day_of_the_week**: nombre del día de la semana en que ocurrió el accidente.

**month_year**: nombre del mes en el que ocurrió el accidente.


