# Aprendiendo python y Visual Studio Code

## 🔵 Fundamentos

## ¿Qué es programar?

Proceso de diseñar, escribir, probar y mantener el código fuente de programas informáticos.

## ¿Qué es Python y para qué sirve?

Python es un lenguaje de programación orientado a objetos.
Permite la creación de objetos y reutilización de código (facilitación de tareas complejas).

Python tiene muchas utilidades como:
1. Desarrollo web.
2. Analisis de datos.
3. Inteligencia artificial.
4. Automatización de tareas.
5. Ciencia e ingeniería.
6. Apps y videojuegos.

Es un lenguaje de código abierto y de alto nivel.

## ¿Qué es un lenguaje de alto nivel?

Por decirlo de cierta manera un lenguaje de alto nivel es aquel que se "comunica" más lejano al hardware. Se asemeja al lenguaje humano (es mas sencillo de entender).

## ¿Qué es un programa y cómo se ejecuta?

Un programa es un conjunto de instrucciones escritas en un lenguaje de programación (como Python) que una computadora puede seguir para hacer algo.

Ejecutar un programa significa ponerlo en marcha: que la computadora lea las instrucciones y las haga.
En Python, los pasos básicos son:

    Escribes el código en un archivo (por ejemplo: programa.py)

    Abres una terminal (como lo estás haciendo en Visual Studio Code)

    Escribes el comando para ejecutarlo:

## ¿Qué es una variable?
Una variable es como una cajita donde puedes guardar información para usarla más adelante.
Puedes ponerle un nombre a esa cajita y meterle lo que quieras: un número, un texto, un resultado, etc.

## Tipos de datos

Str: En Python, str es el tipo de dato que representa cadenas de texto (del inglés string). Se usa para guardar y trabajar con texto, como palabras, frases, letras, etc.

int: En Python, int es el tipo de dato que representa números enteros (integer en inglés). Es decir, números sin decimales.

float: En Python, float es el tipo de dato que representa números con decimales (viene de floating point number en inglés).

bool: En Python, bool es el tipo de dato que representa valores lógicos, o sea, verdadero o falso.

Los dos valores posibles de un bool son:

    True (verdadero)

    False (falso)

## Operadores aritméticos

En Python, los operadores aritméticos se usan para hacer operaciones matemáticas:


🔢 Operadores aritméticos básicos


1. (Suma +)

2. (Resta -)

3. (Multiplicación *)

4. (División /)

5. (División entera //)

6. (Módulo o resto %)

7. (Potencia **)

## Algunos comandos

print: El comando print() en Python se usa para mostrar información en pantalla. En mi opinión le doy lógica asimilandolo a su traducción al español.

input: El comando input() en Python se usa para pedirle datos al usuario. Detiene el programa y espera que el usuario escriba algo y presione Enter.

## Conversión de tipo o casting
Convertir tipos de datos: int(), float(), str().

¿Qué es convertir tipos?

Es cambiar el tipo de dato de un valor. Por ejemplo:

    De texto a número

    De número a texto

    De entero a decimal

_Si se quiere entender del todo, es mejor investigar aparte._

## Errores que cometí

En ocasiones me pasaba lo siguiente:

• No verificar que hace bien un comando antes de usarlo.

• Errores comunes de sintaxis por escribir rápido.

• No utilizaba bien la lógica de programación (por ejemplo, usaba elif cuando no había necesidad y era mejor utilizar un else).

_seguiré añadiendo errores que cometa_

## Lógica de programación 

*Comparar datos*

Algunos operadores de comparación:

• == igualdad: Comprueba si dos valores son iguales.

•!= desigualdad: Comprueba si dos valores son diferentes.

• > mayor que: Comprueba si un valor es mayor que otro.

• < menor que: Comprueba si un valor es menor que otro.

• >= mayor o igual que: Comprueba si un valor es mayor o igual que otro.

• <= menor o igual que: Comprueba si un valor es menor o igual que otro.

_Nota: Asegurarme que los datos que este comparando sean del mismo tipo._

### Toma de decisiones

Capacidad de un programa de tomar decisiones basadas en condiciones específicas. 

• Estructura de control de flujo (if): Si la condición es verdadera, se ejecuta el código dentro del bloque (if).

• Estructura de control de flujo (elif): Se utiliza para tomar decisiones basadas en múltiples condiciones. Si la condición (if) es falsa, se evalúa la condición (elif).

• Estructura de control de flujo (else): Se utiliza para ejecutar código cuando la condición (if) es falsa

### Combinación de condiciones 

Técnica para evaluar múltiples condiciones y tomar decisiones basadas en ellas. 

Algunos operadores lógicos:

• (and): Se utiliza para combinar dos condiciones que deben ser verdaderas para que la condición general sea verdadera.

• (or): Se utiliza para combinar dos condiciones donde al menos una de ellas debe ser verdadera para que la condición general sea verdadera.

• (not): Se utiliza negar una condición.

_Dentro de visual studio code podemos añadir comentarios utilizando "#" antes de el comentario que deseemos dejar, muy útil para dejar evidenciado la información y muchasas cosas._

## ¿Qué es la identacion y porque es tan importante en python?

Identacion » Se refiere al uso de espacios o tabuladores para identar líneas de código y definir bloques de código.

¿Por qué es tan importante en python?

• Define bloques de código.
• Determina la estructura del código.
• Evita errores de sintaxis.

## Buenas prácticas al nombrar variables 

Un buen nombre de variable debe de ser claro.

Al nombrar variables siempre debo de: 

• Utilizar nombres descriptivos.
• Utilizar nombres en minúsculas con "_" para nombres compuestos.
• Evitar nombres ambiguos.
• Utilizar nombres que indiquen el tipo de dato. 
• Escribirlos en inglés.

## ¿Qué hacer cuando algo no funciona?

Como nos han repetido ya en varias ocasiones la solución nunca será preguntar primero por la respuesta completa sino más bien despertar ese sentido curioso que que representa a los programadores.

Revisar el error, no frustrarme, investigar y si al final de todo eso el error persiste ahí si debo de preguntar.

## Esctructuras de control 

Repetir acciones con bucles: En python los bucles me permiten ejecutar un bloque de código varias veces.
Es util cuando necesito repetir una acción, sin tener que escribir el código una y otra vez.

Bucles más comunes en python: 

1. Bucle "for": Es útil cuando sabes de antemano cuántas veces deseas que se ejecute el bloque de código o cuando deseas recorrer una secuencia, como una lista, un rango de números, o una cadena de texto.

2. Bucle "while": Se utiliza cuando no sabes cuántas veces se repetirá el ciclo, pero sabes que debe continuar repitiéndose mientras se cumpla una condición.

Diferencias clave:

    El for es ideal cuando sabes cuántas veces quieres repetir algo o cuando estás trabajando con secuencias (listas, rangos, etc.).

    El while es más flexible, y se usa cuando no sabes exactamente cuántas veces se repetirá, pero necesitas que el ciclo continúe mientras se cumpla una condición.

