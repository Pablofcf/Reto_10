# Reto_10

1. Desarrollar un algoritmo que calcule el promedio de un arreglo de reales.

```python

```
2. Desarrollar un algoritmo que calcule el producto punto de dos arreglos de números enteros (reales) de igual tamaño.
```python
#Desarrollar un algoritmo que calcule el producto punto de dos arreglos de números enteros (reales) de igual tamaño.
Lista1 = [1,2,3,4]
Lista2 = [4,3,2,1]
Producto : int = 0 
for i in range(len(Lista1)):
    Producto = Producto + (Lista1[i]*Lista2[i]) 
print(Producto)
```
3. Hacer un algoritmo que deje al final de un arreglo de números todos los ceros que aparezcan en dicho arreglo.


```python

```
4. Revisar que son los algoritmos de sorting, entender bubble-sort

Bubble-sort es un algoritmo de clasificación el cual va reemplazando iterativamente elementos si están desordenados con el fin de ordenarlos de menor a mayor. Sin embargo, existe un problema y es que este algoritmo no es adecuado para grandes conjuntos de datos porque su complejidad temporal se vuelve alta a medida que la lista incremente sus elementos ya que utilizaria mas condicionales.
