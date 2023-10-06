# Ghibli Friends
## Índice

* [1. Definición del Producto](#1-definición-del-producto)
* [2. Historias de Usuaria](#2-historias-de-usuaria)
* [3. Diseño de la interfaz de usuaria](#2-resumen-del-proyecto)
* [4. Diseño de alta fidelidad](#4-diseño-de-alta-fidelidad)
* [5. Testeos de usabilidad](#3-Testeos-de-usabilidad)

  
***
## 1. Definición del Producto
Ghibli Friends, es una aplicación diseñada para quienes quieran saber un poquito más acerca de las maravillosas producciones realizadas por Studio Ghibli.
Tendrán acceso a una lista de 20 películas con unas tarjetas que muestran los poster de cada una y sus nombre traducidos al Inglés. Esta aplicación permitirá a sus usuarios filtrar las tarjetas según el director a cargo de cada película, además de  ordenar por año de publicación ,desde la más antigua (1986) a la más actual (2014). Para quiénes tengan curiosidad sobre el trabajo de los directores se visualizará una estadística, representando el porcentajes de trabajo de cada Director dentro del Estudio.

## 2. Historias de Usuaria
La aplicación busca brindar una herramienta que permita expandir la comunidad de interesados en el Studio Ghibli, al mismo tiempo que proporciona información relevante a aquellos que ya son fanáticos de los films.

En ese sentido, el enfoque específico abordado en el trabajo es:

![historias de usuaria](https://github.com/Carolinava21/DEV011-data-lovers-DL12/assets/142191821/29040a1a-d4a1-4ae0-8502-b5300ac5fb05)

## 3. Diseño de baja Fidelidad

![diseño](https://github.com/Carolinava21/DEV011-data-lovers-DL12/assets/142191821/596a97d8-748f-4d1d-8ba6-7708e2f6dcf1)

## 4. Diseño de alta Fidelidad

![image](https://github.com/Carolinava21/DEV011-data-lovers-DL12/assets/142191821/5d41d0b4-e871-410f-9235-cbcea4f27998)

## 5. Testeos de usabilidad
La efectividad de las funciones dentro de la aplicación ha sido analizada a través de pruebas unitarias creadas específicamente:
- [ ] **Describe** ("funciónOrdenarASC") => **it** ("Ordenar las tarjetas por los años de publicación de manera ascendente")
- [ ] **Describe** ("funciónOrdenarDESC") => **it** ("Ordenar las tarjetas por los años de publicación de manera descendente")
- [ ] **Describe** ("funciónFiltrar") => **it** ("Filtar las tarjetas por el nombre de los directores")
- [ ] **Describe** ("funciónEstadística") => **it** ("Calcular el % de películas realizadas por cada director")
- [ ] **Describe** ("funciónEstadísticaFALSE") => **it** ("No Calcula si no encuentra el nombre del director proporcionado")
      
![image](https://github.com/Carolinava21/DEV011-data-lovers-DL12/assets/142191821/f12d560d-3432-4217-9f85-0070412ee5f3)
