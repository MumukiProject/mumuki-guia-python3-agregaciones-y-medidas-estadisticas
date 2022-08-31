Al hacer `describe` de nuestro dataset obtuvimos una tabla como esta:

TABLA DE DESCRIBE.

Expliquemos un poco de qué se trata cada una de estas filas:

* `count` es la cantidad de valores que tenemos dentro de esa columna;
* `mean` es el promedio de los valores de esa columna;
* `std` es el desvío estándar. En otras palabras, cuán lejos tienden a estar los valores del promedio;
* `min` es el menor valor que podemos encontrar en la columna;
* `25%` es el valor de Q1;
* `50%` es el valor de Q2;
* `75%` es el valor de Q3;
* `max` es el mayor valor que podemos encontrar en la columna.

También habrás notado que `describe` nos muestra solo información sobre las columna numéricas de nuestro lote de datos. Sin embargo, es importante notar que aunque la columna sea numérica no siempre tiene sentido obtener medidas estadísticas. Probablemente no nos interese el promedio de los códigos postales o la mediana de los ids. 

Ahora que comprendimos `describe` vamos a conocer `info`, otra herramienta que nos permite obtener otro tipo de información sobre nuestros datos.

> Probá en la consola `arboles.info()`.
