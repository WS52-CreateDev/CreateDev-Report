
## 5.1. Software Configuration Management. 

A continuación, se presentará un repositorio central y organizado que servirá como guía para el desarrollo enfocado y consistente de nuestra solución..

### 5.1.1. Software Development Environment Configuration.

En esta sección se incluye los links de las aplicaciones, productos de software realizadas durante el ciclo del proyecto en los programas que se utilizaron. 
Para ello se clasificará en las siguientes secciones:
<br><br>
<strong>Requirements Management</strong><br>
Es el proceso de garantizar que una organización documente verifique y satisfaga las necesidades, expectativas de sus clientes con las partes interesadas internas o externas.<br><br>
<ul>
<li><strong>Pivotal Tracker</strong>: Esta herramienta se define como una plataforma en la que se realiza la gestión de user stories, agrupándoles en epics y clasificando su presencia en el programa, por puntaje. Se usó porque permite que cada miembro del equipo comparte la misma vista en tiempo real de lo que está sucediendo con cada proyecto, ya sea aportando con diferentes secciones o corrigiendo el flujo del proyecto. https://www.pivotaltracker.com/n/projects/2603049
</li>
</ul>

<strong>Product UX/UI Design</strong>

<ul>
<li><strong>Uxpressia:</strong> es una herramienta en línea para el mapeo de la trayectoria del cliente que crea mapas de impacto y personas. Sus herramientas nos permitieron establecer las bases del modelado de User Persona, Empathy Map y Journey Map.<br>
https://uxpressia.com/

</li>
<li><strong>Figma:</strong> es una pizarra digital colaborativa en línea, que puede ser usada para la investigación, la ideación, la creación de lluvias de ideas, mapas mentales y una variedad de otras actividades colaborativas.<br>https://www.figma.com/design/ 
</li>
<li><strong>Structurizr:</strong> es una herramienta de diseño que soporta el modelo C4, para visualizar la arquitectura de software de nuestra solución. <br>https://structurizr.com/  
</li>
<li><strong>Lucid Chart:</strong> es una herramienta de diagramación basada en la web, que permite a los usuarios colaborar y trabajar juntos en tiempo real, creando diseños UML, mapas mentales, prototipos de software y muchos otros tipos de diagrama. <br>https://lucid.app/documents#/dashboard 
</li>
<li><strong>MIRO:</strong> es una pizarra digital colaborativa en línea, que puede ser usada para la investigación, la ideación, la creación de lluvias de ideas, mapas mentales y una variedad de otras actividades colaborativas. <br>https://miro.com/app/dashboard/ 
</li>
</ul>
<br>
<strong>Software Development</strong><br>
Es una estructura aplicada al desarrollo de un producto de software. Se utiliza para el establecimiento de un proceso para el desarrollo de software, cada uno de los cuales describe un enfoque diferente para diferentes actividades que tienen lugar durante el proceso.<br>
<ul>

<li><strong>Github:</strong> Es un repositorio comunitario cuya función es almacenar los avances de un proyecto elaborado por un grupo de personas. <br>
https://github.com/TechOps-upc
</li>

<li>
<strong>Web Storm:</strong> Es un entorno de JetBrains, empresa desarrolladora de Software, orientado en el desarrollo web en JavaScript. Este nos ofrece facilidad en probar nuestro entorno web en navegadores como Google. Para el proyecto se implementará la ayuda de los lenguajes HTML, CSS , JavaScript y TypeScript.<br>
https://www.jetbrains.com/webstorm/promo/?source=google&medium=cpc&campaign=9641686239&term=webstorm&gclid=CjwKCAjwv-GUBhAzEiwASUMm4ncU-aP3HPxUWVYTPMthApgSMowOvvfEAoJMFvwf1O_gQdv0HtWOrhoCdacQAvD_BwE
</li>

<li>
<strong>Visual Studio Code:</strong> Es un editor potente que brinda extensiones que nos permiten personalizar y agregar funcionalidades para que la función del desarrollador sea más eficiente. Asimismo, se empleará para poder construir el backend de nuestro web Applications.<br>
https://code.visualstudio.com/ 
</li>

<li>
<strong>HTML:</strong> Es un lenguaje que sirve como desarrollador de plataformas web que trabaja con hipertextos, que enlace a otros documentos. Este lenguaje ofrece herramientas para el diseño del sitio web. Asimismo, la disponibilidad de trabajar HTML junto con CSS y JavaScript. Este lenguaje será utilizado en el presente proyecto para implementar la documentación de la página web. <br>https://www.jetbrains.com/help/webstorm/editing-html-files.html 
</li>

<li>
<strong>CSS:</strong> Es un lenguaje de diseño para el entorno web. Permite elaborar el interfaz de usuario diseñada anteriormente, agregando colores, tamaños entre otros elementos. Además, se puede diseñar un estilo en CSS y compartirlo en el web elaborado en HTML. Este lenguaje se utilizará para la implementación del diseño de nuestra plataforma web.<br>
https://www.jetbrains.com/help/webstorm/style-sheets.html#ws_css_completion 
</li>
</ul>
<strong>Software Deployment</strong>
<ul>
<li>
<strong>Github pages:</strong>Servicio de Github que nos permitió alojar nuestra lading page y nos permitirá alojar nuestro web applications.<br>
https://pages.github.com/<br> 
https://github.com/ 
</li>
</ul>

### 5.1.2. Source Code Management.

#### Gestión de Código Fuente con GitFlow

La Gestión de Código Fuente (SCM, por sus siglas en inglés) es un aspecto crucial del desarrollo de proyectos, que realiza un seguimiento de las modificaciones realizadas por el equipo a lo largo de la vida útil del proyecto en repositorios de código fuente. Sirve como un sistema de control de versiones, que permite hacer un seguimiento de los cambios realizados por cada miembro del equipo o desarrollador en el proyecto. Para el control de versiones, utilizaremos GitHub.

