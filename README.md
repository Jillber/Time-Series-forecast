# Time-Series-forecast
I forecast time series using Excel, Rstudio. 
Introducción.
En este documento hago distintos modelos de pronóstico de la tasa de desempleo en Colombia para el periodo entre Enero del 2001
(2001-01) a Noviembre de 2019 (2019-11). El objetivo es hacer una predicción de la tasa de desempleo para los siguientes
3 meses (2019-12,2020-01,2020-02), usando regresiones polinómicas, promedios móviles y suavizamiento exponencial.

Descripción.
Comienzo por conocer los datos por medio de la estadística descriptiva y un gráfico de lineas. A partir de la estadística
descriptiva se puede afirmar que
-La mediana es 11,12, lo cual quiere decir que el 50% de las veces la tasa de desempleo ha sido 11,12.
-La desviación estándar es la dispersión de los datos respecto a la media
-Excel calcula la curtosis respecto a 3. En este caso es -0.24,  quiere decir que está ligeramente debajo de 3 (2,76), lo que 
significa que tiene una forma platicúrtica.
-El coeficiente de asimetría en una distribución normal es cero, en este caso es de 0,03, significa que la distribución
de los datos esta ligeramente sesgado a la izquierda. Es decir, la mayoría de los datos se han concentrado a la derecha.
