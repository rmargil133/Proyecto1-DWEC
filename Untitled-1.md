---
marp: true
---

###### Rubén Mariscal Gil 2ºDAW

###### Proyecto 1 DWEC
![PortadaDocumentacion](portadaDocumentacion.png)

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

# Explorando los Fundamentos del Desarrollo Web en Entornos de Cliente

### 1. Modelos de Programación en Arquitectura Web.

La arquitectura web consiste en la planificación y diseño de los componentes técnicos, funcionales y visuales de un sitio web, antes de que sea diseñado, desarrollado e implementado.

 *- Investigación de los modelos cliente/servidor más comunes*

- **Single Page Application (SPA)**: consiste en una única página que recoge todo el contenido de forma que el usuario una vez accede a la aplicación, no necesita navegar a otra página web.                                                                           Ventajas de las SPA, podemos construir aplicaciones web con muchas interacciones, optimizar las SPA no supone gran impacto en el rendimiento.
- **Arquitectura de Aplicaciones Web Progresivas (PWA)**: se basa en una única página que proporciona capacidades offline para tu aplicación web. Al igual que las SPA, las PWA son fluidas y sin fisuras.                                                                              Ventajas de la arquitectura PWA, las aplicaciones se ejecutan con mucha fluidez y son compatibles entre plataformas, los desarrolladores pueden acceder al acceso sin conexión y a las API de los dispositivos.
- **Arquitectura de Renderizado del Lado Servidor (SSR)**: consiste en el renderizado de las páginas web desde un servidor backend después de que un usuario las solicite. Las aplicaciones SSR son muy populares entre los blogs y sitios web de comercio electrónico.Ventajas de la arquitectura SSR, la carga de la primera página es casi instantánea en la mayoría de los casos, puedes combinarla con un servicio cache para mejorar aun mas el rendimiento de tu aplicación.

 *- Identificación de ejmplos de aplicaciones que utilizan cada modelo*

- **Single Page Application**: algunos ejemplos de una SPA son Gmail, LinkedIn o Twitter y la carga entre vistas es extremadamente rápidas.

- **Aplicaciones Web Progresivas**: hay ejemplos de PWA como Google Maps, Uber, Instagram, Facebook, etc.

- **Renderizado del Lado Servidor**: ejemplos son principalmente blogs o sitios web de comercio electrónico debido a la gestión de enlaces.

### 2. Mecanismos de Ejecución de Código en un Navegador Web. Capacidades y Limitaciones de Ejecución. Compatibilidad con Navegadores Web.

 *- Estudio de como se ejecuta el código JavaScript en un navegador*

En Chrome podemos crear snippets que son fragmentos pequeños de códigos y nos permiten ejecutar código JavaScript en nuestro navegador.

Para crear un snippet en Chrome podemos usar la consola del navegado dentro de la sección Sources / Snippets / New Snippet, elegimos el nombre que queramos y escribimos en la consola console.log (“Hello World”);

Poir último presionamos CTRL+Enter o CMD+Enter para ejecutar el programa y ver la salida desde la consola.

 *- Evaluación de las difrencias de compatibilidad entre navegadores*

De entre todos los navegadores que existen a día de hoy vemos cuales son los mas usados por los usuarios en pleno 2023 teniendo en cuenta el apartado web, es importante una la compatibilidad de los mismos ya que no en todos los navegadores nuestra web se ve de la misma manera.

| 2023      | Chrome | Safari | Edge | Firefox | Opera |
| --------- | -----: | -----: | ---: | ------: | ----: |     
| Agosto    |   66,1%|     13%|  4,6%|     3,9%|   1,1%|
| Julio     |   72,8%|   13,5%|  2,7%|     2,5%|   1,2%|
| Junio     |     76%|     11%|  2,6%|     2,5%|     1%|
| Mayo      |   75,7%|   10,8%|  3,3%|     2,6%|     1%|

