# Estudio sobre violencia de genero
![image](titulo.png)
# Violencia de Género España 2003 - 2023

## 1 - Descripción
Los datos de este proyecto han sido obtenidos de las páginas oficiales de:
- INE: [INE](https://www.ine.es/dyngs/INEbase/es/operacion.htm?c=Estadistica_C&cid=1254736176866&menu=ultiDatos&idp=1254735573206)
- Ministerio de Igualdad: [Ministerio de Igualdad](https://violenciagenero.igualdad.gob.es/)

El proyecto está basado en el análisis de la situación a lo largo de la historia en la violencia de género en España.

## 2 - Objetivos de desarrollo
### 2.1 - Análisis exploratorio
El principal objetivo es investigar tras los datos obtenidos de las páginas oficiales.
### 2.2 Limpieza de datos
Comenzamos con la limpieza de los datos eliminando valores NaN, buscando errores en las tablas e implementando mejoras para la optimización de estas. Una vez tenemos los datos limpios, pasamos al tipo de dato que necesitamos para trabajarlos con homogeneidad.
### 2.3 Unión de los datos
Una vez limpio cada CSV, comenzamos con la unión de las tablas utilizando los diferentes métodos que nos facilita el lenguaje de Python (merge, concat, join, etc.). Después de esto y muy importante, realizamos la comprobación de que todo se ha unificado correctamente sin habernos dejado ningún dato por el camino o que se hayan creado valores NaN que nos puedan poner problemas en el desarrollo del modelo.
### 2.4 Gráficas
Sacaremos mediante pivot table, group by y otros métodos la relación de lo que queremos estudiar para ver si tiene relación e incluso ver si afecta variables exógenas a la violencia de género, como por ejemplo el nivel de estudios o nivel de paro de cada comunidad.

| Gráficas | Enlace |
| ------ | ------ |
| Desempleo | [Desempleo]([Graficas Estudio/desempleo dic2023.png](https://github.com/SergioPrior/Violencia-de-genero/blob/main/Graficas%20Estudio/desempleo%20dic2023.png)) |
| Muertes por CCAA, 2023| [Muertes por CCAA, 2023](https://github.com/SergioPrior/Violencia-de-genero/blob/main/Graficas%20VVG/muertes%20por%20comunidad%202023.png) |
| Nivel de estudios | [Nivel de estudios](https://github.com/SergioPrior/Violencia-de-genero/blob/main/Graficas%20VVG/informe%20PISA%202022.png) |
| Muertes por Origen Nacionalidad | [Muertes por Origen Nacionalidad](https://github.com/SergioPrior/Violencia-de-genero/blob/main/Graficas%20VVG/muertes%20por%20origen%20de%20nacionalidad%202003-2023.png) |
| Muertes por millón de hab, Histórico | [Muertes por millón de hab, Histórico](https://github.com/SergioPrior/Violencia-de-genero/blob/main/Graficas%20VVG/muertes%20por%20cada%20millon%20de%20habitantes%2020%20a%C3%B1os.png) |

## 3 - Estudio
A raíz de sacar las gráficas, hemos obtenido resultados en donde podemos observar que el nivel de estudios de la comunidad autónoma y la tasa de desempleo tienen mucha relación con la cantidad de casos por violencia de género en nuestro país.

## 4 - Dashboard PowerBI
Una vez realizado el estudio lo he trasladado todo a un dashboard en PowerBI para darle más claridad, calidad e interactividad, si quieres obtenerlo para visualizarlo o trabajarlo te dejo aquí el enlace:

| Dashboard | [Dashboard PowerBI](Dashboard_VG.pbix) |

- Como podemos observar en él tenemos unas gráficas con la información de Nº víctimas por CCAA, si convivían juntos o no, más el total de hijos huérfanos de las familias, el número de víctimas mensuales y víctimas por año desde el estudio 2003 hasta la actualidad. También, mapas donde podemos observar la correlación entre el Nº víctimas y la tasa de desempleo, un gráfico circular donde vemos la tasa de suicidio del agresor y finalmente una tabla donde podemos ver en sí el número de víctimas totales y la tasa de desempleo de forma porcentual.

## 6 - Conclusiones
Gracias al gráfico en PowerBI hemos podido observar cómo las comunidades autónomas con más tasa de paro y menos nivel de estudios son, con diferencia, las CCAA donde más homicidios con violencia de género hay.
También cabe destacar que si orientamos los homicidios por millón de habitantes, las ciudades donde más se cometen son.

Los peores meses donde más homicidios existen son los meses de verano y Navidad, meses donde la mayoría de la gente convive más tiempo, vacaciones, fiestas, etc.

Los años más negros desde la recogida del estudio han sido:

| Años | Víctimas |
| ------ | ------ |
| 2008 | 76 |
| 2010 | 73 |
| 2015 | 59 |
| 2019 | 56 |
| 2023 | 57 |

Muchas gracias.
