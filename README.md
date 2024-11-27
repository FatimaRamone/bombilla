Proyecto: BOMBILLA2 - Interruptor de Luz Interactivo

Este proyecto consiste en una página web que simula el encendido y apagado de una bombilla utilizando un interruptor interactivo. La página cuenta con un fondo negro, una bombilla que cambia entre los estados "encendido" y "apagado", y un interruptor visual que permite al usuario cambiar el estado de la bombilla.
Características

    Cambio Visual de la Bombilla:
        La bombilla se muestra en dos estados: encendida (bombillaON.png) y apagada (bombillaOFF.png).
        Un interruptor en la parte inferior permite cambiar entre estos dos estados, simulando la acción de encender y apagar la luz.

    Estilo y Diseño:
        El fondo de la página es de color negro, lo que resalta las imágenes de la bombilla y el interruptor.
        El interruptor tiene un diseño estilizado con sombras y efectos para dar una apariencia más realista.

    Interactividad:
        El interruptor es un control de tipo checkbox que, cuando se marca, cambia la visualización de las imágenes de la bombilla, mostrando la bombilla apagada y viceversa.

Estructura del Proyecto

    HTML:
        La estructura está formada por dos imágenes (bombillaON y bombillaOFF), y un interruptor (implementado con un checkbox y un label).
        El input de tipo checkbox permite el control de la interacción con el interruptor.

    CSS:
        Se utiliza un fondo negro para la página.
        Las imágenes de la bombilla (bombillaON y bombillaOFF) están centradas en la página utilizando posicionamiento absoluto.
        El interruptor tiene un diseño en forma de palanca, con un estilo que incluye bordes redondeados y sombras para simular profundidad.

    JavaScript:
        Se utiliza un script que escucha el evento change del interruptor (checkbox).
        Dependiendo de si el interruptor está activado o no, la bombilla apagada o encendida es mostrada/ocultada cambiando su propiedad display.

Instrucciones de Uso

    Abrir el archivo HTML en un navegador web para interactuar con el interruptor.
    Imágenes:
        Asegúrate de tener las imágenes bombillaON.png y bombillaOFF.png en el mismo directorio que el archivo HTML o ajusta las rutas de las imágenes si están en otra ubicación.
    Interactividad:
        El usuario puede interactuar con el interruptor para ver cómo cambia la bombilla entre el estado encendido y apagado.

Mejoras Posibles

    Efectos de Animación:
        Se pueden agregar animaciones para que el cambio entre los estados de la bombilla sea más suave (por ejemplo, utilizando transition para animar el encendido y apagado).

    Más Controles:
        Añadir más controles como un dimmer o un cambio de color para hacer la simulación más realista.

    Compatibilidad Móvil:
        Asegurarse de que el diseño sea completamente responsivo para adaptarse a dispositivos móviles y tablets.

Este proyecto es ideal para aprender a manejar imágenes, formularios interactivos, y efectos visuales básicos en HTML, CSS y JavaScript.
