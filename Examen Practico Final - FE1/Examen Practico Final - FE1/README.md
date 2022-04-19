## El reto

Su desafío es crear esta página de destino y hacer que se parezca lo más posible al diseño.

Sus usuarios deberían poder:

- Ver el diseño óptimo para el sitio según el tamaño de la pantalla de su dispositivo
- Los aspectos que tendremos en cuenta para la corrección serán los siguientes:
         -Estructura correcta de HTML
         -Uso y correcta implementación de etiquetas semánticas
         -Adaptabilidad a dos tipos de dispositivos
         -Correcta implementación del fomulario
         -Imagens, iconos, fuentes, background
         -Implementación de Flexbox
         -Buenas Practicas en el CSS
         -Pseudoelementos y Pseudoclases 
         -(opcional) ---> Pequeñas animaciones

## Dónde encontrar todo

Su tarea es construir el proyecto con los diseños dentro de la carpeta `/ diseño`. Encontrará una versión móvil y de escritorio del diseño.

El diseño para mobile esta en formato estático JPG. Si desea hacerle cambios esteticos lo puede hacer a su gusto 

Se agrega link a Figma [https://www.figma.com/file/3PSyK3KYcmvbwK2OVFjFWm/Nico-Digital?node-id=4%3A2], con la oración anterior se hace referencia de que no siempre se le debe hacer caso a todo lo que nos dice esta herramienta.

Encontrará todos los recursos necesarios en la carpeta `/ imagenes`. Los activos ya están optimizados.

También hay un archivo `style-guide.md` que contiene la información necesaria, como la paleta de colores y las fuentes.

## Construyendo tu proyecto

No dude en utilizar cualquier flujo de trabajo con el que se sienta cómodo. A continuación se muestra un proceso sugerido: 

1. Revise los diseños para comenzar a planificar cómo abordará el proyecto. Este paso es crucial para ayudarlo a pensar en el futuro para que las clases de CSS creen estilos reutilizables.
2. Antes de agregar cualquier estilo, estructure su contenido con HTML. Escribir su HTML primero puede ayudarlo a enfocar su atención en la creación de contenido bien estructurado.
3. Escriba los estilos base para su proyecto, incluidos los estilos de contenido general, como `font-family` y` font-size`.
4. Comience a agregar estilos en la parte superior de la página y continúe hacia abajo.
5. Deje comentarios en el codigo en caso que lo crea necesario

## Envío de su solución

Envíe su solución en el google forms adjunto en PG, por favor adjuntar un archivo ZIP.

footer{
    padding: 50px 0;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.piePagina{
    flex-direction: column;
    align-items: center;
    gap:25px;
}

.redes{
    order: 3;
    flex-direction: column-reverse;
}

.redes>div{
    display: flex;
    gap:30px
}
.redes i{
    font-size: 1.5em;
    gap:15px;
}
.navFooter{
    width: 100%;
    padding: 15px;
    gap: 90px;
    order: 2;
    font-size: 0.7em;
}
.piePagina form{
    align-items: center;
    order: 1;
}
footer>p{
    position: relative;
    right:initial;
    bottom:initial;
    font-size: 0.5em;
    padding-top: 5em; 

}
