Cómo podemos notar, `mode` no devuelve un valor escalar sino un `Series`. Esto sucede porque tenemos más de un valor que sea el más frecuente. 

También es importante destacar que el hecho de que un valor sea el que más se repita no implica que sea parecido a su promedio, si bien puede pasar esto no necesariamente es así. Por ejemplo, si tenemos una columna con los valores `1 1 1 1 2000 3000` su moda es `1` pero su promedio es `836`.
