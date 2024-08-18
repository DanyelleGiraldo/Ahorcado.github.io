# Juego del Ahorcado

Este es un juego clásico del ahorcado implementado utilizando JavaScript, HTML y CSS. El objetivo del juego es adivinar una palabra oculta antes de quedarse sin intentos. Los jugadores ingresan letras y el juego proporciona retroalimentación sobre las letras adivinadas y los intentos restantes.

## Descripción del Proyecto

El juego del ahorcado presenta una palabra oculta que el jugador debe adivinar letra por letra. Con cada letra incorrecta, se muestra una imagen progresivamente más completa del ahorcado. El juego termina cuando el jugador adivina la palabra correctamente o se queda sin intentos.

## Uso
Inicia el Juego: Haz clic en el botón "Iniciar" para comenzar el juego.
Ingresa Letras: Escribe una letra en el campo de entrada y presiona "Enter" para adivinar.
Observa el Estado del Juego: La interfaz se actualizará para mostrar la palabra con las letras adivinadas, los intentos restantes y las letras incorrectas.

## Variables Globales
Se definen las variables globales para manejar los elementos del DOM y el estado del juego. Incluyen el botón de inicio, el contenedor de letras, el campo de entrada de letras y la imagen del ahorcado.

## Funciones Principales
inicializarJuego: Esta función inicializa una nueva partida seleccionando una palabra aleatoria de una lista predefinida. Establece el estado inicial del juego, incluyendo la palabra oculta, las letras adivinadas, los intentos restantes y las letras incorrectas.

imgsahorcado: Actualiza la imagen del ahorcado según el número de errores cometidos. Utiliza un conjunto de imágenes que representan el progreso del ahorcado en función del número de intentos restantes.

actutualizarinterfaz: Actualiza la interfaz de usuario en tiempo real para mostrar la palabra con las letras adivinadas, el número de intentos restantes y las letras incorrectas. Llama a la función imgsahorcado para actualizar la imagen del ahorcado.

adivinarLetra: Procesa la letra ingresada por el jugador. Verifica si la letra está en la palabra oculta y actualiza el estado del juego en consecuencia. Si la letra es incorrecta, se resta un intento y se actualiza la imagen del ahorcado. También verifica si el jugador ha ganado o perdido el juego.

teclapresionada: Maneja la entrada del teclado, permitiendo que el jugador ingrese letras mediante la tecla "Enter". Verifica que la entrada sea válida (una sola letra) y llama a la función adivinarLetra para procesarla.

empezar: Configura el inicio del juego, ocultando el botón de inicio, mostrando los elementos del juego y inicializando el estado del juego. También agrega un listener para la entrada del teclado.

## Eventos
Click en el Botón de Inicio: Al hacer clic en el botón de inicio, se llama a la función empezar para iniciar una nueva partida.

## Enlace al Proyecto

Para más detalles, puedes acceder al proyecto en el siguiente enlace:

[Ahorcado](https://danyellegiraldo.github.io/Ahorcado.github.io/)
