# ¿Qué son las iterativas o ciclos?
Estos son unas estructuras de control que se usan con la función de repetir un bloque de código N cantidad de veces (siendo N un número natural o entero).
También se les llama bucles.

# ¿Para qué sirven las iterativas?
- Repetir tareas automáticamente
- Recorrer listas, arreglos o cadenas (estos los verás en fundamentos de informática o más adelante)
- Contar, sumar o procesar datos
- Ejecutar acciones hasta que se cumpla una condición

# Tipos de ciclos a utilizar en c++
## for
Este se utiliza para realizar las iterativas conociendo de antemano la cantidad de veces que se realizará la acción. Ej: "Mezcle la masa 5 veces hacia la derecha".

## while
Este se utiliza para poder hacer que sus ciclos se hagan de forma indefinida, dependeiendo de si se hará o no según una condicional (tema visto en archivo 04 y 05), pero siempre se debe evaluar la condición.
Ej: "Si el número es menos a 10, sume 1 y muéstrelo".

## do - while
Este es muy similar al anterior, teniendo por diferencia el detalle de que este se realizará SIEMPRE por lo menos una única vez, ya que primero se ejecuta el bloque de código y luego cae en el ciclo.
Ej: "Muestre el número, si es menor a 23, súmele 1 y vuelva a mostrar".


# palabras clave importantes en los ciclos
Dentro del funcionamiento de estas estructuras se pueden utilizar distintas herramientas o palabras para hacer cambios en el flujo del programa, un ejemplo de esto son las siguientes palabras a explicar: 
- Break: Esta se utiliza para poder salirnos del funcionamiento de la iterativa por completo, haciendo que continuemos con el siguiente bloque de código dentro del archivo o programa a ejecutar.
- Continue: Este únicamente se utiliza para "brincarnos" un vuelta de los ciclos, no funciona en condicionales porque ellas no se repiten. Ej: "Si es par, sume 1; si es impar, no haga nada". En esta frase, el "no haga nada" sería el continue.
- return: Este lo verás en más parte de tu código, pero este funciona para poder dar fin a un método (puedes ver qué es un método más adelante del curso, pero, básicamente, es donde se trabaja una tarea específica para obtener cierto resultado).