- URL de la Organización: [Create-upc](https://github.com/WS52-CreateDev)
- URL del Repositorio de la Página de Aterrizaje: [Repositorio de la Página de Aterrizaje](https://ws52-createdev.github.io/Maki-Landing-page/)

#### GitFlow

GitFlow es un flujo de trabajo de desarrollo basado en ramas que ha ganado una gran relevancia en los últimos años y es considerado esencial por muchos desarrolladores. Introducido y popularizado por Vincent Driessen, su propósito principal es facilitar la gestión y organización de diferentes versiones de código, permitiendo la creación ordenada de nuevas características y correcciones urgentes.

#### Ramas Principales

- `main`: La rama principal sirve como la rama primaria de la cual derivan todas las demás ramas. Contiene la última versión junto con versiones anteriores creadas por los desarrolladores, sirviendo como el historial oficial de versiones.
- `develop`: Esta rama puede crearse a partir de la rama `main` y contiene todas las características estables. Permite que el equipo integre características.

#### Ramas de Soporte

A diferencia de las ramas principales, estas ramas tienen una vida útil limitada y se eliminan al fusionarse con sus ramas principales.

- `Feature`:
  - Ramificada desde: `develop`
  - Fusionada nuevamente en: `develop`
  - Se utiliza para desarrollar nuevas características que se integrarán en la próxima versión. Existe solo durante el proceso de desarrollo y se fusiona nuevamente en `develop` al completarse.
  
- `Release`:
  - Ramificada desde: `develop`
  - Fusionada nuevamente en: `develop` / `main`
  - Se utiliza para preparar un nuevo lanzamiento de producción. Permite corregir errores menores que ocurrieron durante el desarrollo y preparar metadatos para el lanzamiento. Este proceso permite que `develop` reciba nuevas características para la próxima versión, ya que se genera cuando se acerca una fecha de lanzamiento específica.

#### Principales motivos para usar Gitflow

- Ideal para nuestro proyecto, que se basa en lanzamientos dentro de un sprint específico.
- Ofrece un enfoque centralizado como Subversion (SVN) y un enfoque descentralizado, permitiendo que el equipo trabaje de forma individual. Esto es beneficioso ya que no todos tienen el mismo horario, pero todos deben mantener actualizaciones en el repositorio central en GitHub.



### 5.1.3. Source Code Style Guide & Conventions.
Para el desarrollo de la parte de HTML y CSS se utlizara Google HTML/Css Style Guide, ya que contiene las convenciones que se deben tener en cuenta al trabajar cpnn dichas tecnologías. Para guirarnos de las buenas practicas accederemos mediante este enlace: https://google.github.io/styleguide/htmlcssguide.html. Entre algunas convenciones podemos mencionar:

### HTML y CSS:


- **Declaración del tipo de documento:** Siempre declarar el tipo de documento con `<!DOCTYPE html>`.
- **Nombres de elementos en minúsculas:** Utilizar siempre letras en minúsculas para los nombres de los elementos HTML como `<p>`, `<h1>`, `<section>`, entre otros.
- **Cierre de elementos HTML:** Cerrar siempre los elementos HTML, por ejemplo, `<p></p>`.
- **Comillas en atributos:** Siempre poner entre comillas los atributos dentro de un elemento HTML, como `<p class="name"></p>`.
- **Atributos para imágenes:** Especificar `alt`, `width`, y `height` para imágenes.
- **Espaciado y formato estandarizado:** Mantener un espaciado y un formato de código consistentes.
- **Evitar líneas de código extensas:** Dividir el código en líneas más cortas para facilitar la lectura.
- **Uso de etiquetas meta:** Utilizar meta tags al inicio y asegurarse de incluir el elemento `<title></title>`.


  ### JavaScript:
Para el lenguaje JavaScript, se seguirá la guía de estilo proporcionada por Google en el repositorio de GitHub  [ https://google.github.io/styleguide/jsguide.html ]. Algunas de las convenciones incluyen:

-	Nomenclatura en camelCase: Nombrar variables y funciones utilizando camelCase, por ejemplo, numberArray.
-	Comillas simples: Utilizar comillas simples para strings, como const message = 'This is a string';.
-	Uso de punto y coma: Agregar un punto y coma al final de cada sentencia.
-	Uso de let o const: Evitar declarar variables con var y en su lugar utilizar let o const.
-	Espaciado y formato de código: Mantener un formato de código claro y espaciado adecuado.
-	Manejo de errores: Implementar manejo de errores y excepciones de forma apropiada.
-	Comentarios y documentación: Utilizar comentarios y documentación de código según sea necesario.
### Gherkin (Archivos .feature):

Para el lenguaje Gherkin, se seguirán las convenciones mencionadas en "Make your Gherkin Specifications More Readable" para escribir especificaciones claras y legibles. Se puede conocer más sobre la forma de escribir en el lenguaje de Gerkhin mediante el siguiente enlace: https://specflow.org/gherkin/gherkin-conventions-for-readable-specifications/ .  A continuación, algunas de las convenciones incluyen:

-	Lenguaje simple: Escribir especificaciones en un lenguaje simple y fácil de entender.
-	Palabras clave Given/When/Then/And: Utilizar las palabras clave Given, When, Then, y And para los pasos del escenario.
-	Verbos finitos: Usar verbos finitos para describir acciones en los escenarios.
-	Evitar redundancias: Evitar redundancias en la descripción de los pasos en el escenario.
-	Formato consistente: Mantener un formato y estilo consistentes en toda la especificación.

### Vue.js:
Para el desarrollo con Vue JS se tiene como referencia las convenciones ya definidas por el mismo equipo de Vue con el objetivo de mantener un formato entendible y que ayude en el mantenimiento del sistema. Se puede visualizar las convenciones en el siguiente enlace: https://v2.vuejs.org/v2/style-guide/?redirect=true . a continuación se presentan algunas convenciones en Vue JS:

-	Nombres de componentes deben tener múltiples palabras.
-	El componente data debe ser una función que retorne valores.
-	Detalles de propiedades deben estar definidos.
-	Usar key con v-for.
-	Evitar mezclar v-if con v-for en un mismo scope.


### C#:
Para el uso de C# Microsoft provee una quia de estilos bastante completa cual nos permitirá aplicar estándares aplicados por Microsoft. Se puede conocer mas sobre esto en el siguiente link: https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/coding-style/coding-conventions  . entre algunas convenciones podemos mencionar:
-	Se utiliza PascalCase para nombrar clases, estructuras o registros.
-	Los parámetros se nombran en camelCase.
-	Los comentarios se escriben en líneas separadas y se evita el exceso de comentarios.
-	Se respeta el espaciado después de comas y operadores.
-	Las llaves deben ir en una línea nueva al declarar una clase, estructura, entre otros

### .NET Framework:
Finalmente, para .NET Framework también Microsoft provee una guía de estilos bastante completa as cuales abarcan varias nociones involucradas en el uso de este framework. Se puede acceder a la guía desde el siguiente enlace: https://github.com/dotnet/aspnetcore/wiki/Engineering-guidelines#coding-guidelines . A continuación, se mencionan algunas convenciones:

-	Se siguen las guías de estilo de Microsoft para .NET Framework.
-	Los archivos deben incluir los comentarios de licencia de .NET.
-	Se evita el uso de this a menos que sea necesario.
-	Se especifica la visibilidad de los miembros (por ejemplo, private).
-	Las llaves se colocan en una nueva línea separada del código.
-	Se emplea espaciado después de comas y operadores.




### 5.1.4. Software Deployment Configuration.

El despliegue del software implica la preparación y configuración del entorno de producción. Para nuestra landing page, utilizamos GitHub Pages para publicarla. Este servicio nos permite alojar nuestro sitio web estático directamente desde nuestro repositorio de GitHub, simplificando el proceso de despliegue y asegurando una implementación rápida y eficiente sin la necesidad de un backend complejo.

## 5.2. Landing Page, Services & Applications Implementation.

### 5.2.1. Sprint 1

En esta sección registramos y explicamos nuestro avance de trabajo colaborativo para el Sprint 1. 

#### 5.2.1.1. Sprint Planning 1.

<table>
        <thead>
            <tr>
                <th>Sprint #</th>
                <th>Sprint 1</th>
            </tr>
        </thead>
        <tbody>
                <th><b>Sprint Planning Background</th>
            <tr>
                <th>Date</th>
                <td> 2023-04-09 </td>
            </tr>
            <tr>
                <th>Time</th>
                <td> 10:00 PM </td>
            </tr>
            <tr>
                <th>Location</th>
                <td> Reunión virtual en el servidor de Discord del Startup</td>
            </tr>  
            <tr>
                <th>Prepared By</th>
                <td> Alejandra Díaz, Antonella Gonzales </td>
            </tr> 
            <tr>
                <th>Attendees (to planning meeting)</th>
                <td> María Alejandra Díaz Villacrez, Antonella Frida Gonzales Gomez, Carlo Patricio Ramirez Escalante, Braulio Rodrigo Torrejon Navarro, Jair Andreé Coraje Bayona, Louis Piero Alfaro Coveñas </td>
            </tr>
            <tr>
                <th>Sprint 1 - 1 Review Summary</th>
                <td> Se realizaron los commits y push de los index.html en las ramas "feature/hero, feature/about-the-app, feature/about-us, feature/benefits, feature/contact-us y feature/footer" del repositorio del Landing Page. Quedó pendiente hacer un merge con la rama develop. </td>
            </tr>
            <tr>
                <th>Sprint 1 - 1 Retrospective Summary</th>
                <td> En retrospectiva, los miembros del equipo opinan que se debe seguir una plantilla al elaborar los index de los features, para evitar conflictos a la hora de hacer merge con la rama develop. Sin embargo, como equipo tuvimos la oportunidad de aprender como realizar merges ya que nadie habia realizado esta actividad previamente. </td>
            </tr>
                <th><b>Sprint Goal & User Stories</th>
            <tr>
                <th>Sprint 1 Goal</th>
                <td> Los goals definidos son: Implementación del landing page index y style, además de hacer un merge a la rama develop. 
                La métrica para medir el cumplimiento de los goals será: (Número de elementos del Sprint Backlog completados)/ (Número todal de elementos del Sprint Backlog planificados) x 100% </td>
            </tr>
            <tr>
                <th>Sprint 1 Velocity</th>
                <td> Los Story Points que el equipo acepto para este Sprint fueron alrededor de 25 puntos</td>
            </tr>
            <tr>
                <th>Sum of Story Points</th>
                <td> 
                    HU-17: 5 puntos </br>
                    HU-18: 3 puntos </br>
                    HU-19: 3 puntos </br>
                    HU-20: 5 puntos </br>
                    HU-21: 5 puntos </br>
                    Suma total: 21 Story points
                </td>
            </tr>
        </tbody>
    </table>

#### 5.2.1.2. Sprint Backlog 1.

El objetivo principal del presente sprint es culminar la implementación del Landing Page de nuestra aplicación. Durante el Sprint 1, nos enfocamos en la implementación inicial de las secciones clave que conforman la estructura básica del Landing Page. Específicamente, hemos trabajado en las secciones de "Hero", "About the App", "Benefits", "About Us", "Contact Us", y "Footer", sentando así las bases para una experiencia de usuario completa y coherente. Esta fase inicial del desarrollo nos ha permitido establecer una sólida infraestructura visual y funcional que respalda los objetivos y valores de nuestra aplicación.

Link del Trello: https://trello.com/invite/b/kmauia0S/ATTIcf86396df6e9b14f5ba095c999d949cf751C76A4/sprint-1

<table>
    <thead>
        <tr>
            <th>Sprint #</th>
            <th>Sprint 1</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th>User Story</th>
            <th>Work Item / Task</th>
        </tr>
        <tr>
            <td>Id</td>
            <td>Title</td>
            <td>Id</td>
            <td>Title</td>
            <td>Description</td>
            <td>Estimation (Hours)</td>
            <td>Assigned To</td>
            <td>Status</td>
        </tr>
        <tr>
            <td>HU-01</td>
            <td>Visualización del logo de Maki</td>
            <td>WL-01</td>
            <td>Implementación de imagen de muestra.</td>
            <td>Implementar la visualización del logo en la sección "Hero"</td>
            <td>1</td>
            <td>Implementación de sección "Hero"</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>HU-02</td>
            <td>Implementación de los textos de redirección hacia cada sección del Landing Page</td>
            <td>WL-02</td>
            <td>Implementación de textos directorios</td>
            <td>Implementar textos directorios en la sección "Hero"</td>
            <td>0.5</td>
            <td>Implementación de sección "Hero"</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>HU-03</td>
            <td>Implementación de los botones de Contacto</td>
            <td>WL-03</td>
            <td>Implementos de botones</td>
            <td>Implementar los botones en la sección "Hero"</td>
            <td>0.5</td>
            <td>Implementación de sección "Hero"</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>HU-04</td>
            <td>Implementación de los textos incentivos para el usuario</td>
            <td>WL-04</td>
            <td>Implementos del texto principal</td>
            <td>Implementos del texto principal en la sección “About the app"</td>
            <td>0.5</td>
            <td>Implementación de sección “About the app"</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>HU-05</td>
            <td>Implementación de los botones Contacto</td>
            <td>WL-05</td>
            <td>Implemento de botón</td>
            <td>Implementar botón en la sección "About the app"</td>
            <td>0.5</td>
            <td>Implementación de sección "About the app"</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>HU-06</td>
            <td>Implementación de la visualización de los productos</td>
            <td>WL-06</td>
            <td>Implementos de la visualización de los productos</td>
            <td>Implementar la visualización de los productos en la seccion “Benefits”</td>
            <td>0.5</td>
            <td>Implementación de sección “Benefits"</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>HU-07</td>
            <td>Implementación de la visualización de nuestro equipo</td>
            <td>WL-07</td>
            <td>Implementos de la visualización del equipo</td>
            <td>Implementos de la visualización en la sección "About Us"</td>
            <td>1</td>
            <td>Implementación de sección "About Us"</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>HU-08</td>
            <td>Implementación de los textos de información de nuestro contacto</td>
            <td>WL-08</td>
            <td>Implementos de textos informativos</td>
            <td>Implementos de textos informativos en la sección "Contact Us"</td>
            <td>0.4</td>
            <td>Implementación de sección "Contact Us"</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>HU-09</td>
            <td>Implementación de los botones Contacto</td>
            <td>WL-09</td>
            <td>Implemento de botón</td>
            <td>Implementar botón en la sección "Contact us"</td>
            <td>0.5</td>
            <td>Implementación de sección "Contact us"</td>
            <td>Done</td>
        </tr>
        <tr>
            <td>HU-10</td>
            <td>Implementación de los textos de redirección hacia cada sección del Landing Page</td>
            <td>WL-10</td>
            <td>Implementación de textos directorios</td>
            <td>Implementar textos directorios en la sección "Footer"</td>
            <td>0.5</td>
            <td>Implementación de sección "Footer"</td>
            <td>Done</td>
        </tr>
    </tbody>
</table>



#### 5.2.1.3. Development Evidence for Sprint Review.

|Repository|Branch|Commit id|Commit Mesage|Commit Mesage Body|Commited on (Date)|
| :- | :- | :- | :- | :- | :- |
|Maki-Landing-page|feature/about-the-app(then develop)|73437e3|feat(about-the-app): updated about the app||09/04/2024|
|Maki-Landing-page|feature/about-us(then develop)|ebb0281|feat(about-us):created\_about-us||09/04/2024|
|Maki-Landing-page|feature/benefits(then develop)|328074b|feat(benefits): added benefits|-|09/04/2024|
|Maki-Landing-page|feature/contact-us(then develop)|ab886b8|feat(contact-us): update contact us|-|09/04/2024|
|Maki-Landing-page|feature/hero(then develop)|6e7663c|feat(hero): updated hero|-|09/04/2024|
|Maki-Landing-page|feature/footer(then develop)|4100568|feat(Footer):Add footer|-|09/04/2024|


#### 5.2.1.4. Testing Suite Evidence for Sprint Review.

Para la entrega del Sprint 1, se tuvo pensado alcanzar el desarrollo completo del despliegue del Landing page. En esta sección presentamos la implementación del Landing page, tratando de alcanzar el diseño original que se realizó en Figma, de tal modo que el usuario tenga una buena experiencia de usuario.

|Repository|Branch	Commit Id|Commit Message|Commit Message Body|Commited on (Date)|
| :- | :- | :- | :- | :- |
|Maki-Landing-page|8f6bf8c7a74f38647604b7d8564d77ac508b395c|Added initial landing page|Added initial landing page|09/04/24|
|Maki-Landing-page|27fe7eb6d6cfcb8bed5809c9a611eb298a79a7dc|add the toolbar and home page|add the toolbar and home page|09/04/24|
|Maki-Landing-page|c639147ee077cb4aa1ad82b69ccc6421f037ccbc|Update index.html|deleted the beginning of the landing page|09/04/24|
|Maki-Landing-page|6e7663cb0d650b8617f6eeed0e242d5a3b33a87c|feat(hero): updated hero|added hero section|09/04/24|
|Maki-Landing-page|5663ade0cd2408e889827baa50872ca8eebb66e9|feat(about-us): updated about-us|added about-us section|09/04/24|
|Maki-Landing-page|328074b22aec84a51b611af5bfd383f70ca6c14d|feat(benefits): added benefits|feat(benefits): added benefits|09/04/24|
|Maki-Landing-page|ebb02813e6f5fc16136a3d011712c72f78313565|feat(about-us):created\_about-us|feat(about-us):created\_about-us|09/04/24|
|Maki-Landing-page|73437e3a94b49c96f7fb15efe4660e861b37290c|feat(about-the-app): updated about the app|added about the app section|09/04/24|
|Maki-Landing-page|ab886b82e21ff538f6482e6701a0b39f29ed355c|feat(contact-us): update contact us|feat(contact-us): update contact us|09/04/24|
|Maki-Landing-page|4100568fe5221e435dd58e9de91bb0375d8bae76|Feat(Footer):Add footer|Feat(Footer):Add footer|09/04/24|
|Maki-Landing-page|b2dd78b1ce9fcf5c99681e0124acf3a89d851e4a|feat(develop): added js file folder|feat(develop): added js file folder|09/04/24|
|Maki-Landing-page|8f06dfd09dc37f71a320cac8cf45839d9625c556|feat(develop): added images folder|feat(develop): added images folder|09/04/24|
|Maki-Landing-page|16cfa2de1768d89ea7f9ad4a706455ed7f826a45|feat(develop): added css file folder|feat(develop): added css file folder|09/04/24|
|Maki-Landing-page|947274a5471975f4bd5e94a9943cf95825bfb046|<p>Merge pull request #1 from WS52-CreateDev/feature/hero</p><p></p>|<p>Merge pull request #1 from WS52-CreateDev/feature/hero</p><p></p><p></p>|09/04/24|
|Maki-Landing-page|0c0570f4054939a2a73613eb7fef540976950119|fix(about-us): fixed about us|fix(about-us): fixed about us|09/04/24|
|Maki-Landing-page|2f45bcf4e6d3c6ba88591dd868d848d052f50c65|fix(about-the-app): fixed about the app|fix(about-the-app): fixed about the app|09/04/24|
|Maki-Landing-page|afe033cee84ee0834a18b3e4da3480e588174727|fix(footer): fixed footer|fix(footer): fixed footer|09/04/24|
|Maki-Landing-page|8ae864a8dd2f69c923075f1d37b73a24c940b527|<p>Merge pull request #3 from WS52-CreateDev/feature/footer</p><p></p>|<p>Feature/footer</p><p></p><p></p><p></p>|09/04/24|
|Maki-Landing-page|34c6bc7f7c61391461edaee1df3104844295fc1b|fix(benefits): fixed benefits|fix(benefits): fixed benefits|09/04/24|
|Maki-Landing-page|e45e2ea20d7846e93b44e6427cbac7e32698031a|fix(contact-us): fixed contact us|fix(contact-us): fixed contact us|09/04/24|
|Maki-Landing-page|7a5f233894f9974f930e9557fe63cc46a78cfc1a|<p>Merge pull request #4 from WS52-CreateDev/feature/contact-us</p><p></p>|Feature/contact us|09/04/24|
|Maki-Landing-page|6e134e7aca8dc1d85358a025aad685ff82933ec8|<p>fix(contact-us): fixed contact us</p><p></p>|<p>fix(contact-us): fixed contact us</p><p></p><p></p>|09/04/24|
|Maki-Landing-page|579be40925e4b398375897f2ce0a16e8f4a5ca5f|fix(contact-us): fixed contact us|fix(contact-us): fixed contact us|09/04/24|
|Maki-Landing-page|071761200d77ecf3807011920888e8ef15c68b75|feat(contact-us): update contact-us|feat(contact-us): update contact-us|09/04/24|
|Maki-Landing-page|f92b11101f9e234fc7383919ac13868c3366b87d|fix(contact-us): fixed|fix(contact-us): fixed|09/04/24|
|Maki-Landing-page|cdcfc7277c3282c91b5311330aea9930b9cafd7f|fix(contact-us): fixed contact us section|fix(contact-us): fixed contact us section|10/04/24|
|Maki-Landing-page|831d56c43fcadc4efa6869c76f580bd28c56b923|Merge branch 'develop' into feature/contact-us|Merge branch 'develop' into feature/contact-us|10/04/24|
|Maki-Landing-page|408e3981fc62fa2bd94c06e561af755682b866a7|Merge pull request #6 from WS52-CreateDev/feature/contact-us|<p>Feature/contact us</p><p></p>|10/04/24|
|Maki-Landing-page|60e91cd5c8f219ad3c36babeee02e90b0956c243|<p>Merge branch 'develop' into feature/about-us</p><p></p>|<p>Merge branch 'develop' into feature/about-us</p><p></p>|10/04/24|
|Maki-Landing-page|411d38d5c9e2ddfde11ffdc612a640a886e5f7d0|Merge pull request #5 from WS52-CreateDev/feature/about-us|<p>Feature/about us</p><p></p>|10/04/24|
|Maki-Landing-page|e0c6473d80224b38e5d8a099ef2ff68070d8da74|Merge branch 'develop' into feature/benefits|Merge branch 'develop' into feature/benefits|10/04/24|
|Maki-Landing-page|51c64f9aed21325e6e3cfc9f797cbc25d8d6d7a2|The "feature/benefits" branch was integrated into the "develop" branch.|The "feature/benefits" branch was integrated into the "develop" branch.|10/04/24|
|Maki-Landing-page|53ec259fb27f47c5fc0ad36c00abf9fc9a5fe935|Merge branch 'develop' into feature/about-the-app|Merge branch 'develop' into feature/about-the-app|10/04/24|
|Maki-Landing-page|600bcb72767ecbf59309fccd6afc7fb5cd544cbd|Merge pull request #8 from WS52-CreateDev/feature/about-the-app|The "feature/about-the-app" branch was integrated into the "develop" branch.|10/04/24|
|Maki-Landing-page|020e23f0e62a866e0a36a53055004fd46614c4bb|fix(develop): fixed index.html|fix(develop): fixed index.html|10/04/24|
|Maki-Landing-page|464e4e384d700ad472efa506ba1029de0b8295f8|feat(develop): added images|feat(develop): added images|11/04/24|
|Maki-Landing-page|447d11465b10ae6f240a6ad31627482a5582af68|fix(develop): updated team images|fix(develop): updated team images|11/04/24|
|Maki-Landing-page|55585af40fb209eadf5e7cec8b4f82225a40f6bb|fix(develop): updated team images|fix(develop): updated team images|11/04/24|
|Maki-Landing-page|ccb9905e4678a4c0f758ece859daef38cab12ad7|feat(master): added index file|feat(master): added index file|11/04/24|
|Maki-Landing-page|02a40816620151490db09a7cd8670e6c89a88995|Merge branch 'master' into develop|Merge branch 'master' into develop|11/04/24|
|Maki-Landing-page|f0f003a881fdd96c8444cd2ee056f5fe02124b66|Merge from develop branch into master|Develop|11/04/24|


#### 5.2.1.5. Execution Evidence for Sprint Review.

Vistas implementadas: la primera vista se puede observar el navbar con secciones home, meet us o know us, services, contact us. cabe resaltar que es fijo y con forme el usuario se desplaye podrá seleccionar cual sección desde el navbar

desktop web browser se muestra la versión menú de la plataforma, detallando los principales contenidos, opciones que permiten conocer más nuestro sistema al usuario.
![Imagen](https://cdn.discordapp.com/attachments/1227800643784151040/1227800730044465193/image.png?ex=6629b989&is=66174489&hm=ebf807b4e63cab329bedf9b6af1a1abe36eb2707820e3696b074f3e31a47678c&)


Al elegir la opción “Sobre nosotros” de la barra de herramientas del menú principal, se muestra  el informe  acerca de nuestro proyecto.

![Imagen](https://cdn.discordapp.com/attachments/1227800643784151040/1227800774579585055/image.png?ex=6629b994&is=66174494&hm=938d30ac9595526e60a9f24e1d1cdf6d8633c7c491290cd258ae6fe7065f9316&)

Al elegir la opción “Productos” de la barra de herramientas del menú principal, se se presenta los productos que posee el usuario a lo largo del consumo del software.

![Imagen](https://cdn.discordapp.com/attachments/1227800643784151040/1227800832691667024/image.png?ex=6629b9a1&is=661744a1&hm=4cec0618d1bf43e50502d45155b1d0cf199e097c55cc66c7fd910c1440bd52b5&)


Al elegir la opción “Equipo” de la barra de herramientas del menú principal, se muestra  los integrantes que estan a cargo del proyecto
![Imagen](https://cdn.discordapp.com/attachments/1227800643784151040/1227800894184362024/image.png?ex=6629b9b0&is=661744b0&hm=85fc4d0392043d42405e83be74d0465753ea7ec38a2b692d0ce8ce5160863bd8&)



Al elegir la opción “Contacto” de la barra de herramientas del menú principal, se muestra  un formulario para que el usuario pueda enviar su correro.

![Imagen](https://cdn.discordapp.com/attachments/1227800643784151040/1227800961477513217/image.png?ex=6629b9c0&is=661744c0&hm=611c6ad96e7dd84061b623d472a58cf3b015b34cd5113b31a40f3ffc7b408ee1&)

En la parte final de la landing page se muestra un footer, información breve de contacto, y la opción de contactarnos y nuestras redes sociales.

![Imagen](https://cdn.discordapp.com/attachments/1227800643784151040/1227801032625492048/image.png?ex=6629b9d1&is=661744d1&hm=d47aea4ee74cbe39e581a9ccc906d401d5094e26a4bc1ed728a6a2ef0c88cfe7&)


#### 5.2.1.6. Services Documentation Evidence for Sprint Review.

No se desarrolló en este sprint, pues en esta sección presentaremos la relación de Endpoints documentados con OpenAPI, relacionados con el alcance del Sprint y con web services.


#### 5.2.1.7. Software Deployment Evidence for Sprint Review.

En este sprint, se completó el desarrollo de la landing page y se utilizó un conjunto de herramientas para su despliegue

- **Git:** Se empleó como sistema de control de versiones para trabajar de manera colaborativa y monitorear las versiones de la landing page en un repositorio remoto.

- **Gitflow:** Este flujo de trabajo colaborativo permitió dividir el trabajo por ramas dentro del repositorio, facilitando la colaboración en el desarrollo.

- **GitHub:** Se utilizó esta plataforma para crear y almacenar el repositorio del proyecto, brindando una herramienta para gestionar las versiones.

- **Netlify:** Esta plataforma automatizó el proceso de alojamiento y despliegue de la landing page, siendo fundamental para ponerla en producción.


#### 5.2.1.8. Team Collaboration Insights during Sprint.

Durante el segundo Sprint, utilizamos Visual Studio Code junto con Git para gestionar nuestros commits. Inicialmente, un miembro del equipo realizó el primer commit para crear el repositorio. Luego, clonamos el repositorio con Git y procedimos a realizar cambios en Visual Studio Code. Para organizar estos cambios, creamos branches específicos y luego realizamos los commits correspondientes. Todos los commits fueron revisados y aprobados en el repositorio de GitHub por el líder del grupo.

Hemos desarrollado un total de 62 commits en el desarrollo del proyecto.

| Username  | Nombre |
| ------------- | ------------- |
| BraulioTN  | Torrejon Navarro, Braulio Rodrigo |
| alehandraxx | Diaz Villacrez, Maria Alejandra  |
| LouisAlfaro | Alfaro Coveñas, Louis Piero |
| Anthonnela | Gonzales Gomez, Antonella Frida |
| JairCoraje | Coraje Bayona, Jair Andreé  |

![Network Graph](/img/landingpage.PNG)


**Anexo: tablas de commits en el periodo de 1 mes**
![Commits](/img/3.PNG)


**Anexo: Flujo de trabajo en el periodo de 1 mes**

![Workflow](/img/1.PNG)


**Anexo: Colaboration Insights en el periodo de 1 mes**
![Collab Insights](/img/2.PNG)


### 5.2.2. Sprint 2

### 5.2.2.1 Sprint Planning 2

<table>
        <thead>
            <tr>
                <th>Sprint #</th>
                <th>Sprint 2</th>
            </tr>
        </thead>
        <tbody>
                <th><b>Sprint Planning Background</th>
            <tr>
                <th>Date</th>
                <td> 2023-04-21 </td>
            </tr>
            <tr>
                <th>Time</th>
                <td> 6:30 PM </td>
            </tr>
            <tr>
                <th>Location</th>
                <td> Reunión virtual en el servidor de Discord del Startup</td>
            </tr>  
            <tr>
                <th>Prepared By</th>
                <td> Alejandra Díaz, Antonella Gonzales </td>
            </tr> 
            <tr>
                <th>Attendees (to planning meeting)</th>
                <td> María Alejandra Díaz Villacrez, Antonella Frida Gonzales Gomez, Braulio Rodrigo Torrejon Navarro, Jair Andreé Coraje Bayona, Louis Piero Alfaro Coveñas </td>
            </tr>
            <tr>
                <th>Sprint 2 - 2 Review Summary</th>
                <td> Se crearon las ramas y repositorio para nuestro frontend. Se dividió el trabajo según bounded contexts y se creó una rama (feature) para luego hacer un merge con develop. </td>
            </tr>
            <tr>
                <th>Sprint 2 - 2 Retrospective Summary</th>
                <td> En retrospectiva, los miembros del equipo opinamos que hubo una buena comunicación y desarrollo durante el sprint. Se pudo aprender mucho sobre los errores o bugs que pueden ocurrir a la hora de elaborar el frontend. </td>
            </tr>
                <th><b>Sprint Goal & User Stories</th>
            <tr>
                <th>Sprint 2 Goal</th>
                <td> Los goals definidos son: Desarrollo de componentes según features incluidas en cada bounded context para nuestra aplicación web.
                La métrica para medir el cumplimiento de los goals será: (Número de elementos del Sprint Backlog completados)/ (Número todal de elementos del Sprint Backlog planificados) x 100% </td>
            </tr>
            <tr>
                <th>Sprint 2 Velocity</th>
                <td> Los Story Points que el equipo acepto para este Sprint fueron alrededor de 80 puntos</td>
            </tr>
            <tr>
                <th>Sum of Story Points</th>
                <td> 
                    HU-1: 5 puntos </br>
                    HU-2: 3 puntos </br>
                    HU-3: 3 puntos </br>
                    HU-4: 5 puntos </br>
                    HU-5: 8 puntos </br>
                    HU-6: 8 puntos </br> 
                    HU-7: 8 puntos </br> 
                    HU-8: 8 puntos </br>
                    HU-9: 5 puntos </br>
                    HU-10: 5 puntos </br>
                    HU-11: 8 puntos </br>
                    HU-12: 3 puntos </br>
                    HU-13: 5 puntos </br>
                    HU-14: 5 puntos </br>                                   
                    Suma total: 80 Story points
                </td>
            </tr>
        </tbody>
    </table>

### 5.2.2.2 Sprint Backlog 2
|**Sprint #**|**Sprint 2**|||||||
| :- | :- | :- | :- | :- | :- | :- | :- |
|**User Story**|**Work Item / Task**|||||||
|Id|Title|Id|Title|Description|Estimation (Hours)|Assigned To|Status|
|HU-01|Login y registro (ambos segmentos)|WL-01|Login y registro |Implementar el componente Login y registro de ambos segmentos|3|Antonella|Done|
|HU-02|Perfil de usuario y editar perfil (ambos segmentos)|WL-02|Perfil de usuario y editar perfil |Implementar el componente Perfil de usuario y editar perfil|3\.5|Jair|Done|
|HU-03|Diseños solicitados y solicitar diseño|WL-03|Diseños solicitados y solicitar diseño|Implementar el componente diseños solicitados y solicitar diseño para su respectivo segmento|4|Braulio|Done|
|HU-04|Subir producto, mostrar todos los productos y detalle de producto|WL-04|Subir producto, mostrar todos los productos y detalle de producto|Implementos el componente subir, mostrarlo y su detalle del producto|4|Alejandra|Done|
|HU-05|Carrito y detalle del carrito|WL-05|Carrito y detalle del carrito|Implementar botón carrito para agregar y eliminar dando su precio final en la sección productos|3\.5|Louis|Done|
|HU-06|Agregar mock-up de registro|WL-06|Mock-up de registro|Implementar  mock-up de registro|3|Braulio|Done|

### 5.2.2.3 Development Evidence for Sprint Review

|Repository|Branch|Commit id|Commit Mesage|Commit Mesage Body|Commited on (Date)|
| :- | :- | :- | :- | :- | :- |
|maki-front-end|feature/login-general(then develop)|2f13abc|feat(login-general):added login general|-|23/04/2024|
|maki-front-end|feature/list-products(then develop)|77beb52|feat(list-products): added list-products component|-|24/04/2024|
|maki-front-end|feature/the-about-product(then develop)|fe68e5c|feat(the-about-product): added the about product component|-|24/04/2024|
|maki-front-end|feature/post-product(then develop)|75e733a|feat(post-product): added post product component|-|24/04/2024|
|maki-front-end|feature/custom-design(then develop)|84746fd|feat(custom-design): added custom design component|-|26/04/2024|
|maki-front-end|feature/login-customer(then develop)|a9ab479|feat(login-customer):added complete login customer|-|28/04/2024|
|maki-front-end|feature/login-artisan(then develop)|2caf9ae|feat(login-artisan):added complete login artisan|-|28/04/2024|
|maki-front-end|feature/register-customer(then develop)|daf473d|feat(register-customer):added complete register customer|-|28/04/2024|
|maki-front-end|feature/register-artisan(then develop)|28985b0|feat(register-artisan):added complete register artisan|-|28/04/2024|

### 5.2.2.4 Testing Suite Evidence for Sprint Review
Para la entrega del Sprint 2, se tuvo pensado alcanzar el desarrollo completo del despliegue del FrontEnd. En esta sección presentamos la implementación del FrontEnd.



|Repository|Branch	Commit Id|Commit Message|Commit Message Body|Commited on (Date)|
| :- | :- | :- | :- | :- |
|Maki-FrontEnd|14542d034e7c1e51bd42c52e14b06cd9b8532a14|Initial commit|Initial commit|23/04/24|
|Maki-FrontEnd|9077b954d010d1a23b2ae67ce2e04ea8237a79f5|feat(develop): initial proyect|feat(develop): initial proyect|23/04/24|
|Maki-FrontEnd|2f13abc034c5b057072102c45201e23350c7dc86|feat(login-general):added login general|feat(login-general):added login general|23/04/24|
|Maki-FrontEnd|8c07b9bf5766771ef11c0d3d15fec709e1e71b9a|fix(develop): fixed develop template|added locales and assets folders, fixed main.js|24/04/24|
|Maki-FrontEnd|77beb52fe27a71fd21fb616c169161795ccbead4|feat(list-products): added list-products component|feat(list-products): added list-products component|24/04/24|
|Maki-FrontEnd|fe68e5c9b8113452ab864ac9ee4d636e65ce39e2|feat(the-about-product): added the about product component|feat(the-about-product): added the about product component|24/04/24|
|Maki-FrontEnd|c1f3c222d70b46355f74d63b050dbf9e109c45d2|fix(list-products): fixed the-toolbar component|fix(list-products): fixed the-toolbar component|24/04/24|
|Maki-FrontEnd|75e733abde17f4b0ad2fe987589cbb149f633e62|feat(post-product): added post product component|feat(post-product): added post product component|24/04/24|
|Maki-FrontEnd|ad2b2e5ac7b83732f67f18ea250c1fe919096b8b|feat(post-product): added post product component|feat(post-product): added post product component|24/04/24|
|Maki-FrontEnd|ad2b2e5ac7b83732f67f18ea250c1fe919096b8b|Merge branch 'develop' of https://github.com/WS52-CreateDev/maki-front-end into feature/login-general|Merge branch 'develop' of https://github.com/WS52-CreateDev/maki-front-end into feature/login-general|24/04/24|
|Maki-FrontEnd|bafddad01123529a0ef201a28172a83c833d6897|Merge branch 'feature/list-products' of https://github.com/WS52-CreateDev/maki-front-end into feature/login-general|Merge branch 'feature/list-products' of https://github.com/WS52-CreateDev/maki-front-end into feature/login-general|24/04/24|
|Maki-FrontEnd|14d3edb6a18c577538fa4e70df9b473e90704970|Merge branch 'feature/list-products' of https://github.com/WS52-CreateDev/maki-front-end into feature/login-general|Merge branch 'feature/list-products' of https://github.com/WS52-CreateDev/maki-front-end into feature/login-general|24/04/24|
|Maki-FrontEnd|10da84d22c5db6ed8b0281c8804540f916865d55|Merge branch 'feature/the-about-product' of https://github.com/WS52-CreateDev/maki-front-end into feature/login-general|Merge branch 'feature/the-about-product' of https://github.com/WS52-CreateDev/maki-front-end into feature/login-general|24/04/24|
|Maki-FrontEnd|947274a5471975f4bd5e94a9943cf95825bfb046|<p>Merge pull request #1 from WS52-CreateDev/feature/hero</p><p></p>|<p>Merge pull request #1 from WS52-CreateDev/feature/hero</p><p></p><p></p>|24/04/24|
|Maki-FrontEnd|84746fde9513264798923bc7f91c6f6f5a2e15a8|Feature(Custom design)|Feature(Custom design)|26/04/24|
|Maki-FrontEnd|66564656961da4dbebeb8caf59548faf3afc8e28|feat(login-general):added complete login|feat(login-general):added complete login|28/04/24|
|Maki-FrontEnd|a9ab4799c7679ed7dd3a29b938ae1173a96e87f6|feat(login-customer):added complete login customer|feat(login-customer):added complete login customer|28/04/24|
|Maki-FrontEnd|2caf9aed60d46bb44df9b4f89755dd4442df7ddd|feat(login-artisan):added complete login artisan |<p>feat(login-artisan):added complete login artisan </p><p></p><p></p>|28/04/24|
|Maki-FrontEnd|daf473d86f407e5a58d6de6ad0b19fc208479525|feat(register-customer):added complete register customer|feat(register-customer):added complete register customer|28/04/24|
|Maki-FrontEnd|28985b045b7689e47ddbfa3cc7f6a1f8faaf20cf|feat(register-artisan):added complete register artisan|feat(register-artisan):added complete register artisan|28/04/24|
|Maki-FrontEnd|08150bc0392338cd2a0e82edded7423606c1894f|Merge pull request #1 from WS52-CreateDev/feature/login-general |Merge pull request #1 from WS52-CreateDev/feature/login-general|28/04/24|
|Maki-FrontEnd|2e45e26dc65dc3cd7a3fb4c5eb473bba72a73621|Merge pull request #2 from WS52-CreateDev/feature/login-customer |<p>Merge pull request #2 from WS52-CreateDev/feature/login-customer </p><p></p>|28/04/24|
|Maki-FrontEnd|7bd9985970d5560460106ce0e275b2531765f2cf|Merge pull request #3 from WS52-CreateDev/feature/login-artisan|Merge pull request #3 from WS52-CreateDev/feature/login-artisan|28/04/24|
|Maki-FrontEnd|2fbe140f18b1e06a775adaccafab92a2477c3551|Merge pull request #4 from WS52-CreateDev/feature/register-artisan|Merge pull request #4 from WS52-CreateDev/feature/register-artisan|28/04/24|
|Maki-FrontEnd|3097ecb40b2a55a7d1f1a8308f5e2030a6bb9aec|Merge branch 'develop' into feature/custom-design|Merge branch 'develop' into feature/custom-design|28/04/24|
|Maki-FrontEnd|b895e4d1346db8bd6b46badaac570691fbf17c0d|Merge pull request #5 from WS52-CreateDev/feature/custom-design|Merge pull request #5 from WS52-CreateDev/feature/custom-design|28/04/24|
|Maki-FrontEnd|e435286b29f6d60b61a33000fe2664ddb62ff537|fix(develop): fixed product components|f ix(develop): fixed product components|29/04/24|
|Maki-FrontEnd|cd385123767411afa24f1f67590b53af4db45588|feat(develop):added complete internationalization in log in|feat(develop):added complete internationalization in log in|29/04/24|
|Maki-FrontEnd|ae1c7e0424c1de177a51299420a595c70d887439|feat(develop): add profile components, update login components |feat(develop): add profile components, update login components |30/04/24|
|Maki-FrontEnd|e4c9780e3f8cf2501dd77a86c68bcd518cf6e292|Feature(Fixed custom-design)|Feature(Fixed custom-design) |30/04/24|
|Maki-FrontEnd|7daef8be3180de9afa01332e4c42cafadeb54c8f|feature(added design and fixed things, also implement the i)18n.js|feature(added design and fixed things, also implement the i)18n.js|30/04/24|
|Maki-FrontEnd|a1065a3debc8c552c403b9cb1bb1fca69f6ca369|Add feature(shoppingcart component)|Add feature(shoppingcart component)|30/04/24|
|Maki-FrontEnd|cbe9720ede621e33a36f0b3092559a342814691b|feat(develop): add sessionStorage|feat(develop): add sessionStorage|1/05/24|
|Maki-FrontEnd|05a1c388b93542bb87420f19085ccd745dbbf8bf|feat(develop): add session storage in products components|feat(develop): add session storage in products components|1/05/24|
|Maki-FrontEnd|990874ef3fc2dd00efd09710fe831ee519928191|feat(develop): update view-profile-artisan component|feat(develop): update view-profile-artisan component|1/05/24|
|Maki-FrontEnd|515f04246147bbcc15aae9050af30d24e6437c4d|fix(develop): fixed list-products feature|fix(develop): fixed list-products feature|1/05/24|
|Maki-FrontEnd|c3ad7c34b142755d1ff2642770986d4602daa045|feature(routerlink to buttons)|feature(routerlink to buttons)|1/05/24|

### 5.2.2.5 Execution Evidence for Sprint Review

#### Login general, donde el usuario puede elegir como iniciar sesion

![Imagen](https://cdn.discordapp.com/attachments/1231761393368174644/1235275661766033500/image.png?ex=6633c79c&is=6632761c&hm=1ddb8f78ad979cf10443dfb0fd9c525e83b60a8a7cc344c793756f90f4a30b10& )

#### Login Cliente

![Imagen]( https://cdn.discordapp.com/attachments/1231761393368174644/1235278628481400852/image.png?ex=6633ca5f&is=663278df&hm=0b122a686116eef38d23a4592717d80e97868a519349c3b7d2d9441b34089c6b&)

#### Login Artesano

![Imagen]( https://cdn.discordapp.com/attachments/1231761393368174644/1235278689005207633/image.png?ex=6633ca6d&is=663278ed&hm=1d487e89fea63b3279d2ec7ae46de40474d62aa6de3951d0299c4467a2335db2&)

#### Registrarse como Cliente

![Imagen]( https://cdn.discordapp.com/attachments/1231761393368174644/1235278955137863690/image.png?ex=6633caad&is=6632792d&hm=cd1f4f0b1ae80c8a6ed1f9651f3735be71ce0e1724911edfda9fec933d4f56b6&)


#### Registrarse como artesano

![Imagen](https://cdn.discordapp.com/attachments/1231761393368174644/1235278738489479178/image.png?ex=6633ca79&is=663278f9&hm=07c0233795fbd0bf30ff0a2f1a0b653fea7b9296b341a75be3f5509260f65eab& )


#### Pantalla principal del Cliente, donde puede viasualisar los productos 

![Imagen]( https://cdn.discordapp.com/attachments/1231761393368174644/1235279219211239555/image.png?ex=6633caec&is=6632796c&hm=710707ebcb2998b76d0032ea64dc3f655d81886fc25a8146650791493fd88033&)

#### Detalles de los productos

![Imagen]( https://cdn.discordapp.com/attachments/1231761393368174644/1235279432759902239/image.png?ex=6633cb1f&is=6632799f&hm=ed40fbfdb5dd404dc0b4b222c9b28bff03ebd03e0e4921f8f2a03474d2205f2c&)

#### Agregar productos al carrito

![Imagen](https://cdn.discordapp.com/attachments/1231761393368174644/1235279887154286612/image.png?ex=6633cb8b&is=66327a0b&hm=78ea29b1fa332caed763514fcdc71c199150ea1f4cdbc4a20b41098042ae835f& )

#### Ver los Artesanos

![Imagen](https://cdn.discordapp.com/attachments/1231761393368174644/1235280338683564115/image.png?ex=6633cbf7&is=66327a77&hm=08a861ad35196a4fff90e1472a4eff7b5f16d9b3e7cd6803508354daecf6514b& )

#### Visualizar perfil del usuario

![Imagen](https://cdn.discordapp.com/attachments/1231761393368174644/1235279541975388230/image.png?ex=6633cb39&is=663279b9&hm=c163b5b48a85f353d2c43800e93cbc4f1122566a9eb67b9285e794740abcaf3d& )

#### Editar perfil del usuario

![Imagen](https://cdn.discordapp.com/attachments/1231761393368174644/1235279597050790019/image.png?ex=6633cb46&is=663279c6&hm=d576006e5cef833c1c425c4563bb3a43dc6291a2c3d4af8fde66eb5b43f1aa92& )
### 5.2.2.6 Services Documentation Evidence for Sprint Review

No se desarrolló en este sprint, pues en esta sección presentaremos la relación de Endpoints documentados con OpenAPI, relacionados con el alcance del Sprint y con web services.

### 5.2.2.7 Software Deployment Evidence for Sprint Review

Para realizar el despliegue automático de nuestro Front-End, hemos utilizamos la herramienta Vercel, el cual nos permite alojar nuestro código desarrollado y generar una página en base al despliegue del desarrollo. 

Para poder desarrollar, nos tenemos que logear en la pagina de Vercel y despues seleccionar nuestro repositorio:

![Imagen](https://cdn.discordapp.com/attachments/784950770000199721/1235375067769339925/image.png?ex=66342430&is=6632d2b0&hm=96612bc0f2b6e8d166c213df9ec0113db5019d04b2372225be16e9f1b3840fc4&)

Después de subir nuestro repositorio, procedemos a deployear el proyecto el cual ejecutara los comandos en su consola:

![Imagen](https://cdn.discordapp.com/attachments/784950770000199721/1235375529767604274/image.png?ex=6634249e&is=6632d31e&hm=db3b23d5f98df87b3f3d0e8fc596cdcc21ab85811884c0b7313b2b618b3c695c&)

Al terminar de desplegar nos mostrara la vista previa de nuestro proyecto:

![Deployment](/img/deployment-evidence.jpg)

El link de nuestro Front-End es el siguiente: 

https://maki-front-end-pi.vercel.app


### 5.2.2.8 Team Collaboration Insights during Sprint

Durante el segundo Sprint, empleamos Visual Studio Code junto con Git para gestionar los commits. Inicialmente, un miembro del equipo realizó el primer commit para crear el repositorio. Posteriormente, clonamos el repositorio con Git y realizamos los cambios necesarios en Visual Studio Code. Creamos branches para estos cambios y finalizamos con los commits correspondientes. Todos los commits fueron revisados en el repositorio de GitHub y los pull request solicitados fueron aprobados por el líder del grupo.

Colaboracion durante el sprint 2 a nuestro repositorio de front-end en el periodo de 1 mes.

![Pulse](/img/pulse.png)
![Clones](/img/clones.png)

### 5.2.3. Sprint 3

#### 5.2.3.1. Sprint Planning 3

En el Sprint Planning 3, se llevó a cabo una sesión de planificación para la elaboración de:

<table>
        <thead>
            <tr>
                <th>Sprint #</th>
                <th>Sprint 3</th>
            </tr>
        </thead>
        <tbody>
                <th><b>Sprint Planning Background</th>
            <tr>
                <th>Date</th>
                <td> 16-05-2024 </td>
            </tr>
            <tr>
                <th>Time</th>
                <td> 10:00 PM </td>
            </tr>
            <tr>
                <th>Location</th>
                <td> Reunión virtual en el servidor de Discord del Startup</td>
            </tr>  
            <tr>
                <th>Prepared By</th>
                <td> Alejandra Díaz, Antonella Gonzales </td>
            </tr> 
            <tr>
                <th>Attendees (to planning meeting)</th>
                <td> María Alejandra Díaz Villacrez, Antonella Frida Gonzales Gomez, Braulio Rodrigo Torrejon Navarro, Jair Andreé Coraje Bayona, Louis Piero Alfaro Coveñas </td>
            </tr>
            <tr>
                <th>Sprint 3 - 1 Review Summary</th>
                <td> Se revisaron las correcciones pendientes para el TB3, se divieron las partes de nuestro backend a desarrollar en el sprint, se repartieron los features según bounded context y se agendaron las reuniones siguientes para revisión de avances.</td>
            </tr>
            <tr>
                <th>Sprint 3 - 1 Retrospective Summary</th>
                <td> En retrospectiva, los miembros del equipo opinan que trabajar colaborativamente para la elaboración del backend va a ser lo más beneficioso ya que se pueden encontrar dificultades en su implementación para esta primer entrega de web services. </td>
            </tr>
                <th><b>Sprint Goal & User Stories</th>
            <tr>
                <th>Sprint 3 Goal</th>
                <td> Los goals definidos son: Implementación del backend, web services.  
                La métrica para medir el cumplimiento de los goals será: (Número de elementos del Sprint Backlog completados)/ (Número todal de elementos del Sprint Backlog planificados) x 100% </td>
            </tr>
            <tr>
                <th>Sprint 3 Velocity</th>
                <td> Los Story Points que el equipo acepto para este Sprint fueron alrededor de 12 puntos</td>
            </tr>
            <tr>
                <th>Sum of Story Points</th>
                <td> 
                    TS001: 3 puntos<br>
                    TS002: 3 puntos<br>
                    TS003: 3 puntos<br>
                    TS004: 3 puntos<br>
                    Suma total: 12 Story points
                </td>
        </tr>
    </tbody>
</table>

#### 5.2.3.2. Sprint Backlog 3

En el tercer sprint backlog, el equipo completó parcialmente tanto el frontend como el backend de la aplicación web. Para organizar y gestionar al equipo, se utilizó la herramienta Trello. Esta herramienta permitió dividir todas las historias de usuario en tareas manejables y asignarlas a los distintos miembros del equipo.

![backlog-trello](/img/sprint-backlog-3-maki.png)

Link de Trello: https://trello.com/b/7LbQIFjQ

<table>
  <tr>
    <td> <strong>Sprint #</strong></td>
    <td colspan="7"> <strong>Sprint 3</strong> </td>
  </tr>

  <tr>
    <td colspan="2"> <strong>Technical Story</strong></td>
    <td colspan="6"> <strong>Work-item/Task</strong></td>
  </tr>
  <tr>
    <td> <strong>ID</strong> </td>
    <td> <strong>Title</strong></td>
    <td> <strong>ID</strong> </td>
    <td> <strong>Title</strong></td>
    <td> <strong>Description</strong></td>
    <td> <strong>Estimation (Hours)</strong></td>
    <td> <strong>Assigned To</strong></td>
    <td> <strong> Status (To-do/In-Process/To-Review/Done) </strong></td>
  </tr>
  <!---------------------------------------------------------------------- -->
  <tr>
    <td rowspan="3">TS001</td>
    <td rowspan="3">Obtener Usuarios</td>
    <td>TA1</td>
    <td>Get Profiles</td>
    <td>Endpoint que retorna los perfiles registrados</td>
    <td rowspan="3">3</td>
    <td rowspan="3">Antonella Frida Gonzales, Jair Andreé Coraje </td>
    <td rowspan="3">Done</td>
  </tr>
  <tr>
    <td>TA2</td>
    <td>Get Profile by Id</td>
    <td>Endpoint que retorna un perfil dado un Id</td>
  </tr>
  <tr>
    <td>TA3</td>
    <td>Post Profile</td>
    <td>Endpoint que permite le registro de un nuevo perfil</td>
  </tr>
  <!------------------------------------------------------------------------>
  <tr>
    <td rowspan="3">TS002</td>
    <td rowspan="3">Obtener Productos</td>
    <td>TA4</td>
    <td>Get Products</td>
    <td>Endpoint que retorna los productos del sistema</td>
    <td rowspan="3">3</td>
    <td rowspan="3">Maria Alejandra Díaz </td>
    <td rowspan="3">Done</td>
  </tr>
  <tr>
    <td>TA5</td>
    <td>Get Product by Id</td>
    <td>Endpoint que retorna un producto dado un Id</td>
  </tr>
  <tr>
    <td>TA6</td>
    <td>Post Product</td>
    <td>Endpoint que permite el registro de un nuevo producto</td>
  </tr>
  <!------------------------------------------------------------------------>
  <tr>
    <td rowspan="2">TS003</td>
    <td rowspan="2">Obtener Categorias</td>
    <td>TA7</td>
    <td>Get category by Id</td>
    <td>Endpoint que retorna una categoria dado un Id</td>
    <td rowspan="2">3</td>
    <td rowspan="2">Maria Alejandra Díaz</td>
    <td rowspan="2">Done</td>
  </tr>
  <tr>
    <td>TA8</td>
    <td>Post Category</td>
    <td>Endpoint que permite el registro de una nueva categoria</td>
  </tr>
  <!------------------------------------------------------------------------>
  <tr>
    <td rowspan="2">TS004</td>
    <td rowspan="2">Obtener Diseños</td>
    <td>TA9</td>
    <td>Get Designs by Id</td>
    <td>Endpoint que retorna la solicitud de diseño de un producto dado un Id</td>
    <td rowspan="2">3</td>
    <td rowspan="2">Braulio Rodrigo Torrejon</td>
    <td rowspan="2">Done</td>
  </tr>
  <tr>
    <td>TA10</td>
    <td>Post Design</td>
    <td>Endpoint que permite el registro de la solicitud de diseño de un producto</td>
  </tr>
</table>

#### 5.2.3.3. Development Evidence for Sprint Review 

#### 5.2.3.4. Testing Suite Evidence for Sprint Review 

#### 5.2.3.5. Execution Evidence for Sprint Review 

#### 5.2.3.6. Services Documentation Evidence for Sprint Review  

Hemos desarrollado una serie de endpoints para la gestión de roles y usuarios en nuestra aplicación. A continuación, se detallan estos endpoints y cómo interactuar con ellos:

<h3>Customer</h3>
<h4>GET</h4>
<strong>Path: </strong>/Customer</br>
<strong>Parámetros: Ninguno</strong></br>
Este endpoint recupera todas los clientes disponibles en la aplicación.


![Imagen](https://cdn.discordapp.com/attachments/1231761393368174644/1248407462705500241/image.png?ex=66638d8d&is=66623c0d&hm=e96c6fe9dd9cbfb6381d4ef36a46a84ef8f303b5157195f610bb6c1535157bdc&)


<h4>POST</h4>
<strong>Path: </strong>/Customer</br>
<strong>Parámetros: {nombre, email, password}</strong></br>
Este endpoint crea un nuevo cliente en la aplicación.

![Imagen](https://cdn.discordapp.com/attachments/1231761393368174644/1248408241361260634/image.png?ex=66638e47&is=66623cc7&hm=b91162b289765da010ac850b00bab3dcf03adfd5f493fa8b7faf809764bc627e&)


<h4>GET</h4>
<strong>Path: </strong>/Customer</br>
<strong>Parámetros: {id}</strong></br>
Este endpoint recupera el cliente con el id especificado.

![Imagen](https://cdn.discordapp.com/attachments/1231761393368174644/1248408929013334081/image.png?ex=66638eea&is=66623d6a&hm=73b3e82f3c542fe5b67a36b697ed68dbda334a6a1bf7007b6bb8cbee1396c058& )


<h4>PUT</h4>
<strong>Path: </strong>/Customer</br>
<strong>Parámetros:  {nombre, email, password}</strong></br>
Este endpoint actualiza el cliente con el id especificado.

![Imagen](https://cdn.discordapp.com/attachments/1231761393368174644/1248410985748762705/image.png?ex=666390d5&is=66623f55&hm=d49c20cd40fa4575f45db9ba0d63534c02a60a42907ac8c217207b84e4137b0e&)


<h4>POST</h4>
<strong>Path: </strong>/Customer</br>
<strong>Parámetros:  {email, password}</strong></br>
Este endpoint autentica al cliente y devuelve un token de acceso.

![Imagen](https://cdn.discordapp.com/attachments/1231761393368174644/1248412143955611648/image.png?ex=666391e9&is=66624069&hm=6338370cc8a207c14e137ea2a21755443cd35fe5ee8516ea584e463f8ca3f8c1&)



<h4>DELETE</h4>
<strong>Path: </strong>/Customer</br>
<strong>Parámetros:  {id}</strong></br>
Este endpoint elimina el cliente con el id especificado.

![Imagen](https://cdn.discordapp.com/attachments/1231761393368174644/1248412440635641916/image.png?ex=66639230&is=666240b0&hm=d49786de36677bb4cfacb5c9c612b0c75007edf4949ebd77e40d90ec3e05ada4&)


<h3>Product</h3>
<h4>GET</h4>
<strong>Path: </strong>/Product</br>
<strong>Parámetros: Ninguno</strong></br>
Este endpoint recupera todas los productos disponibles en la aplicación.

![Imagen]( https://cdn.discordapp.com/attachments/1231761393368174644/1248414550152187956/image.png?ex=66639427&is=666242a7&hm=828a9b279707db995d5f1e9ae51797164c022ba310ce58447da26bfc7e5d2ce2&)


<h4>POST</h4>
<strong>Path: </strong>/Product</br>
<strong>Parámetros:  {nombre, precio, descripcion}</strong></br>
Este endpoint crea un nuevo producto en la aplicación.

![Imagen]( https://cdn.discordapp.com/attachments/1231761393368174644/1248414828473749654/image.png?ex=66639469&is=666242e9&hm=4d6778db48b5541a30318c21753e70d2a8cb03320d989ac6b324991c937fffcd&)


<h4>GET</h4>
<strong>Path: </strong>/Product</br>
<strong>Parámetros:  {id}</strong></br>
Este endpoint recupera el producto con el id especificado.

![Imagen](https://cdn.discordapp.com/attachments/1231761393368174644/1248415289708777532/image.png?ex=666394d7&is=66624357&hm=d58f270c303e35fc28598ed941931618824a04f78816e9f9283dba98d770dc5d& )


<h4>PUT</h4>
<strong>Path: </strong>/Product</br>
<strong>Parámetros: {nombre, precio, descripcion}</strong></br>
Este endpoint actualiza el producto con el id especificado.

![Imagen]( https://cdn.discordapp.com/attachments/1231761393368174644/1248415503819473056/image.png?ex=6663950a&is=6662438a&hm=a2df0b544b346340a5918b6012c6097501a8739ff7f98bcc33df03868ec9c0b3&)


<h4>DELETE</h4>
<strong>Path: </strong>/Product</br>
<strong>Parámetros: {id}</strong></br>
ste endpoint elimina el producto con el id especificado.

![Imagen](https://cdn.discordapp.com/attachments/1231761393368174644/1248415779859206144/image.png?ex=6663954c&is=666243cc&hm=9dd96b97eae66a8928aa880f7a8a313eb0dd4b72ff0a79cb84ffdaa39cb61101& )


<h3>Category</h3>
<h4>GET</h4>
<strong>Path: </strong>/Category</br>
<strong>Parámetros: Ninguno</strong></br>
Este endpoint recupera todos las categorías disponibles en la aplicación.

![Imagen](https://cdn.discordapp.com/attachments/1231761393368174644/1248417007775387700/image.png?ex=66639671&is=666244f1&hm=fd64cd2792ff8f067f5a48e8c4f7f02483b46e30bab74a35f18261e7e178b19b&)



<h4>POST</h4>
<strong>Path: </strong>/Category</br>
<strong>Parámetros:  {nombre, descripcion}</strong></br>
Este endpoint crea una nueva categoría en la aplicación.

![Imagen](https://cdn.discordapp.com/attachments/1231761393368174644/1248417372654800907/image.png?ex=666396c8&is=66624548&hm=c0be1f73c1e84b61a41fa01cd517d93bc9f068b8372d306580aec6aa7abd4241&)


<h4>GET</h4>
<strong>Path: </strong>/Category</br>
<strong>Parámetros: {id}</strong></br>
Este endpoint recupera la categoría con el id especificado.

![Imagen](https://cdn.discordapp.com/attachments/1231761393368174644/1248417580335497287/image.png?ex=666396f9&is=66624579&hm=bf00f3054249c4f928cd83d0e60e1305314b0767815d4f665428fbcd5ad20fda&)


<h4>PUT</h4>
<strong>Path: </strong>/Category</br>
<strong>Parámetros: {nombre, descripcion}</strong></br>
Este endpoint actualiza la categoría con el id especificado.

![Imagen](https://cdn.discordapp.com/attachments/1231761393368174644/1248417869461459015/image.png?ex=6663973e&is=666245be&hm=34f842433d3ebf2455080717c26cd0abb1ab99c547a2be1a084880069af9296a&)


<h4>DELETE</h4>
<strong>Path: </strong>/Category</br>
<strong>Parámetros: {id}</strong></br>
Este endpoint elimina la categoría con el id especificado.

![Imagen](https://cdn.discordapp.com/attachments/1231761393368174644/1248418019181596782/image.png?ex=66639762&is=666245e2&hm=c706f3334cbe2fd057afd293c85324a2d6daf56ea210c2be89528651492584da&)


#### 5.2.3.7. Software Deployment Evidence for Sprint Review

#### 5.2.3.8. Team Collaboration Insights during Sprint

## 5.3. Validation Interviews

### 5.3.1. Diseño de Entrevistas

- User Goal: Navegar por la landing page
User persona → Artesanos y clientes
Explicación del flujo → El usuario deberá ingresar a la landing page de la aplicación web. En esta, podrá desplazarse y visualizar información general sobre los servicios ofrecidos, así como los beneficios de utilizar la aplicación. Además, podrá cambiar el idioma a inglés o español a través de un botón. También, tendrá acceso directo a la aplicación web a través de un Call To Action situado en la vista principal de la landing page.

- User Goal: Iniciar sesión
User persona → Artesanos y clientes
Explicación del flujo → Primero, el usuario deberá ingresar a la aplicación desplegada. A continuación, verá en la pantalla un formulario que le pedirá sus datos de inicio de sesión, específicamente su correo electrónico y contraseña. Una vez validadas las credenciales, el sistema le permitirá ingresar a la aplicación. En caso el usuario no tenga una cuenta, puede registrarse completando otro formulario con sus datos personales.

- User Goal: Ver perfil
User persona → Artesanos y clientes
Explicación del flujo → El usuario tiene dos formas de acceder a su perfil. La primera opción es a través de un panel lateral ubicado a la izquierda de la aplicación; al hacer clic en el ícono de la persona, podrá acceder a su perfil, donde verá sus datos personales y detalles de la cuenta. La segunda opción es desde la barra de navegación en la parte superior de la aplicación; al hacer clic en "Mi perfil", accederá a la misma vista mencionada.

- User Goal: Buscar productos
User persona → Clientes
Explicación del flujo → Primero el usuario puede acceder a la vista de búsqueda de productos desde el sidebar lateral, donde podrá buscar productos por nombre, categoría o artesano. Además, podrá filtrar los resultados de la búsqueda. Una vez seleccionado un producto, podrá ver sus detalles, añadirlo al carrito, y proceder a la compra.

- User Goal: Administrar productos
User persona → Artesanos
Explicación del flujo → El usuario deberá acceder a la vista de gestión de productos. En esta, podrá ver los productos que ha subido a la plataforma, así como añadir nuevos productos, editar detalles de los existentes, y eliminar aquellos que ya no desea vender. Además, podrá revisar las peticiones de patrones personalizadas realizadas por los usuarios.

- User Goal: Comprar un producto
User persona → Clientes
Explicación del flujo → El usuario deberá buscar y seleccionar el producto que desea comprar. Una vez en la página del producto, puede añadirlo al carrito de compras. Desde el carrito, el usuario podrá proceder al checkout, donde ingresará sus datos de envío y pago para completar la compra. Tras finalizar la compra, recibirá una confirmación y detalles del pedido.

- User Goal: Subir un producto
User persona → Artesanos
Explicación del flujo → El usuario deberá acceder a la vista de gestión de productos. En esta, podrá seleccionar la opción para añadir un nuevo producto, completando un formulario con los detalles del producto, incluyendo imágenes, descripción, precio, y categoría. Una vez completados todos los campos, podrá subir el producto a la plataforma, donde estará disponible para que los clientes lo vean y compren.

- User Goal: Revisar peticiones de patrones
User persona → Artesanos
Explicación del flujo → El usuario podrá acceder a las peticiones de patrones desde su panel de administración. Aquí, podrá ver una lista de solicitudes realizadas por los clientes, con detalles específicos de cada petición. El artesano puede aceptar, rechazar o solicitar más información sobre la petición, y mantener comunicación directa con el cliente si es necesario.

- User Goal: Solicitar un diseño personalizado
User persona → Clientes
Explicación del flujo → El usuario podrá seleccionar la opción de "Solicitar diseño personalizado" desde la página principal o desde la vista de un producto. Al hacer clic, será dirigido a un formulario donde podrá describir el diseño deseado, adjuntar referencias y especificar detalles adicionales. Una vez enviada la solicitud, el artesano correspondiente podrá revisarla y comunicarse con el cliente para afinar detalles.

- User Goal: Administrar pedidos
User persona → Artesanos
Explicación del flujo → El usuario deberá acceder a la vista de gestión de pedidos. Aquí, podrá ver todos los pedidos realizados por los clientes, con detalles como el estado del pedido, fecha de realización, y productos incluidos. El artesano podrá actualizar el estado del pedido (por ejemplo, en preparación, enviado, completado) y añadir comentarios si es necesario.

### 5.3.2. Registro de Entrevistas

Entrevistas a Clientes

<table>
    <thead>
        <tr>
            <th>Entrevistado 1</th>
            <th>Christian Barzola</th>
        </tr>
        <tr>
            <th>Entrevistador</th>
            <th>Antonella Gonzales</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Edad</td>
            <td>21</td>
        </tr>
        <tr>
            <td>Distrito</td>
            <td>San Martin de Porres</td>
        </tr>
        <tr>
            <td>
                <img src="https://cdn.discordapp.com/attachments/1231761393368174644/1248426274121318551/image.png?ex=66639f12&is=66624d92&hm=7c013cbbfb5e6a3de8f34e2e1e4487cd35a39f5686536c027d4bc0a3c4162162" alt="Imagen">
            </td>
            <td>
                <strong>Resumen:</strong><br>
                Durante la conversación, Christian compartió sus impresiones sobre la aplicación desde la perspectiva del usuario. Destacó que encuentra la aplicación satisfactoria y que cumple con las expectativas de un usuario exigente. Le pareció interesante y elogió su interfaz intuitiva. Sin embargo, también señaló algunas áreas de mejora potencial en la aplicación. En particular, mencionó la necesidad de reducir la redundancia en la interfaz, ya que considera que esto puede generar confusión entre los usuarios. Sus comentarios ofrecen valiosas sugerencias para perfeccionar aún más la experiencia del usuario en la aplicación.
            </td>
        </tr>
        <tr>
            <td>Timing de la entrevista</td>
            <td>10</td>
        </tr>
        <tr>
            <td>URL de la entrevista</td>
            <td>---</td>
        </tr>
        <tr>
            <th>Entrevistado 2</th>
            <th></th>
        </tr>
        <tr>
            <th>Entrevistador</th>
            <th></th>
        </tr>
        <tr>
            <td>Edad</td>
            <td></td>
        </tr>
        <tr>
            <td>Distrito</td>
            <td></td>
        </tr>
        <tr>
            <td>
                <img src="" alt="Foto de entrevista">
            </td>
            <td>
                <strong>Resumen:</strong><br>
                resumen
            </td>
        </tr>
        <tr>
            <td>Timing de la entrevista</td>
            <td>!</td>
        </tr>
        <tr>
            <td>URL de la entrevista</td>
            <td>!</td>
        </tr>
        <tr>
            <th>Entrevistado 3</th>
            <th>Nombre</th>
        </tr>
        <tr>
            <th>Entrevistador</th>
            <th>Nombre</th>
        </tr>
        <tr>
            <td>Edad</td>
            <td>---</td>
        </tr>
        <tr>
            <td>Distrito</td>
            <td>--</td>
        </tr>
        <tr>
            <td>
                <img src="" alt="Foto de entrevista">
            </td>
            <td>
                <strong>Resumen:</strong><br>
                --
            </td>
        </tr>
        <tr>
            <td>Timing de la entrevista</td>
            <td>--</td>
        </tr>
        <tr>
            <td>URL de la entrevista</td>
            <td>--</td>
        </tr>
    </tbody>
</table>

<h2>Entrevista a Artesanos</h2>

<table>
    <thead>
        <tr>
            <th>Entrevistado 1</th>
            <th>Olga Samanez</th>
        </tr>
        <tr>
            <th>Entrevistador</th>
            <th>Alejandra Diaz</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Edad</td>
            <td>52</td>
        </tr>
        <tr>
            <td>Distrito</td>
            <td>Pueblo Libre</td>
        </tr>
        <tr>
            <td>
                <img src="" alt="Foto de entrevista">
            </td>
            <td>
                <strong>Resumen:</strong><br>
            </td>
        </tr>
        <tr>
            <td>Timing de la entrevista</td>
            <td>--</td>
        </tr>
        <tr>
            <td>URL de la entrevista</td>
            <td>--</td>
        </tr>
        <tr>
            <th>Entrevistado 2</th>
            <th>Nombre</th>
        </tr>
        <tr>
            <th>Entrevistador</th>
            <th>Nombre</th>
        </tr>
        <tr>
            <td>Edad</td>
            <td>---</td>
        </tr>
        <tr>
            <td>Distrito</td>
            <td>--</td>
        </tr>
        <tr>
            <td>
                <img src="" alt="Foto de entrevista">
            </td>
            <td>
                <strong>Resumen:</strong><br>
                resumen aqui
            </td>
        </tr>
        <tr>
            <td>Timing de la entrevista</td>
            <td>--</td>
        </tr>
        <tr>
            <td>URL de la entrevista</td>
            <td>--</td>
        </tr>
        <tr>
            <th>Entrevistado 3</th>
            <th>Nombre</th>
        </tr>
        <tr>
            <th>Entrevistador</th>
            <th>Nombre</th>
        </tr>
        <tr>
            <td>Edad</td>
            <td>---</td>
        </tr>
        <tr>
            <td>Distrito</td>
            <td>--</td>
        </tr>
        <tr>
            <td>
                <img src="" alt="Foto de entrevista">
            </td>
            <td>
                <strong>Resumen:</strong><br>
                resumen aqui
            </td>
        </tr>
        <tr>
            <td>Timing de la entrevista</td>
            <td>--</td>
        </tr>
        <tr>
            <td>URL de la entrevista</td>
            <td>--</td>
        </tr>
    </tbody>
</table>

### 5.3.3. Evaluaciones según heurísticas

**UX Heuristics & Principles Evaluation**

**Usability – Inclusive Design – Information Architecture**

CARRERA : Ingeniería de Software

CURSO : Aplicaciones Web

SECCIÓN : WS52

PROFESOR : Naldo Reupo-Musayon Gastulo

AUDITOR : CreateDev

CLIENTE(S) : -

SITE o APP A EVALUAR: -

TAREAS A EVALUAR:
El alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas:
* Landing Page
  * i. --
  * ii. --
  * iii. --
  * iv. --
* Web Application
  * i. --
  * ii. --
  * iii. --
  * iv. --
  * v. --

### ESCALA DE SEVERIDAD:
Los errores serán puntuados tomando en cuenta la siguiente escala de severidad

| Nivel | Descripción                                                                                                                                                                                     |
|-------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1     | Problema superficial: puede ser fácilmente superador por el usuario ó ocurre con muy poco frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo.                   |
| 2     | Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja resolverlo de cara al siguiente release. |
| 3     | Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es importante que sean corregidos y se les debe asignar una prioridad alta.                                 |
| 4     | Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento.                               |

#### TABLA DE RESUMEN - Landing Page

| # | Problema                                                                                             | Escala de severidad | Heurística/Principio violada(o)                 |
|---|------------------------------------------------------------------------------------------------------|---------------------|-------------------------------------------------|
| 1 | -                                                                                                    | -                   | -                                               |
| 2 | -                                                                                                    | -                   | -                                               |
| 3 | -                                                                                                    | -                   | -                                               |
| 4 | -                                                                                                    | -                   | -                                               |
| 5 | -                                                                                                    | -                   | -                                               |
| 6 | -                                                                                                    | -                   | -                                               |

**DESCRIPCIÓN DE PROBLEMAS:**

**PROBLEMA #1:** --

**Severidad:** -

**Heurística violada:** --

**Problema:**
--.

![evidencia del problema](/img/.png)

**Recomendación:**
--.

#### TABLA DE RESUMEN - Web Application


| # | Problema | Escala de severidad | Heurística/Principio violada(o)           |
|---|--------- |---------------------|-------------------------------------------|
| 1 | -        | -                   | -                                         |
| 2 | -        | -                   | -                                         |
| 3 | -        | -                   | -                                         |
| 4 | -        | -                   | -                                         |
| 5 | -        | -                   | -                                         |
| 6 | -        | -                   | -                                         |

**DESCRIPCIÓN DE PROBLEMAS:**

**PROBLEMA #1:** --

**Severidad:** -

**Heurística violada:** --

**Problema:**
--.

![evidencia del problema](/img/.png)

**Recomendación:**
--.


## 5.4. Video About-the-Product

En esta sección presentamos el video about the product. Este consolida una orientación promocional, resumiendo el modelo de nuestro negocio de Maki, las características y beneficios del producto, incluyendo algunas escenas de interacción con el producto.

<img src="/img/about-the-product-video.png"></img>

Link de Microsoft Stream: https://shorturl.at/LTPJ0

Link de Youtube: https://youtu.be/6G13QMLYB5A

## Avance de Conclusiones, Bibliografía y Anexos.

### **Conclusiones**
  
### **Bibliografía**

•	Avila Mendoza, J. L., & Carhuaricra Perez, E. M. (2021). La actividad artesanal de mates burilados en el desarrollo del turismo en la Comunidad de Cochas Chico, 2019. Recuperado de https://repositorio.uncp.edu.pe/handle/20.500.12894/7409 

•	Ministerio de Comercio Exterior y Turismo. (2019). Información de interés – Estadísticas del del Sistema de Información para la Promoción y Desarrollo del Artesano – SIPDAR. Recuperado de https://www.gob.pe/institucion/mincetur/informes-publicaciones/374828-informacion-de-interes-estadisticas 

•	Ortega Diaz, L. G. (2022). Impactos socioeconómicos de la Covid 19 en la asociación de artesanos San José I del Puerto Muelle de Puno desde marzo de 2020 hasta marzo de 2021.
Recuperado de http://repositorio.unap.edu.pe/bitstream/handle/UNAP/18119/Ortega_Diaz_Laura_Guadalupe.pdf?sequence=1&isAllowed=y 

•	Red de Comunicación Regional (RCR). (2020). EXPORTACIÓN DE ARTESANÍA SE AGRAVA POR PANDEMIA. 
Recuperado de https://www.rcrperu.com/exportacion-de-artesania-se-agrava-por-pandemia/  

### **Anexos**

<table>
        <thead>
            <tr>
                <th>Sección</th>
                <th>Características del video</th>
                <th>Sobre el contenido</th>
                <th>Integración y entrega</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Needfinding Interviews</td>
                <td>Cantidad de videos: 1 <br> 
                  Nomenclatura: upc-pre-202401-si730-ws52-createDev-needfinding-sprint-1 <br>
                  Formato: .mp4 <br>
                  Duración: 39:40 min </td>
                <td>Consolida todas las entrevistas realizadas</td>
                <td>Link: https://shorturl.at/awz05 
                  Captura: <br>
                    <img src="https://cdn.discordapp.com/attachments/1220543866789167136/1241142080542212260/interviews.png?ex=66491f23&is=6647cda3&hm=c6acd7437d2972968afd8ad4df679922188b8af3b5e17e355c500e953b65454a&" width="350"></img> </td>
                </td>
            </tr>
            <tr>
                <td>Exposicion TB1</td>
                <td>Cantidad de videos: 1 <br>
                  Nomenclatura: upc-pre-202401-si730-ws52-createDev-expo-tb1 <br>
                  Formato: .mp4 <br>
                  Duración: min</td>
                <td>Consolida las exposiciones de la TB1</td>
                <td>Link: https://shorturl.at/gmBF8
                Captura: <br> 
                  <img src="https://cdn.discordapp.com/attachments/1220543866789167136/1241142377377173504/image.png?ex=66491f6a&is=6647cdea&hm=6229a44816bdf3a1471305040a906208168466a64e404cd98680344e1ba7fe4a&" width="350"></img> </td>
                </td>
            </tr>
            <tr>
                <td>Exposicion TP</td>
                <td>Cantidad de videos: 1 <br>
                  Nomenclatura: upc-pre-202401-si730-ws52-createDev-expo-tp <br>
                  Formato: .mp4 <br>
                  Duración: min</td>
                <td>Consolida las exposiciones del TP</td>
                <td>Link: https://shorturl.at/qsAGV
                Captura: <br>
                  <img src="https://cdn.discordapp.com/attachments/1220543866789167136/1241142458805391474/image.png?ex=66491f7d&is=6647cdfd&hm=0e7463133e704d62515847190dfc3be6a31975af314612bdefc9c90595a9b60c&" width="350"></img> </td>
                </td>
            </tr>
            <tr>
                <td>Exposicion TB2</td>
                <td>Cantidad de videos: 1 <br>
                  Nomenclatura: upc-pre-202401-si730-ws52-createDev-expo-tb2 <br>
                  Formato: .mp4 <br>
                  Duración: min</td>
                <td>Consolida las exposiciones del TB2</td>
                <td>Link: 
                Captura: <br> 
                  <img src="" width="350"></img> </td>
                </td>
            </tr>
            <tr>
                <td>Validation Interviews</td>
                <td>Cantidad de videos: 1 <br>
                  Nomenclatura: upc-pre-202401-si730-ws52-createDev-validation-sprint-3 <br>
                  Formato: .mp4 <br>
                  Duración: min</td>
                <td>Consolida sesiones y
                    entrevistas de validación en
                    las que usuarios de los
                    segmentos objetivo
                    interactúen con el landing
                    page y con los prototipos
                    de experiencias web.</td>
                <td>Link: 
                Captura: <br>
                  <img src="" width="350"></img> </td>
                </td>
            </tr>
            <tr>
                <td>Video About The Product</td>
                <td>Cantidad de videos: 1 <br>
                  Nomenclatura: upc-pre-202401-si730-ws52-createDev-about-the-product-sprint-3 <br>
                  Formato: .mp4 <br>
                  Duración: 4:41 min</td>
                <td>Consolida la orientación promocional,
                    resumiendo el modelo de
                    negocio, las características
                    y beneficios del producto,
                    incluyendo algunas escenas
                    de interacción con el producto. </td>
                <td>Link Streams: https://shorturl.at/LTPJ0 Link de Youtube: https://youtu.be/6G13QMLYB5A
                Captura: <br> 
                  <img src="/img/about-the-product-video.png" width="350"></img> </td>
                </td>
            </tr>
            <tr>
                <td>Video About The Team</td>
                <td>Cantidad de videos: 1 <br>
                  Nomenclatura: upc-pre-202401-si730-ws52-createDev-about-the-team-sprint-3 <br>
                  Formato: .mp4 <br>
                  Duración: min</td>
                <td>Consolida el video que resume el
                    proceso de trabajo
                    realizado, incluyendo
                    escenas de sesiones de
                    trabajo real del equipo,
                    complementando con
                    narración (voz en off) del
                    proceso. Incluye además el
                    testimonio ante cámara de
                    cada participante
                    describiendo actividades
                    realizadas, logro de
                    outcomes y desarrollo de
                    competencias alcanzados.</td>
                <td>Link: 
                Captura: <br> 
                  <img src="" width="350"></img> </td>
                </td>
            </tr>
        </tbody>
    </table>
