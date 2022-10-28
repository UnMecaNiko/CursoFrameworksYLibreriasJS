# Curso de Frameworks y Librerías de JavaScript

¿React, Vue, Angular o Svelte? Comprende la diferencia entre un framework y librería de JavaScript. Explora el ecosistema del desarrollo frontend y compara las ventajas de sus herramientas principales. Descubre el poder de usar componentes, reactividad, CSS-in-JS y estrategias de routing en el diseño de una aplicación web.

- Aprende cómo se compone un stack profesional de desarrollo frontend
- Utiliza los principales frameworks y librerías de JavaScript
- Divide tu aplicación web en componentes
- Integra preprocesadores y CSS-in-JS

💚 Lo que verás a continuación son mis apuntes de las clases 💚

# Fundamentos del Desarrollo Web Profesional

> Cuando es un sitio web que únicamente se encarga de mostrar información, es un Website, pero cuando empezamos a involucrar al usuario, a permitirle manipular la página, a permitirle ingresar datos, procesarlos y demás, es cuando se vuelve una Webapp y para esto es cuando nos apoyamos de JavaScript.

Conforme pasa el tiempo JavaScript se convierte en la herramienta principal para la maquetación de las páginas sobre HTML, esto nos permite tener páginas reactivas, componentes reutilizables y comportamientos condicionales.

Desde JavaScrpt podemos generar componentes HTML, cambiar sus parámetros, comportamiento, quitarlos, etc.

Un componente puede tener todo tipo, comportamiento o aspecto, la composición de componentes se refiere a la unión de elementos básicos para crear bloques más complejos.

## Cómo estructurar un componente

Cuando se tiene una página con muchos tipos de componentes es importante tener orden en la identificación de estos y su clasificación, generalmente se empieza desde las páginas, luego en las partes principales de la página.

## Reactividad

> Un paradigma es una forma de pensar y traducir la ideas a código

La reactividad es un paradigma que sigue ciertos lineamientos:

- **Responsive** Son resilientes y escalables. La aplicación sabe qué hacer en situaciones problema (caida de servidor, error de usuario), la app también puede crecer sin generar problemas.

- **Message Driven** Programar la app con emisores y receptores de mensajes, los mensajes se transmiten   asincrónicamente, el gestionador de q´s se encarga de administrar los mensajes recibidos, clasificarlos y avisar a los receptores que estén suscritos a la categoría que tenga mensajes nuevos. Para el funcionamiento de este proceso se usan observers.

Estado: Lugar donde se guarda la información reactiva de los componentes, no todos los frameworks lo llaman de la misma forma. Cuando el usuario interactúa o hay nueva información se actualiza del state

Render: Proceso por el cual el código html se convierte en información visual en el DOM. 
Hay distintas estrategias para hacer render:

- Virtual DOM: Se evalúa cuales son los componentes que se deben renderizar para no hacer un render completo de la página, es costoso, por lo que se prefiere guardar una copia del DOM con JavaScript para identificar qué partes cargar.

Cada framework usa una estrategia distinta y es importante identificarlas para tener argumentos con los cuales elegir el que más se adapte a nuestras necesidades.




# Fuentes de información

- [Basic writing and formatting syntax | GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)




