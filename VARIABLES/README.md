# VARIABLES PYTHON

En la mayoría de lenguajes de programación existe el concepto de variables. Las variables permiten asignar nombres coherentes a información para ser reutilizada con facilidad.

---

## Asignaciones

La forma de dar valor a una variable se realiza por asignaciones y en Python pueden ser simples o múltiples.

En Python las asignaciones se hacen utilizando el carácter `=` y la dirección es hacia la izquierda, por tanto, se guarda en la parte izquierda lo que se ponga a la derecha.

En la parte izquierda hay que situar un identificador válido y a la derecha un literal o una expresión, que serán los datos a asignar al identificador.

```py
identificador = [literal o expresión]
```

### Asignaciones simples

En las siguientes asignaciones se asigna un valor a una única variable.

```py
str_color = 'Red'
num_of_cards = 56
pi_number = 13.1416
buy_list = ['Bread', 'Rise', 'Oil']
locations = {madrid=(40.26, 3.42), dublin=(53.20, 6.15)}
```

### Asignaciones múltiples

En las siguientes asignaciones se asignan valores a varias variables a la vez.

```py
str_red, str_blue = 'Red', 'Blue'
cards, half_cards = 56, 28
pi_number, g_force = [13.1415, 9.8]
ltr1, ltr2, ltr3 = 'Red'
```

### Literales y expresiones

Cuando se hacen asignaciones se pueden utilizar:

**Literales:** son datos descritos directamente en el código. Es información estática, puede ser simple o usar instancias de clases. La definición clave es que se conoce cuál será el valor asignado analizando el código.

```py
a = 1
msg = 'Hello World'
total = 78 + 3.24
cat = Cat('Garfield', aye=1.5)
is_active = True
```

**Expresiones:** son datos asignados tras la evaluación de una o varias sentencias. Suelen ser dinámicos y no se conoce el valor final analizando el código.

```py
a = arg1 + p
msg = 'Hello' + world_msg
position = prev_position + 89
```

### Keywords en Python

En Python hay algunas palabras reservadas en que no pueden ser utilizadas como identificadores válidos. Se pueden encontrar en `keyword.kwlist`, y son los siguientes.

```py
False    None    True    and    as    assert    async
await    break    class    continue    def    del    elif
else    except    finally    for    from    global    if
import    in    is    lambda    nonlocal    not    or
pass    raise    return    try    while   with    yield
```

Para saber si un nombre es un keyword o no se puede hacer comprobar usando `keyword.iskeyword`

```py
>>> keyword.iskeyword('red')
False
>>> keyword.iskeyword('as')
True
```

---

## TIPOS DE VARIABLES EN PYTHON

### TIPOS NUMÉRICOS

**Enteros (`int`):**

```py
numero = 10
```

**Float o Decimal (`float`):**

```py
decimal = 3.14
```

**Complex:** Números con una parte real y una parte imaginaria (`complex`):

```py
complex = 3+2j
```

### TIPO TEXTO

**String:** Secuencia de caracteres encerrada entre comillas simples o dobles (`str`):

```py
nombre= "PEPE"
apellido = 'Perez'
```

### TIPO BOOLEANO

Representan valores de verdad, con dos opciones posibles (`bool`):

```py
True False
```

### TIPOS DE COLECCION

**Lista:** Colecciones ordenadas y modificables (mutables) de elementos (`list`):

```py
lista = [1,True, "Pedro"]
```

**Tupla:** Colecciones ordenadas pero inmutables (no se pueden modificar tras su creación) (`tuple`):

```py
tuple = (1, False, "Perez")
```

**Rangos:** Secuencia de números, usada comúnmente en bucles (`range`):

```py
range(0,10)
```

**Diccionario:** Colecciones de pares con estructura clave-valor (`dict`):

```py
dict = {"Nombre": "Pepe", "Edad": 20}
```

**Conjuntos:** Colecciones desordenadas de elementos únicos (sin duplicados) (`set`):

```py
set = {1,2,3}
```

**Conjuntos inmutables:** Versión inmemorial o fija de un conjunto. (`frozenset`)

### OTRO TIPO ESPECIAL

**NoneType:** Representa la ausencia de valor o un valor vacío, cuyo único valor es `None`.

---

*INFORMACIONES SACADAS DE PAGINAS/INTERNET. PYTHONGUIONISTA.*