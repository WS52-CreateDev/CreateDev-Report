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

Contenido

#### 5.2.1.3. Development Evidence for Sprint Review.

Contenido

#### 5.2.1.4. Testing Suite Evidence for Sprint Review.

Contenido

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

Contenido

#### 5.2.1.8. Team Collaboration Insights during Sprint.

Contenido

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
