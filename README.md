# kotlin
curso de kotlin de google

Learn more about the course goals and requirements in this introduction to Unit 1. To check if your computer can download Android Studio, see the system requirements at the 
bottom of this page: https://developer.android.com/studio

Se puede entender un programa como una serie de instrucciones para que un sistema realice una acción. Por ejemplo, podrías escribir un programa que cree una tarjeta de cumpleaños
y, en él, una instrucción para imprimir un texto de felicitación o calcular la edad de una persona en función de su año de nacimiento.

De la misma manera en la que usas un lenguaje humano para comunicarte con otra persona, debes usar un lenguaje de programación para comunicarte con el sistema operativo de tu
computadora. Afortunadamente, los lenguajes de programación son menos complejos que los humanos y son bastante lógicos.

Las apps para Android se escriben en lenguaje de programación Kotlin. Kotlin es un lenguaje moderno creado para ayudar a los desarrolladores a escribir código de forma eficaz y
con la menor cantidad de errores posible.

Aprender a crear una app al mismo tiempo que aprendes los conceptos básicos de programación no será fácil. Por eso, comenzaremos con un poco de programación antes de comenzar 
con la creación de la app. Conocer los conceptos básicos no solo es un primer paso importante en la creación de apps, sino que además te facilitará crear tu primera app más
adelante en este curso.

Los editores de código son herramientas que te permiten escribir código, al igual que un procesador de texto (como Documentos de Google) te ayuda a crear documentos de texto. 
En este codelab, usarás un editor de Kotlin interactivo en tu navegador. Esto significa que no necesitas instalar ningún software para dar tus primeros pasos en el desarrollo 
de apps.

fun main() {
    println("Hello, world!")
}

Ejecutar un programa creado por ti no es muy diferente a ejecutar un procesador de texto en la computadora. La diferencia es que cuando ejecutas un programa para completar una
tarea o para jugar, lo que más te interesa es lo que el programa puede hacer por ti y no el código que lo hace posible. Cuando programas, puedes ver el código que hace la magia 
y trabajar con él.

La compilación es un proceso que convierte el código del programa en Kotlin en un formato que el sistema puede ejecutar. Si la compilación se completa correctamente, no habrá
errores que impidan que el programa se ejecute. Si hay errores, aparecerán en el panel ubicado en la parte inferior.
Si quieres que un amigo escriba "Hello World" en un papel, habrá mucha información implícita. Si solo le dices "Escribe 'Hello World' en este papel", hará suposiciones sobre la información que no le proporcionaste. Por ejemplo, supondrá que necesita un bolígrafo y que quieres que lo escriba en letras. La computadora no realiza estas suposiciones, por lo que debes brindarle instrucciones precisas que incluyan cada paso.

Al igual que los idiomas humanos, los lenguajes de programación tienen estructuras. Si alguna vez estudiaste un segundo idioma, sabrás el desafío de aprender la gramática, la ortografía, quizás un nuevo alfabeto de símbolos y el vocabulario de ese idioma. Si bien aprender a programar tiene desafíos similares, afortunadamente, es menos complejo y más lógico que, por ejemplo, aprender inglés.

fun es una palabra en lenguaje de programación Kotlin. fun significa "función". Una función es una sección del programa que realiza una tarea específica.
Nota: Kotlin tiene muchas palabras especiales con significados muy específicos, que conocerás a medida que aprendas a programar en este lenguaje. Por lo general, se denominan palabras clave o palabras reservadas.

main es el nombre de esta función. Las funciones tienen nombres, a fin de poder distinguir unas de otras. Esta se llama main porque es la primera función, o la principal, a la que se llama cuando ejecutas el programa. Todos los programas en Kotlin necesitan una función llamada main.

El nombre de la función siempre va seguido de dos paréntesis ().
Dentro de los paréntesis, puedes ingresar información que usará la función. Esta información de entrada de la función se denomina "argumentos" o, de forma abreviada, args. Seguirás aprendiendo sobre los argumentos más adelante.

Pon atención al par de llaves {} después de los paréntesis. Dentro de una función, se incluye código que permite completar una tarea. Las llaves rodean esas líneas de código.

println("Happy Birthday!")

Esta línea de código imprime el texto Happy Birthday!.

println le indica al sistema que imprima una línea de texto.
Dentro de los paréntesis, debes ingresar el texto que quieras imprimir.
Verás que ese texto está entre comillas. Esto le indica al sistema que todo lo que está dentro de las comillas se debe imprimir tal como está.
Para que el programa imprima el texto, toda la instrucción println debe estar dentro de la función main.

Eso es todo. El programa más pequeño escrito en Kotlin.

fun main() {
    println("Happy Birthday!")
}

Bien hecho. Imprimiste una línea de texto con la función println() function. Sin embargo, puedes escribir tantas líneas de instrucciones dentro de una función como desees o necesites para realizar una tarea.

Copia la línea println("Happy Birthday!") y pégala debajo dos veces más. Asegúrate de que las líneas que pegues estén dentro de las llaves de la función main.
Cambia una parte del texto que deseas imprimir por un nombre, como "Jhansi".
Cambia el otro texto que se imprimirá a "¡Tienes 25!".
El código debería ser similar al siguiente:

fun main() {
    println("Happy Birthday!")
    println("Jhansi")
    println("You are 25!")
}

Es normal cometer errores mientras programas, y la mayoría de las herramientas disponibles te brindarán comentarios para que los corrijas. En este paso, crearás un error para ver qué sucede.

En tu programa, quita las comillas alrededor del texto Jhansi. La línea se verá así:

println(Jhansi)

Ejecuta el programa. Deberías ver el texto Jhansi impreso en rojo y un signo de exclamación junto a la línea de código que modificaste. De esa forma, se indica dónde hay un error.

Observa el panel de resultados. Aparecerá un mensaje con el mismo ícono de signo de exclamación y la palabra Error. A continuación, se muestra una descripción del error en tu código.

El mensaje, Unresolved reference: Jhansi, te indica lo que el sistema considera que es un error en el código. Incluso si no sabes qué significa el mensaje de error, es posible que puedas entender cuál es el problema. En este caso, sabes que la instrucción println() imprime texto. Ya aprendiste que el texto debe estar entre comillas. Si no está entre comillas, se generará un error.
Agrega las comillas nuevamente.
Ejecuta el programa para asegurarte de que vuelva a funcionar.
¡Felicitaciones! Ejecutaste y modificaste tu primer programa en Kotlin.

 Resumen
https://developer.android.com/training/kotlinplayground es un editor de código interactivo en la Web que te permite practicar programación en Kotlin.
Todos los programas en Kotlin deben tener una función main(): fun main() {}.
Utiliza la función println() para imprimir una línea de texto.
Coloca el texto que deseas imprimir entre comillas dobles. Por ejemplo: "Hello".
Repite la instrucción println() para imprimir varias líneas de texto.
Los errores se marcan en rojo en el programa. Verás un mensaje de error en el panel de resultados que te ayudará a determinar dónde está el error y cuál puede ser la causa.

ia las instrucciones println() por print().
Ejecuta el programa. ¿Qué ocurre entonces?
Sugerencia: La instrucción print() imprime el texto sin agregar un salto de línea al final de cada string.

Corrige el texto para que cada parte del mensaje esté en una línea separada.
Sugerencia: Usa \n dentro del texto para agregar un salto de línea. Por ejemplo, "line \n break". Si agregas un salto de línea, el resultado cambiará como se muestra a continuación.

Sugerencia: Puedes imprimir una línea vacía si no ingresas texto (por ejemplo: println("")).

