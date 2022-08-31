Hasta acá estuvimos trabajando con operaciones que nos permiten obtener información de nuestras columnas (o `Series`). Lo interesante es que la mayoría de ellas también funcionan con listas pero debemos invocarlas como funciones.

> Probá lo siguiente en la consola en órden para ver las diferencias:
>
```python
arboles["altura_tot"].min()
min([2, 4, 8, 16, 32, 64, 128, 256, 512, 1024])
arboles["inclinacion"].max()
max([2, 4, 8, 16, 32, 64, 128, 256, 512, 1024])
arboles["diametro"].sum()
sum([2, 4, 8, 16, 32, 64, 128, 256, 512, 1024])
arboles["inclinacion"].mean()
mean([2, 4, 8, 16, 32, 64, 128, 256, 512, 1024])
```
