# Juego de Aventura: ¡El Héroe y el Cofre!

Este es un juego interactivo en el que el jugador controla a un héroe en un tablero y debe llegar a un cofre. El héroe avanza lanzando un dado, y el objetivo es llegar al cofre antes de que se acumulen demasiadas tiradas. Al alcanzar el cofre, el juego termina y se muestra el número de tiradas realizadas.

## Funcionalidades

- **Ingreso de nombre:** El jugador debe ingresar su nombre antes de comenzar el juego. El nombre debe tener al menos 4 caracteres y no contener números.
- **Tablero de juego:** El tablero es una cuadrícula 10x10 donde el héroe empieza en la esquina superior izquierda (0,0) y el cofre se encuentra en la esquina inferior derecha (9,9).
- **Tiradas de dado:** El jugador lanza un dado (número aleatorio entre 1 y 6) para mover al héroe. Cada tirada aumenta el contador de tiradas.
- **Victoria:** El juego termina cuando el héroe llega al cofre. Al final, el juego muestra el número total de tiradas realizadas.
- **Historial de tiradas:** El número de tiradas se guarda en `localStorage` para que se conserve entre sesiones.
- **Récord personal:** El jugador puede establecer un nuevo récord de tiradas si lo consigue.

## Requisitos

- Un navegador web moderno con soporte para JavaScript.
- El proyecto es ejecutable directamente desde un navegador web sin necesidad de instalar dependencias adicionales.

