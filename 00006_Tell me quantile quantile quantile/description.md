En el ejercicio anterior conocimos la mediana, la cual nos permite saber el valor del medio de una columna teniendo en cuenta sus elementos ordenados. Este concepto se puede extrapolar a la idea de cuantiles. :eyes:

El cuantil me dice cuál es el elemento más grande de un subconjunto de elementos más chicos. ¡Vamos a explicarlo con un ejemplo para que se entienda mejor!

Si hicieramos...

```python
arboles["diametro"].quantile(0.95)
XXX
```

... obtendríamos el diámetro más grande dentro del 95% más chico. Dicho de otra forma, si quitamos el 5% de árboles "más anchos" el mayor diámetro que nos queda es XXX. 

> ¡Probalo! Obtené la altura del árbol más alto dentro del 80% más bajo.

