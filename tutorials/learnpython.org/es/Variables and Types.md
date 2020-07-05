Tutorial
--------

Python está completamente orientado a objetos, y no es "escrito estaticamente". No necesitas declarar variables o el tipo antes de usuarlas. Cada variable en Python es un objeto y así cada objeto soporta las siguientes instrucciones:

**help(object)** - Muestra información de como usar objetos.

**dir(object)** - muestra que la estructura interna del objeto - y sus metodos y miembros.

Este tutorial explorará algunos tipos basicos de variables.

### Números
Python soporta dos tipos de números - integrales y numeros de punto flotante. (Tambien soporta números complejos, los cuales no se explicarán en este tutorial). 

Para definir un integral (un número entero), usa la siguiente sintaxis:

    miIntegral = 7

Para definir un número de punto flotante (un número con decimales), debes usar una de las siguientes notaciones:

    miflotante = 7.0
    miflotante = float(7)

### Cadenas

Las cadenas (grupos de caractéres) pueden definirse con comillas sencillas o compuestas.

    micadena = 'Hola'
    micadena = "Hola"

La diferencia ente las dos es que al usar doble comillas se pueden incluir comillas simples dentro de la cadena (de lo contrario la cadena concluiría si se usa doble comillas)

        micadena = "No te preocupes de los 'apostofres' usando comillas dobles"

Hay más variaciones para definir cadenas, para incluír saltos de línea, barras inclinadas hacia atrás "\" y carácteres Unicode. Estos se encuentran por encima de lo intencionado en este tutorial. Pero están bien explicados en la [Python documentation](http://docs.python.org/tutorial/introduction.html#strings "Strings in Python Tutorial").

Operadores sencillos pueden ser ejecutados en números o cadenas:

    uno = 1
    dos = 2
    tres = uno + dos

    hola = "hola"
    mundo = "mundo"
    holamundo = hola + " " + mundo

Se puede asignar a mas de una variable simultaneamente en la misma linea, como se muestra aquí

    a, b = 3, 4

Pero no funcionan si operamos entre números y cadenas:

    # Esto no funcionará!
    print uno + dos + hola


### Ejercicio

La finalidad de este ejercicio es crear una cadena, un integral y un punto flotante. La cadena debe llamarse micadena y debe contener la palabra "hola". El punto flotante debe llamarse miflotante y debe contener el número 10, y el integral debe llamarse miIntegral y debe contener el número 20.

Tutorial Code
-------------
# Escribe tu propio codigo aqui


# probando el codigo
if micadena == "hola":
    print "Cadena: %s" % micadena
if isinstance(miflotante, float) and miflotante == 10.0:
    print "Flotante: %d" % miflotante
if isinstance(miIntegral, int) and miIntegral == 20:
    print "Integral: %d" % miIntegral

Expected Output
---------------
Cadena: hola
Flotante: 10
Integral: 20

Solution
--------
micadena = ("hola")
miflotante = float(10)
#o miflotante = 10.0
miIntegral = 20 
