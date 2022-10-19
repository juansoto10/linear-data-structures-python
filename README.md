# Linear Data Structures with Python

This repository contains information, examples and more about linear structures with Python.


## Colecciones incorporadas en Python

### Listas: 

- De propósito general.
- Índices con tamaños dinámicos. 
- Ordenables.
- lista = [].
- Uno de sus posibles usos sería para para almacenar una serie de números, una lista de palabras y básicamente cualquier cosa.

### Tuplas

- Inmutables, no se pueden añadir más elementos.
- Útiles para constantes por ejemplo coordenadas, direcciones.
- Es de tipo secuencial.
- tupla = ().
- Se usarían cuando sé exactamente el tamaño que tendrán los datos.

### Conjuntos/Sets

- Almacenan objetos no duplicados.
- Son de acceso rápido.
- Aceptan operaciones lógicas.
- Son desordenados.
- set = {1, 2, 3, 4}.
- Son bastante útiles para obtener valores individuales de listas con valores duplicados.

### Algunos ejemplos de operaciones con sets:

```py
demo_set = {1,2,3,4,5}
print(2 in demo_set)
print('a' in demo_set)

# OUTPUT

# True
# False
```

Se puede hacer unión e intersección de sets:

```py
# Unión

set_a = {1,2,3}
set_b = {3,4,5}
set_c = set_a.union(set_b) 
#OR
set_c = set_a | set_b
print(set_c)

# OUTPUT

# {1,2,3,4,5}


# Intersección

set_a = {1,2,3}
set_b = {3,4,5}
set_c = set_a.intersection(set_b) 
#OR
set_c = set_a & set_b
print(set_c)

# OUTPUT

# {3}
```

### Diccionarios

- Pares de llaver valor
- Arrays asociativos (hash maps).
- Son muy rápidos para hacer consultas.
- A partir de la versión de python 3.7 los diccionarios ya estan ordenados, lo que significa que al agregar un nuevo item, este se ubicará al final.
- dict ={'Llave': 'Valor'}.
- Un posible uso sería para almacenar datos, listas, objetos que puedan volverse un dataframe o un defaultdict.


## Estructuras de datos lineales

**Estructura de datos**: Representación interna de una colección de información.

### Arrays

Es una estructura de datos que tiene una determinada capacidad de almacenamiento, la cual no se puede reducir ni aumentar.

Existen arrays de 1, 2 o 3 dimensiones. Entre más dimensiones tenga habrá mayor complejidad a la hora de manejar los datos.

Tiene ciertas restricciones:

- No se puede agregar posiciones.
- No se puede remover posiciones o modificar su tamaño.
- Su capacidad define al crearse.

Los arrays se usan en los sprites de los videojuegos, también en un menú de opciones por ejemplo. Son opciones definidas.

El módulo array de Python solo almacena números y caracteres. Está basado en listas.

**Nota**: Los arrays son un tipo de listas pero las listas no son arrays.


