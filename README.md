# RedNacionalCaminos_2019_2023
Se muestra cuantificación de la Red Nacional de Caminos (RNC) 2023 comparada con la versión 2019. 

El objetivo de este procedimiento es cuantificar los segmentos de caminos pertenecientes a la red nacional de caminos (RNC) con valores numéricos que representan que las condiciones de cada rasgo mejoraron, empeoraron o permanecen iguales en el periodo de tiempo comprendido entre los años 2019 y 2023. 

La fuente de los datos son las versiones 2019 y 2023 de la red nacional de caminos de México.
La cuantificación se realizó considerando ocho variables: condición de pavimentación, recubrimiento, número de carriles, estatus, condición, circulación, velocidad y ancho de la vía. En todos los casos se comprobó que los valores estuvieran homologados mediante la revisión de los diccionarios de datos correspondientes. 

El procedimiento se realizó una variable a la vez y consistió en comparar el valor de cada rasgo entre las dos versiones de la RNC y determinar si la condición del camino es mejor, igual o peor.

Una vez realizado este procedimiento para las ocho variables, se realizó la sumatoria de los valores obtenidos en cada comparación para obtener los valores de la cuantificación, los cuales pueden ser: 

 - Negativos si el camino tiene peores condiciones en 2022 con respecto a 2019.  Los valores menores indican que las condiciones han empeorado en varias variables.
 - Cero que puede indicar un empate entre los valores positivos y negativos de la cuantificación o que la condición no ha sufrido cambios.
 - Positivos que representan mejores condiciones en el camino.
 
Los valores mayores indican que se ha mejorado en varias variables.

Adicionalmente, se identifican rasgos que aparecen en la RNC 2023 pero que no están en la versión 2019, a estos valores se les clasifica como caminos nuevos.

La capa de información geoespacial en formato hapefile contiene rasgos de la RNC 2023 y dos columnas adicionales donde se realiza la cuantificación:

 - **estatus3_s**: texto que describe queindicadores mejoran o empeoran en cada segmento.
 - **estatus3_n**: valores enteros entre -4 y 5 para la cuantificación de segmentos y el valor de 10 para caminos nuevos.
 
