# ¿Qué son las condicionales?
Las condicionales son estructuras de control que permiten que nuestro programa tome decisiones y ejecute diferentes instrucciones según si se cumple una condición o no.
Básicamente: "Si se cumple esto, haz tal tarea; si no, haz esta otra".

## ¿Para qué sirven las condicionales?
Estas se pueden utilizar en diferentes escenarios, por ejemplo:
- Controlar escenarios
- Tomar decisiones
- Ejecutar ciertas partes del programa solo si una condición sucede o es verdadera

## ¿Cómo funcionan?
Las condicionales evalúan una expresión lógica, cuyo resultado siempre es:
- Verdadero (true)
- Falso (false)

Dependiendo del resultado, el programa decide qué camino seguir.
Los tipos de condicionales son:

## if(Si)
Este ejecuta su bloque de código (lo que posea entre sus "{}") solo cuando su condición es verdadera. Ej: "Si llueve, llevo paraguas".

## if - else if - else (si's anidados)
Este es útil cuando más de una condición es poosible y puede ser verdadera cualquiera. Ej:

- if (calificacion >= 90) { devuelve "Excelente" }
- else if (calificacion >= 70) { devuelve "Bueno" }
- else { devuelve "Insuficiente" }

## if-else (Si-no)
Este permite tener solo dos caminos, ya que si no se cumple una condición, se irá automáticamnete a otra:

- if (calificacion >= 70) { devuelve "Aprobado" }
- else { devuelve "Suspendido" }
  
## switch (Casos)
En ciertos casos, se pueden tener varios escenarios posibles en la evaluación de una sola variable, siendo esto necesario trabajarse por medio de los switch's:
-
switch (dia) {
    case 1:
        System.out.println("Lunes");
        break;
    case 2:
        System.out.println("Martes");
        break;
    default:
        System.out.println("Día inválido");
}




