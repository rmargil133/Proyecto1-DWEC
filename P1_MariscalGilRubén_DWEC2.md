---
marp: true
---
![PortadaPresentacion](portadaPresentacion.png)

# - *ÍNDICE* -

- ####  1. Modelos de Programación en Arquitectura Web.
    - ***-** Investigación de los modelos cliente/servidor más comunes*
    - ***-** Identificación de ejemplos de aplicaciones web que utilizan cada modelo.*

- #### 2. Mecanismos de Ejecución de Código en un Navegador Web. Capacidades y Limitaciones de Ejecución. Compatibilidad con Navegadores Web.
    - ***-** Estudio de cómo se ejecuta el código JavaScript en un navegador*
    - ***-** Evaluación de las diferencias de compatibilidad entre navegadores.*
    - ***-** Resolución de problemas de compatibilidad en una aplicación web.*

- #### 3. Lenguajes de Programación en Entorno Cliente.
    - ***-** Investigación de lenguajes como JavaScript, TypeScript, y otros.*
    - ***-** Comparación de sus características y aplicaciones.*

- ### 4. Características de los Lenguajes de Script. Ventajas y Desventajas.
    - ***-** Análisis de las ventajas y desventajas de la programación en lenguajes de script sobre la programación tradicional.*

- ### 5. Tecnologías y Lenguajes Asociados. Integración del Código con las Etiquetas HTML.
    - ***-** Exploración de tecnologías como CSS y HTML5.*
    - ***-** Creación de una pequeña aplicación web integrando código JavaScript de diferentes maneras.*

- ### 6. Herramientas de Programación.
    - ***-** Uso de herramientas como Visual Studio Code, Chrome DevTools, etc.*

---
### 1. Modelos de Programación en Arquitectura Web.
 *- Investigación de los modelos cliente/servidor más comunes*

- **Single Page Application (SPA)**:  es una aplicación web que carga todo su contenido en una sola página sin recargar la página completa al navegar.

<img src="SPA.png" width="220"/>

- **Arquitectura de Aplicaciones Web Progresivas (PWA)**: es una única página que proporciona capacidades offline para tu aplicación web. 

<img src="PWA.png" width="280"/>

- **Arquitectura de Renderizado del Lado Servidor (SSR)**:  renderizado de las páginas web desde un servidor backend después de que un usuario las solicite.

<img src="SSR.png" width="400"/>

 *- Identificación de ejmplos de aplicaciones que utilizan cada modelo*

- **Single Page Application**: algunos ejemplos de una SPA son Gmail, LinkedIn o Twitter.

<img src="Eje SPA.png" width="220"/>

- **Aplicaciones Web Progresivas**: hay ejemplos de PWA como Google Maps, Uber, Instagram, Facebook, etc.

<img src="Eje PWA.png" width="220"/>

- **Renderizado del Lado Servidor**: ejemplos son principalmente blogs o sitios web de comercio electrónico.

<img src="Eje SSR.png" width="220"/>

---
### 2. Mecanismos de Ejecución de Código en un Navegador Web. Capacidades y Limitaciones de Ejecución. Compatibilidad con Navegadores Web.

 *- Estudio de como se ejecuta el código JavaScript en un navegador*

<img src="js-chrome.png"/>

En Chrome podemos crear snippets.
Para crear un snippet en Chrome podemos usar la consola del navegador dentro de la sección Sources / Snippets / New Snippet, elegimos el nombre que queramos y escribimos en la consola console.log (“Hello World”);
Por último presionamos CTRL+Enter o CMD+Enter para ejecutar el programa y ver la salida desde la consola.

 *- Evaluación de las difrencias de compatibilidad entre navegadores*

Para conseguir que nuestra página web se vea correctamente en el navegador influye la compatibiliad entre los navegadores, por eso vemos una tabla con los mas usados en 2023.

| 2023      | Chrome | Safari | Edge | Firefox | Opera |
| --------- | -----: | -----: | ---: | ------: | ----: |     
| Agosto    |   66,1%|     13%|  4,6%|     3,9%|   1,1%|
| Julio     |   72,8%|   13,5%|  2,7%|     2,5%|   1,2%|
| Junio     |     76%|     11%|  2,6%|     2,5%|     1%|
| Mayo      |   75,7%|   10,8%|  3,3%|     2,6%|     1%|

Estos datos son obtenidos gracias a https://www.w3counter.com/globalstats.php

*-Resolución de problemas de compatibilidad en una aplicación web.*
- Validar los archivos CSS y HTML ya que pueden ser un gran problema para los desarrolladores. 
- No incluir la línea más básica del HTML (Doctype)
- Investigar si la función de JavaScripr es compatible con las versiones de los navegadores más antiguos y puedes hacer uso para ello de la herramienta Caniuse.

<img src="html-css-js.png" width="250"/>

---
### 3. Lenguajes de Programación en Entonrno Cliente.
*- Investigación de lenguajes como JavaScript, Typescript y otros*

- **JavaScript**: es un lenguaje de programación ligero, interpretado o compilado justo-a-tiempo con funciones de primera clase y su usa para crear interactividad dinámica en los sitios web.

