## Transformación de mayúsculas y minúsculas

upper(): Convierte todos los caracteres a mayúsculas:

```py
"hola".upper()
>>> HOLA
```
lower(): Convierte todos los caracteres a minúsculas:

```py
HOLA.lower()
>>> hola
```
capitalize(): Pone la primera letra en mayúscula y el resto en minúscula:

```py
"bienvenido a python".capitalize()

>>> Bienvenido a python
```

title(): Convierte a mayúscula la primera letra de cada palabra:

```py
"hola mundo".title()
>>> Hola Mundo
```
swapcase(): Intercambia mayúsculas por minúsculas y viceversa:

```py
"PyThOn".swapcase()

>>> pYtHoN
```

## Búsqueda y conteo

count(sub): Cuenta cuántas veces aparece un subtipo o carácter en la cadena:

```py
"manzana".count("a")
>>> 3
```
find(sub): Busca un subtipo y devuelve el índice de su primera aparición (si no lo encuentra, devuelve -1):

```py
txt = "Hello, welcome to my world."

x = txt.find("welcome")

>>> 7
```
rfind(sub): Busca un subtipo empezando por el final de la cadena (de derecha a izquierda).

```py
txt = "Mi casa, su casa."

x = txt.rfind("casa")

>>> 12
```
startswith(prefijo): Devuelve True si la cadena empieza con el texto indicado:

```py
txt = "Hello, welcome to my world."

x = txt.startswith("Hello")

>>> True
```
endswith(sufijo): Devuelve True si la cadena termina con el texto indicado:

```py
txt = "Hello, welcome to my world."

x = txt.endswith("Hello")

>>> False
```


## Validación (devuelven True o False)

isalpha(): Verifica si todos los caracteres son letras.
isdigit(): Verifica si todos los caracteres son números.
isalnum(): Verifica si son letras y/o números (alfanuméricos).
isspace(): Verifica si la cadena contiene únicamente espacios en blanco.
isupper() / islower(): Comprueban si todos los caracteres están en mayúsculas o en minúsculas.

## Modificación y limpieza

replace(viejo, nuevo): Reemplaza todas las apariciones de un subtipo por otro.

strip(): Elimina los espacios en blanco (o caracteres específicos) al inicio y al final de la cadena.

lstrip() / rstrip(): Eliminan los espacios o caracteres solo del lado izquierdo (lstrip) o del lado derecho (rstrip).
split(separador): Divide la cadena en una lista usando el separador indicado (por defecto, los espacios).

join(iterable): Une los elementos de una lista o iterable usando la cadena actual como pegamento ("-".join(["a", "b", "c"]) -> "a-b-c").