## Introducción a python

En los siguientes ejemplos usaremos el símbolo [>>>]() para simular que un código se está introduciendo a la terminal interactiva de python.

### Tipos de datos
Aprendimos los tipos de datos más básicos para el uso de python

| tipo            | nombre en python | ejemplo       |
| --------------- | :--------------: | ------------: |
| número entero   |       int        |       10      |
| número decimal  |       float      |       8.5     |
| cadena de texto |       str        |  'Hola mundo' |

### Funciones built-in de python
Vimos algunas funciones que python incluye para facilitarnos el trabajo.

```python
#Para imprimir textos en la consola
print('texto\n')
```

```python
#Para leer textos desde la consola
input('introduce un número: ')
```

```python
#Para obtener el tipo de dato que almacena una variable
type(variable)
```

### Variables
Las variables son el medio por el cual almacenamos los datos con los que trabajamos durante la ejecución de un programa.

Como vimos, python es un lenguaje de tipado dinámico, es decir que para crear variables NO tendremos que indicar qué tipo de dato contendrán (entero, decimal, texto),
solo necesitaremos asignarle un nombre y un valor inicial.
```python
>>> nombre = 'Carlos' #Crea la variable "nombre" y le asigna una cadena de texto que dice "Carlos"
>>> edad = 24 #Crea una variable "edad" y le asigna un valor numérico entero "24"
```

Una vez creada una variable podemos usarla a lo largo del programa, podemos leer su valor (por ejemplo para imprimirlo en pantalla)
```python
>>> nombre = 'Carlos'
>>> print(nombre)
'Carlos'
```

También podemos modificar el valor de la variable. (recuerda que en la terminal interactiva no necesitamos usar la función print(), solo introducir el nombre de la variable que deseamos verificar)
```python
>>> nombre = 'Carlos'
>>> nombre
'Carlos'
>>> nombre = 'Daniel'
>>> nombre
'Daniel'
```
También podemos asignar nuevos valores de tipos diferentes a nuestras variables, gracias a que python es un lenguaje con tipado dinámico.
```python
>>> nombre = 'Carlos' #Una variable tipo string (cadena de texto), abreviado en python como "str"
>>> type(nombre)
<class "str">
>>> nombre = 0 #Un nuevo valor tipo int (número entero), abreviado en python como "int"
>>> type(nombre)
<class "int">
```

### Operadores
Como vimos en clase, existe varios tipos de operadores en python, los principales son los operadores aritméticos, operadores de comparación y operadores booleanos.

#### Operadores aritméticos principales
Las operaciones básicas de python son:

  | operación                       | símbolo  | ejemplo   | resultado |
  | ------------------------------- | :------: | :-------: | -: |
  | suma                            |     +    |   2 + 2   | 4 |
  | resta                           |     -    |   2 - 2   | 0 |
  | multiplicación                  |     *    |   2 * 2   | 4 |
  | división                        |     /    |   5 / 2   | 2.5 |
  | división entera (sin decimales) |     //   |   5 // 2  | 2 |
  | resudio de división entera      |     %    |   5 // 2  | 1 |