- **HTML**: es el lenguaje con el que se define el contenido de las páginas web. 

- **CSS**: es un lenguaje que maneja el diseño y presentación de las páginas web, es decir, como lucen cuando el usuario las visita. 

- **TypeScript**: es un lenguaje de programación fuertemente tipado que está basado en JavaScript y le brinda mejores herramientas a cualquier escala. 

<img src="lenguajes-programacion.png" width="250"/>

*-Comparación de sus caracteristicas y aplicaciones*
*Caracteristicas de JavaScript y aplicaciones.*

- Es un lenguaje interpretado.
- Es orientado a objetos y utiliza prototipos para poder definir los objetos. 
- Es un lenguaje muy sencillo.
- Al ser un lenguaje interpretado le permite tener múltiples interpretes en distintos navegadores.

Se usa en el Desarrollo de aplicaciones Web, Desarrollo web, desarrollo de juegos en línea, etc. 

*Caracteristicas de HTML y aplicaciones.*

- No es necesario estar en línea para que el lenguaje HTML funcione correctamente.
- Es muy fácil de usar y entender.
- Es reconocido y admitido por cualquier tipo de explorador web.
- Es multiplataforma, por lo que se puede acceder desde cualquier lugar y dispositivo.

Se usa para la estructuración de contenido de una página web.


*Caracteristicas de CSS y aplicaciones.*

- Es utilizable en todos los navegadores y plataforma.
- Optimiza el funcionamiento de las páginas web.
- Permite personalizar totalmente la apariencia de las páginas. 

CSS se utiliza para controlar el diseño y la maquetación de una página web.


*Caracteristicas de Typescript y aplicaciones.*

- Admite todos los elementos de JavaScript.
- Se fundamenta en JavaScript. 
- Se puede ejecutar en cualquier navegador, dispositivo o sistema operativo.
- Tiene todas las herramientas de un lenguaje de programación orientado a objetos.

Se utiliza principalmente para el desarrollo de aplicaciones web y proyectos de software en general.

---
### 4. Caracteristicas de los Lenguajes de Script. Ventajas y Desventajas.
*-Análisis de las ventajas y desventajas de la programación en lenguajes de script sobre la programación tradicional.*

*Ventajas de la programación en lenguajes de script:*

- **Fácil integración.** 
- **Rápido Desarrollo.** 
- **Facilidad de Aprendizaje.**
- **Amplia Comunidad y Soporte.** 

*Desventajas de la programación en lenguajes de script:*

- **Dependencias Externas.** 
- **Rendimiento.** 
- **Mayor Uso de Recursos.** 
- **Tamaño de Ejecutables.** 

---
### 5. Tecnologías y Lenguajes Asociados. Integración del Código con las Etiquetas HTML.

*-Exploración de tecnologías como CSS y HTML5.*

HTML5 es un lenguaje de marcas que permite estructura y presentar contenido en la web.

- **CSS.**

- **JavaScript.**

- **SVG.**

- **Canvas.**

<img src="lenguajes-tecnologias.png" width="215"/>

Estas son algunas de las tecnologías complementarias de HTML5 que nos permiten poder llevar nuestras páginas web a un nivel superior.

*-Creación de una pequeña aplicación web integrando código JavaScript de diferentes maneras.*

- Aplicación integrando JavaScript de 2 formas distintas.

JavaScript dentro del HTML.
~~~
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>App Saludo</title>
</head>
<body>
    <h1>App Saludo</h1>
    <input type="text" id="name" placeholder="Ingresa tu nombre">
    <button onclick="saludar()">Saludar</button>
    <p id="mensaje"></p>
    <script>
        function saludar() {
            const name = document.getElementById('name').value;
            document.getElementById('mensaje').textContent = `¡Hola, ${name}!`;
        }
    </script>
</body>
</html>
~~~

JavaScript en un archivo externo.
~~~
<!DOCTYPE html>
<html>
<head>
    <title>App Saludo</title>
</head>
<body>
    <h1>App Saludo</h1>
    <input type="text" id="name" placeholder="Ingresa tu nombre">
    <button onclick="saludar()">Saludar</button>
    <p id="mensaje"></p>
    <script src="script.js"></script>
</body>
</html>
~~~

---
### 6. Herramientas de Programación. 
*- Uso de herramientas como Visual Studio Code, Chrome DevTools, etc.*

- **Visual Studio Code.**

<img src="vscode.png" width="130"/>

*- Algunas características claves de Visual Studio Code*

- **Soporte a los mejores lenguajes de programación.**
- **Tiene una amplia biblioteca de extensiones.** 
- **Resaltado de sintaxis.**

- **Chrome Developer Tools.**

<img src="devtools.jpeg" width="140"/>

*- Algunas características claves de Chrome Developer Tools*

- **Anulaciones locales.** 
- **Características del diseño web.**
- **Herramientas de diagnóstico.** * Ve el uso de memoria de una página web con el Administrador de tareas de Chrome.

- **GitHub.**

<img src="GitHub.png" width="140"/>

*- Algunas características claves de GitHub*

- **Solicitudes de extracción y revisión de código.** 
- **Amplias funciones de seguridad.** 
- **Automatización.** 

---
# - Bibliografía -
