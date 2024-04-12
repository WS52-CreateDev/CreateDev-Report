# Capítulo V: Product Implementation, Validation & Deployment.

## 5.1. Software Configuration Management. 

La gestión de la configuración de software es fundamental para garantizar un desarrollo de software eficiente y controlado. Incluye la administración de la configuración del entorno de desarrollo, la gestión del código fuente, las guías de estilo y convenciones, así como la configuración del despliegue de software.

### 5.1.1. Software Development Environment Configuration.

Configuramos un entorno de desarrollo completo para facilitar la creación, compilación y prueba de nuestro software. Este entorno incluye IDEs como Visual Studio Code, junto con las dependencias necesarias para el lenguaje de programación utilizado, como Node.js para JavaScript.

### 5.1.2. Source Code Management.

Gestionamos nuestro código fuente utilizando sistemas de control de versiones como Git, alojando nuestro repositorio en plataformas como GitHub o GitLab. Esto nos permite mantener un registro de los cambios realizados en el código, colaborar eficazmente con otros miembros del equipo y revertir a versiones anteriores según sea necesario.

### 5.1.3. Source Code Style Guide & Conventions.

Adoptamos una guía de estilo y convenciones de código para asegurar la coherencia y legibilidad del mismo. Esta guía se basa en estándares reconocidos por la comunidad de desarrollo de software y abarca aspectos como la nomenclatura, el formato, la gestión de errores y los comentarios, con el objetivo de mejorar la mantenibilidad del código.

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
            <td>Visualización del logo de CreateDev</td>
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
| alehandraxx | Gonzales Gomez, Antonella  |
| Carlo211 | Content Cell  |
| LouisAlfaro | Alfaro Coveñas, Louis Piero |
| Anthonnela | Gonzales Gomez, Antonella Frida |
| JairCoraje | Coraje Bayona, Jair Andreé  |


**Anexo: tablas de commits en el periodo de 1 mes**
<p align = "center"> <img src="/img/flujodetrabajo.PNG" width="800"></img> </p>



**Anexo: Flujo de trabajo en el periodo de 1 mes**
<p align = "center"> <img src="/img/tabladecommits.PNG" width="800"></img> </p>



**Anexo: Colaboration Insights en el periodo de 1 mes**
<p align = "center"> <img src="/img/colaborationinsights.PNG" width="800"></img> </p>


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
                  <img src="/img/interviews.png" width="350"></img> </td>
            </tr>
            <tr>
                <td>Exposicion</td>
                <td>Cantidad de videos: 1 <br>
                  Nomenclatura: upc-pre-202401-si730-ws52-createDev-expo-tb1 <br>
                  Formato: .mp4 <br>
                  Duración: min</td>
                <td>Consolida las exposiciones de la TB1</td>
                <td>Link: Captura: </td>
            </tr>
        </tbody>
    </table>
