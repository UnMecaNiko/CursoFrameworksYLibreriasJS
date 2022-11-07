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

## Librería

Herramienta con una utilidad específica.

## Framework

Conjunto de herramientas que trabajan en un proyecto completo bajo ciertas reglas.

## Ecosistema de frameworks y librerías

### Empaquetadores

En vez de hacer una consulta para cad archivo se empaquetan todos los archivos en uno solo, este proceso se optimiza para que el navegador demore lo menos posible. WebPack es una de las herramientas más populares. Parcel simplifica el proceso sin tener que hacer archivos de configuración, el proceso es automático. 

> Webpack para construir sitios y aplicaciones web, rollup para librerías en JS.

### Compiladores

(no son exactamente compiladores pero cumplen la función de transformación de código)

- Babel: Es un transpirador, permite utilizar ECMA Script, por meio de plugins permite programar de otras formas que JS no permite.

- TypeScript: Es otro lenguaje de programación (subset), tipado y orientado a objetos, una de sus mayores ventajas es la inyección de dependencias.

### Herramientas para UI

Vistas e interacción con los usuarios, puede ser sólo JS peero, un framework es una mejor herramienta. Transforman componentes en un render on el que puede interactuar el usuario.

### Css y preprocesadores

Permiten mayor comodidad para la escritura de los estilos.

- Css-in-JS: En un mismo componente se usan css, html y JS. Unas de las herramientas son estyled components, radium, afrodit, etc.

### Routers

Son la forma en la que hacemos la navegación de nuestra aplicación.

### Frameworks

Son hel todo en uno, se encargan de administrar casi todos los elementos mencionados anteriormente.

### Manejo de estado

(Redux, XState o MobX)

Organización de comunicación entre componentes, cuando se cambia algo en el estado de la aplicación estas herramientas facilitan la administración de nuesvas características.

### Consulta de datos

(API Rest o GraphQL)

Protocolos para comnicarse con el packet para enviar y recibir información de los usuarios.

La mejor forma de organizar una aplicación es organizarla por capas, esto es bueno en medida de que se puede trabajar en cada parte sin tener problemas con afectar las otras.

# Contexto y funcionamiento de los Frameworks JavaScript

## Qué es React y cómo se construyó

> EcmaScript es la especiicación del lenguaje JS

Jordan Walke creo React en mayo de 2013. Influenciado por el problema de implementación de anuncios de Facebook, eventualmente Reat se volvió open source, aunque sigue siendo de Facebook, luego llegaron las herramientas para debugging.

Con el tiempo más y más empresas lo implementaron en sus páginas.

### Caracteristicas de React

- Declarative: Es fácil de entender y leer.
- Component-Based.
- Learn One, Write anywhere: React es multiplataforma.

### Componentes

![](https://static.platzi.com/media/user_upload/9-diagrama-ciclo-de-vida-bdf72607-e2a8-44b4-a075-72296dafb7ce.jpg)

## Qué es Angular y cómo se construyó

Tiene un sistema para crea componentes llamado engine modules, agrupan componentes que acuden a un mismo fin.

Componente: lógica e interfaz e usuario con el que la interacción es real. 

Incemental DOM: cada componente se convierte en una instrucción por lo qu nose crean copias del DOM, así se ahorra memoria.         

# Fuentes de información

- [Basic writing and formatting syntax | GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

- [Webpack vs. Parcel vs. Rollup vs. ESBuild | Empaquetadores de JavaScript](https://platzi.com/blog/empaquetadores-javascript/)

- [Webpack and Rollup: the same but different](https://medium.com/webpack/webpack-and-rollup-the-same-but-different-a41ad427058c)

- [¿Qué es CSS-in-JS?](https://platzi.com/clases/1601-react-avanzado/21258-que-es-css-in-js/)

- [React](https://es.wikipedia.org/wiki/React)

- [ReactSimple-PlatziIntroFrameworks - CodeSandbox](https://codesandbox.io/s/reactsimple-platziintroframeworks-zqenr?file=/src/App.js)