# Reto-10
Desarrollar un algoritmo que calcule el promedio de un arreglo de reales.
```
a = [1,2,3,4,5] 
suma: int=0  #Inicializando la variable donde se va acumular la suma 
for i in a:
    suma+=i
    n: float = suma/len(a)
print(n)
```
Desarrollar un algoritmo que calcule el producto punto de dos arreglos de números enteros (reales) de igual tamaño.
```
x = [1,2,3,4,5]
y = [5,4,3,2,1]
n:int = 0 
a = len(x)
b = len(y)
if a==b: # Esto puesto que las listas deben ser de igual tamaño
    for i in range(len(x)): #Recorre la lista solo una vez
        n+= x[i]*y[i]#El producto punto va acumulando la suma de los productos de las respectivas posiciones
    print(n)    
```
Hacer un algoritmo que deje al final de un arreglo de números todos los ceros que aparezcan en dicho arreglo.
```
lista = [1,3,0,2,4,0,0]

n_zeros = lista.count(0)
while 0 in lista:
    lista.remove(0)

a = lista + [0]*n_zeros #En este caso se multiplica la lista [0] por el numero de ceros contados previamente y se suma con la lista resultante al quitar los ceros en el inicio 
print(a)
```
Revisar que son los algoritmos de sorting, entender bubble-sort (enlace a implementación).
