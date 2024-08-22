# Juego del Ahorcado

Este proyecto es una implementación simple del clásico juego del Ahorcado en Java. El objetivo del juego es adivinar una palabra secreta letra por letra antes de que se agoten todos los intentos.

## Características

-   **Palabra secreta predeterminada:** El juego utiliza una palabra secreta que el jugador debe adivinar.
-   **Sistema de intentos:** El jugador tiene un número limitado de intentos (por defecto, 10) para adivinar la palabra.
-   **Verificación de letras:** El juego verifica si las letras ingresadas están presentes en la palabra secreta, actualizando las letras adivinadas correctamente en la palabra oculta.
-   **Interfaz de consola:** Toda la interacción del juego se realiza a través de la consola, lo que lo hace fácil de usar y comprender.
-   **Gestión de mayúsculas/minúsculas:** El juego no es sensible a mayúsculas, por lo que las letras ingresadas se consideran en minúsculas para simplificar la experiencia del usuario.

## Cómo Jugar

1.  **Ejecución del juego:**
    
    -   Clona este repositorio en tu máquina local.
    -   Compila y ejecuta el archivo `Ahorcado.java`.
2.  **Reglas del juego:**
    
    -   El juego seleccionará una palabra secreta.
    -   El jugador debe intentar adivinar la palabra, ingresando una letra en cada turno.
    -   Si la letra está en la palabra, se revelará en la posición correspondiente.
    -   Si la letra no está en la palabra, se descontará un intento.
    -   El juego continúa hasta que el jugador adivina la palabra completa o se queda sin intentos.
3.  **Finalización del juego:**
    
    -   Si el jugador adivina la palabra antes de quedarse sin intentos, ganará.
    -   Si se acaban los intentos sin adivinar la palabra, el juego mostrará la palabra secreta y finalizará.

## Requisitos

-   **Java Development Kit (JDK) 8 o superior.**

## Ejemplo de Ejecución


    Palabra a adivinar: _ _ _ _ _ _ _ _ _ _
    11 letras
    
    Introduce una letra, por favor:
    a
    
    ¡Incorrecto! Te quedan 9 intentos.
    
    Palabra a adivinar: _ _ t _ l _ g _ n _ _ _
    11 letras
    
    Introduce una letra, por favor:
    n
    
    ¡Correcto!
    
    ...

## Contribuciones

¡Las contribuciones son bienvenidas! Si tienes alguna mejora o nueva funcionalidad que te gustaría agregar, no dudes en abrir un issue o enviar un pull request.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para obtener más detalles.
