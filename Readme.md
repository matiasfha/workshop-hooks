# 🎉 Bienvenido 

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

## 🚌 React Hooks

- Demo app:
React hooks, este es el nombre con que React ha bautizado la API que te permite desarrollar aplicaciones dinámicas e interactivas con React, hooks es una colección de funciones nativas a React que permiten que tus componentes reaccionen a diferentes estimulos propocionando dinamismo a tu aplicación o sitio web.

En este workshop aprenderás lso conceptos necesarios para otorgar dicho dinamismo a tus aplicaciones utilizando las diferentes herramientas o hooks proporcionados con React. Aprenderás cómo utilizar estas funciones para resolver el problema más importante a la hora de desarrollar: Manejar el estado de tus componentes.

## 👨🏻‍💻 Resumen del Workshop

Ok. ¿listo y ansioso de aprender?, genial, este será un viaje divertido y lleno de desafíos. Algunas de las cosas que podrás aprender serán:

- ¿Qué es manejo de estado?
- ¿Qué es el estado de una aplicación o componente?
- ¿Cómo manejar un estado en un componente? (`useState`)
- ¿Cómo manejar un estado complejo en un componente? (`useReducer`)
- ¿Cómo interactuar directamente con el DOM? (`useRef`)
- ¿Cómo persistir un valor entre re-renders? (`useRef`)
- ¿Cómo reaccionar o emitir cambio externo (side effect) al componente? (`useEffect`)
- Las reglas de los hooks
- ¿Cómo compartir estados entre diferentes componentes? (`useContext`)


## 👨🏻‍💻¿Quién soy?

👋 Soy [Matías Hernández](https://matiashernandez.dev), padre, desarrollador, podcaster, escritor e instructor.

Desde hace mucho tiempo (antes de que jQuery existiese) que escribo software y durante todos esos años el desarrollo web ha sido mi pasión. En los últimos 10 años he trabajado oficial y profesionalmente como Ingeniero de Software para diferentes proyectos. Durante esos años he recolectado muchas ideas, conceptos y conocimientos que intento destilar en diferentes formatos para ayudar a otros desarrolladores a mejorar su carrera.

Me encanta lo que hago y trato de traer la misma pasión a la creación de contenido por medio de cursos en [egghead.io](https://matiasfha.dev/egghead), artículos en [FreeCodeCamp](https://matiasfha.dev/fcces), [mi blog](https://matiashernandez.dev), [Cloudinary](https://mediajams.dev/author/matias-hernandez) y otras publicaciones, en mis podcasts [Café con Tech](https://www.cafecon.tech/) y [Control Remoto](https://www.controlremoto.io/) y en mis [cursos via email](https://microbytes.dev).

Puedes encontrarme en twitter como [@matiasfha](https://twitter.com/matiasfha)

## ⏰ Antes del workshop

¿Que necesitas saber para iniciar tu camino con React?

Primero, y por sobre todo, necesitas conocer fundamentos desarrollo web, Javascript moderno o avanzado y fundamentos de React. 
Durante tu trabajo con React verás mucho ideas y conceptos como:

Te invito a revisar tus conocimientos en esas áreas para que puedas sacar el máximo provecho a este workshop.

- Destructuring.
- Spread.
- Ternaries.
- [Closures.](https://www.freecodecamp.org/espanol/news/que-es-un-closure-en-javascript/)
- Parámetros por defecto.
- [Arrow functions.](https://escuelafrontend.com/articulos/arrow-functions)
- [Métodos de arreglos.](https://escuelafrontend.com/articulos/metodos-de-arreglos)
- Promesas, async/await.
- [¿Cómo crear una aplicación en React?](https://escuelafrontend.com/articulos/como-crear-una-aplicacion-en-react)
- [Componentes Controlados vs No Controlados](https://www.escuelafrontend.com/articulos/las-diferencias-entre-componentes-controlados-y-no-controlados-en-react)
- [¿Cómo funciona la prop key en React?](https://escuelafrontend.com/articulos/como-funciona-la-prop-key-en-react)

Puedes revisar mi newsletter [Microbytes](https://microbytes.dev) y unirte al curso Javascript para React donde encontrarás más material al respecto.

### 🛠 Requerimientos

Para aprovechar al máximo nuestro tiempo durante el workshop, por favor realiza los siguientes pasos antes de iniciar:

#### Requerimientos del sistema
- [git](https://git-scm.com/) v2.13 o superior
- [NodeJS](https://nodejs.org/) `12 || 14 || 15 || 16`
- [npm](https://www.npmjs.com/) v6 o superio

Estas herramientas deben ser parte de tu sistema, para verificar puedes ejecutar en la terminal

```shell
git --version
node --version
npm --version
```

#### Configuración

> Si gustas, puedes hacer un fork de este repositorio para poder ir "guardando" tu progreso.

- [ ] Clona este repositorio, en la terminal ejecuta:

```shell
git clone https://github.com/matiasfha/workshop-hooks.git
```

- [ ] Instala las dependencias

```shell
cd workshop-hooks
npm install
```
> Esto puede tardar unos minutos dependeniendo de tu conexión.

Si tienes algún error durante este proceso por favor [completa un issue](https://github.com/matiasfha/workshop-hooks/issues/new) en el reposotiorio. Escribe en el toda la información de los pasos realizados y el resultado del script que ejecutaste

#### Ejecutando los ejercicios

Para ejecutar los ejercicios, una vez que tienes los pasos anteriores listos, solo debes abrir la terminal y ejecutar

```shell
npm run dev
```

Esto te mostrará una lista de opciones con el nombre de la lección. Selecciona la que corresponda y luego visita `http://localhost:3000` en tu navegador.

> Para terminar el proceso y cambiar de lección solo presiona CTRL-C, esto detendrá el script y podras ejecutarlo nuevamente

- [ ] Ten listo tu editor de código favorito para resolver los ejercicios



### ❓ ¿Cómo ejecutar las lecciones?

Cada lección "vive" dentro de su propio directorio dentro de este monorepo, para ejecutar el ejercicio de una lección en particular sólo debes, desde la terminal, ejecutar `npm run dev`. Esto te mostrará una lista de las lecciones donde podrás seleccionar utilizando el teclado.




## 📝 Sobre el workshop

### Estructura de las lecciones

Cada concepto o contenido esta encapsulado en su propia lección y cada lección tiene su propio directorio con recursos, ejemplos de código y desafíos.

En cada directorio encontrarás un nuevo archivo Readme.md, en el encontrarás una descripción de lo que encontrarás en la lección e instrucciones para llevar a cabo los ejercicios, desafíos o cuestionarios.

Además encontrarás la configuración necesaria para ejecutar el proyecto que te permitirá resolver los ejercicios.

### Ejemplos de Ejercicios

Los ejercicios consisten en el desarrollo y solución de una problemática asociada al concepto que estás aprendiendo en la lección. Esto implica, que el código tendrá pistas y guías para que te mantengas enfocado en el tema correspondiente.

Para esto encontrás comentarios y emojis que te ayudarán en el camino.

- 💡: Indica el contenido del ejercicio.
- 🏋️‍♂️: Indica el ejercicio en particular.
- 🍬: Desafío o crédito extra.

### Listado de lecciones


## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
