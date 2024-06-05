es# Capítulo III: Requirements Specification.




   1. ## <a name="_toc103526023"></a><a name="_toc103526148"></a><a name="_toc103528493"></a><a name="_toc103681138"></a><a name="_toc104884605"></a><a name="_toc105028352"></a><a name="_toc105028415"></a><a name="_toc106381686"></a><a name="_toc106384733"></a><a name="_toc106465574"></a><a name="_toc106465575"></a>To-Be Scenario Mapping.
En este apartado se desarrolla el To-be Scenario Mapping en base al análisis del As-is Scenario Mapping. Con esto seremos capaces de identificar puntos de mejora, replantearemos nuestros objetivos y tendremos, en general, un mejor desarrollo de nuestra aplicación.

### <a name="_toc102524916"></a><a name="_toc106465576"></a>3.1.1. To-be Scenario Mapping User Cliente:


![Imagen]( https://cdn.discordapp.com/attachments/754867305468395543/1228367719708102708/image.png?ex=662bc996&is=66195496&hm=cfafe4b9f91aa80c55dafabc6aecf8ec5f3cfe084aa48705d6e488c63aaafb8a& )








### <a name="_toc102524917"></a><a name="_toc106465577"></a>3.1.2. To-be Scenario Mapping User Artesano:


![Imagen](  https://cdn.discordapp.com/attachments/754867305468395543/1228367719708102708/image.png?ex=662bc996&is=66195496&hm=cfafe4b9f91aa80c55dafabc6aecf8ec5f3cfe084aa48705d6e488c63aaafb8a& )



## 3.2. User Stories. 

|Epic / User Story ID|Título|Descripción|Criterios de Aceptación|Relacionado con (Epic ID)|
| :- | :- | :- | :- | :- |
|<p></p><p>Preferencia y gestión de Cuenta.</p><p>**/HU01**</p><p></p>|Registrar Cuenta|Como usuario, deseo crear una nueva cuenta para entrar a la plataforma.|<p>Escenario 1: Ingreso correcto de datos.</p><p></p><p>**Dado que** el usuario se encuentra en el formulario de registro</p><p>**Cuando** ingresa su nombre, correo, ubicación, edad, número de celular, contraseña y apellidos correctos, y elige su rol</p><p>**Entonces** se registra su nueva cuenta</p><p></p><p></p><p>**Escenario 1:** Ingreso incorrecto de datos.</p><p></p><p>**Dado** que el usuario intenta registrarse en la aplicación.</p><p>Cuando el usuario intenta registrarse sin proporcionar información válida en uno o más campos requeridos.</p><p>**Entonces** el sistema no permite que el usuario complete el proceso de registro y el usuario recibe un mensaje de error que indica los campos que deben corregirse.</p><p></p><p></p>|**EPIC-01**|
|<p>Preferencia y gestión de Cuenta.</p><p>**/HU02**</p><p></p>|<p>Iniciar Sesión</p><p></p>|Como usuario deseo iniciar sesión con la cuenta que cree para poder acceder a las funciones de la aplicación.|<p>**Escenario 1:** Inicio de Sesión Exitoso</p><p></p><p>**Dado** **que** un usuario registrado se encuentra en la pantalla de inicio de sesión.</p><p>**Cuando** el usuario ingresa sus credenciales (nombre de usuario y contraseña) correctamente.</p><p>**Entonces** el sistema permite que el usuario inicie sesión con éxito y lo redirige a la página principal.</p><p>**Escenario 2:** Inicio de Sesión Fallido debido a Credenciales Incorrectas</p><p>**Dado que** un usuario registrado se encuentra en la pantalla de inicio de sesión.</p><p>**Cuando** el usuario ingresa credenciales incorrectas (nombre de usuario o contraseña incorrectos).</p><p>**Entonces** el sistema no permite que el usuario inicie sesión y muestra un mensaje de error que indica que las credenciales son incorrectas.</p><p></p>|**EPIC-01**|
|<p>Preferencia y gestión de Cuenta. **/HU03**</p><p></p>|Recuperación de la Cuenta|Como usuario, deseo poder recuperar mi cuenta en caso de que olvide mi contraseña o dirección de correo electrónico, para evitar tener que crear una nueva cuenta.|<p>**Escenario 1**:  **no recuerda su contraseña**</p><p>**Dado que** el usuario, se encuentra en el sitio web y no recuerda su contraseña.</p><p>**Cuando** en la página de inicio de sesión selecciona la opción "¿Olvidaste tu contraseña?".</p><p>**Entonces** se le redirige a una página donde debe ingresar la dirección de correo electrónico asociada a su cuenta en el sitio web.</p><p>**Escenario N°2**</p><p>Usuario recibe Código de verificación</p><p>**Dado que** el usuario ha recibido el código de verificación en su correo electrónico.</p><p>**Cuando** el usuario regresa al sitio web e ingresa el código de verificación en la página de recuperación de contraseña.</p><p>**Entonces** se habilita la opción para restablecer la contraseña de la cuenta.</p><p>**Escenario N°3**</p><p>**Restablecimiento de Contraseña**</p><p>**Dado** que el usuario puede restablecer su contraseña en el sitio web.</p><p>**Cuando** el usuario escribe su nueva contraseña dos veces en la página de restablecimiento de contraseña.</p><p>**Entonces** después de confirmar la contraseña, se le redirige a la página de inicio de sesión donde puede iniciar sesión con su nueva contraseña.</p><p></p>|**EPIC-01**|
|Preferencia y Gestión de Cuenta. / **HU-04**|Cierre de sesión  |Como usuario de la plataforma, deseo poder cerrar sesión en mi cuenta para proteger mi privacidad y seguridad cuando finalice mi sesión de uso.|<p>**Escenario 1:** Cierre de Sesión Exitoso:</p><p>**Dado** que el usuario ha completado su actividad en la plataforma y desea cerrar sesión.       **Cuando** el usuario busca la opción de cerrar sesión.                                                             **Entonces** el sistema muestra un mensaje de confirmación para verificar si el usuario desea cerrar sesión. Si el usuario confirma la acción, el sistema cierra la sesión del usuario y lo redirige a la página de inicio.</p><p>**Escenario 2:** Cancelación del Cierre de Sesión:  </p><p>**Dado** que el usuario ha seleccionado la opción de cerrar sesión, pero luego decide no cerrar la sesión.                                                                **Cuando** el sistema muestra el mensaje de confirmación para cerrar sesión.                  **Entonces** el usuario puede optar por cancelar la acción y permanecer en su sesión actual.</p>|**EPIC-01**|
|Preferencia y Gestión de Cuenta. **/ HU-05**|Editar información del perfil|Como usuario, deseo tener la opción de editar la información de mi perfil para mantenerla actualizada.|<p>` `**Escenario 1:**</p><p>**Acceso a la Edición de Perfil**</p><p>**Dado** que el usuario desea editar su información de perfil.</p><p>**Cuando** acceda a la sección de "Perfil" o "Configuración de Cuenta" en la aplicación,</p><p>**Entonces** se le proporcionará la opción de "Editar Perfil".</p><p>**Escenario 2:**</p><p>**Edición de Datos Personales**</p><p>**Dado** que el usuario ha seleccionado "Editar Perfil",</p><p>**Cuando** modifique datos personales como nombre, dirección de correo electrónico, número de teléfono u otros campos relevantes,</p><p>**Entonces** se guardarán los cambios y se actualizará la información en el perfil.</p><p>**Escenario 3:**</p><p>**Cambio de Contraseña**</p><p>**Dado** que el usuario desea cambiar su contraseña por motivos de seguridad,</p><p>**Cuando** seleccione la opción para "Cambiar Contraseña",</p><p>**Entonces** se le solicitará que ingrese su contraseña actual y luego proporcione y confirme la nueva contraseña. Una vez confirmada, se actualizará la contraseña de la cuenta.</p><p></p>|**EPIC-02**|
|Gestión de búsqueda  **/ HU-06**|Buscar Artesanías |Como cliente quiero buscar productos de artesanía |<p>**Escenario 1:**  buscar productos</p><p><br>**Dado** que el cliente se encuentra en el menú principal de la plataforma </p><p>**Cuando** el cliente busca el producto por su nombre </p><p><br>**Entonces** El sistema muestra una lista de productos que coinciden con la búsqueda del cliente, incluyendo la dirección del proveedor y detalles relevantes del producto.</p><p></p><p>**Escenario 2:** Búsqueda por Categorías</p><p></p><p>**Dado** que cliente que está explorando la plataforma en busca de productos de artesanía.</p><p>**Cuando** utilizo la función de navegación o menús desplegables para buscar productos por categoría, como "Joyas", "Decoración para el Hogar" o "Arte Textil".</p><p>**Entonces** el sistema muestra una lista de productos dentro de la categoría seleccionada.</p><p><br>**Escenario 3:** Búsqueda sin Resultados</p><p></p><p>**Dado** que el cliente se encuentra en el menú principal de la plataforma.</p><p>**Cuando** el cliente busca un producto por su nombre y no se encuentran resultados</p><p>**Entonces** el sistema muestra un mensaje indicando que no se encontraron productos que coincidan con la búsqueda del cliente</p><p></p>|**EPIC-02**|
|Gestión de búsqueda y personalización **/ HU-07**|Personalizar artesanías al cliente.|Como cliente quiero encontrar diferentes tipos de artesanía para personalizarlas a mi gusto|<p>**Escenario 1:** personalización de artesanías </p><p></p><p>**Dado** que el cliente ha seleccionado una artesanía para comprar</p><p>**Cuando** el cliente selecciona la opción de personalizar la artesanía</p><p>**Entonces** el sistema muestra las opciones de personalización disponibles, como colores, tamaños, materiales, etc.</p><p></p><p>**Escenario 2:** Personalización Cancelada</p><p></p><p>**Dado** que el cliente ha seleccionado una artesanía para comprar y ha iniciado el proceso de personalización.</p><p>**Cuando** el cliente decide cancelar la personalización y regresar a la página anterior</p><p>**Entonces** el sistema cancela todas las selecciones de personalización realizadas por el cliente</p><p></p>|**EPIC-03**|
|Gestión de productos de artesania **/ HU-08**|Gestión de favoritos de artesanía |Como cliente, quiero poder agregar artesanías a una lista de favoritos para poder acceder rápidamente a ellas en el futuro.|<p>**Escenario 1:** Agregar a Favoritos</p><p></p><p>**Dado** que el cliente se encuentra en la página de detalles de una artesanía.</p><p>**Cuando** el cliente selecciona la opción "Agregar a Favoritos".</p><p>**Entonces** el sistema agrega la artesanía seleccionada a la lista de favoritos del cliente y muestra un mensaje de confirmación.</p><p></p><p>**Escenario 2:** Eliminar de Favoritos</p><p></p><p>**Dado** que el cliente se encuentra en su perfil de usuario y accede a su lista de favoritos.</p><p>**Cuando** el cliente selecciona una artesanía de su lista de favoritos y elige la opción "Eliminar de Favoritos".</p><p>**Entonces** el sistema elimina la artesanía seleccionada de la lista de favoritos del cliente</p>|**EPIC-03**|
|Gestión de productos de artesania. **/ HU-09**|Registro de Negocio de Artesano en la Plataforma|Como artesano, quiero poder registrar mi negocio en la plataforma para promocionar y vender mis productos de artesanía.|<p>**Escenario 1:** Registro Exitoso </p><p></p><p>**Dado** que el artesano accede a la plataforma de registro de negocios. </p><p>**Cuando** el artesano completa el formulario de registro con la información requerida.</p><p>**Entonces** el sistema verifica la información proporcionada y aprueba el registro del negocio del artesano.</p><p></p><p>**Escenario 2:** Registro Rechazado.</p><p></p><p>**Dado** que el artesano accede a la plataforma de registro de negocios.</p><p>**Cuando** el artesano completa el formulario de registro con la información requerida.</p><p>**Entonces** el sistema verifica la información y detecta errores y muestra un mensaje de error indicando las áreas que necesitan corrección.</p><p></p>|**EPIC-03**|
|Gestión de productos de artesanía**. / HU-10**|Ver los modelos de diseños personalizados que quieren los clientes|Como artesano, quiero poder ver los modelos de diseños personalizados que solicitan los clientes para adaptar mi producción y satisfacer sus necesidades.|<p>**Escenario 1:** Visualización de Modelos de Diseños Personalizados.</p><p></p><p>**Dado** que el artesano accede al panel de control de gestión de productos de artesanía.</p><p>**Cuando** el artesano selecciona la sección de "Modelos de Diseños Personalizados".</p><p>**Entonces** el sistema muestra una lista de modelos de diseños personalizados solicitados por los clientes</p><p></p><p>**Escenario 2:** Filtrado de Modelos de Diseños Personalizados.</p><p></p><p>**Dado** que el artesano accede a la lista de modelos de diseños personalizados.</p><p>**Cuando** el artesano utiliza la función de filtrado para mostrar solo los modelos de diseños personalizados de una categoría específica.</p><p>**Entonces** el sistema actualiza la lista para mostrar solo los modelos de diseños personalizados de la categoría seleccionada por el artesano</p><p></p>|**EPIC-03**|
|Gestión de productos de artesanía**. / HU-11**|Acceso a información específica de una pieza artesana.|Como usuario cliente deseo obtener más información específica de una pieza que le llamó la atención.|<p>**Escenario 1:** Visualización de Información Detallada.</p><p></p><p>**Dado** que el cliente busca una pieza artesana en la plataforma.</p><p>**Cuando** el cliente selecciona una pieza artesana específica de la lista de productos.</p><p>**Entonces** el sistema muestra la información detallada de la pieza artesana, incluyendo el nombre del producto, descripción, materiales, dimensiones, precio y disponibilidad.</p>|**EPIC-03**|
|Gestión de productos de artesanía. **/ HU-12**|Acceso a la opción de editado de publicaciones|Como usuario artesano me gustaría tener acceso a una herramienta de editado de mis publicaciones para cambiar los datos.|<p>**Escenario 1:** Edición de una Publicación</p><p></p><p>**Dado** que el usuario artesano accede a la herramienta de edición de publicaciones.</p><p>**Cuando** el usuario artesano selecciona una publicación específica que desea editar.</p><p>**Entonces** el sistema muestra un formulario o interfaz que permite al usuario artesano modificar los detalles de la publicación, como el nombre del producto, descripción, precio, imágenes, etc.</p>|**EPIC-03**|
|<p></p><p></p><p></p><p></p><p></p><p>Gestión de productos de artesanía. **/ HU-13**</p>|Agregar Producto al Carrito|Como cliente, deseo poder agregar productos que me interesen a mi carrito de compras |<p>**Escenario 1:** Agregar Producto al Carrito</p><p></p><p>**Dado** que estoy revisando los detalles de un producto que me interesa.</p><p>**Cuando** selecciono la opción de "Agregar al Carrito".</p><p>**Entonces** el sistema agrega el producto a mi carrito de compras.</p><p>Como resultado, puedo continuar navegando por la plataforma o proceder al proceso de pago más tarde.</p><p></p><p></p><p>Escenario 2: Eliminar Producto del Carrito</p><p></p><p>**Dado** que he agregado varios productos a mi carrito de compras.</p><p>**Cuando** reviso mi carrito de compras y decido eliminar un producto.</p><p>**Entonces** el sistema me proporciona la opción de eliminar el producto seleccionado.</p><p></p><p>**Escenario 3:** Vaciar el Carrito de Compras</p><p></p><p>**Dado** que tengo productos en mi carrito de compras y deseo eliminar todos los productos del carrito.</p><p>C**uando** accedo a la opción de "Vaciar Carrito" o "Eliminar Todos los Productos".</p><p>**Entonces** el sistema me solicita confirmación para vaciar completamente el carrito.</p><p></p>|**EPIC-04**|
|Gestión de productos de artesanía. **/ HU-14**|Proceso de Pago|Como cliente, deseo poder realizar el pago de mis productos |<p>**Escenario 1**: Iniciar Proceso de Pago</p><p></p><p>**Dado** que he agregado todos los productos deseados a mi carrito de compras y estoy listo para finalizar mi compra.</p><p>**Cuando** accedo a mi carrito de compras y selecciono la opción de "Proceder al Pago".</p><p>**Entonces** el sistema me redirige a la página de pago donde debo ingresar la información necesaria para completar la transacción.</p><p></p><p>**Escenario 2:** Selección del Método de Pago</p><p></p><p>**Dado** que he ingresado a la página de pago para completar mi compra.</p><p>**Cuando** el sistema me presenta una lista de opciones para seleccionar el método de pago preferido.</p><p>**Entonces** selecciono el método de pago deseado y procedo a ingresar los detalles correspondientes según sea necesario.</p><p></p><p>**Escenario 3:** Ingresar Detalles de Pago</p><p></p><p>**Dado** que he seleccionado el método de pago </p><p>**Cuando** el sistema me solicita que ingrese los detalles requeridos para completar la transacción. </p><p>**Entonces** ingreso los detalles de pago de manera para continuar con el proceso.</p><p></p><p>**Escenario 4:** Confirmar la Orden</p><p></p><p>**Dado** que he ingresado todos los detalles de pago para finalizar la compra.</p><p>**Cuando** reviso todos los detalles de mi pedido incluyendo los productos seleccionados, la dirección de envío y el método de pago.</p><p>**Entonces** selecciono la opción de “Finalizar Compra" para completar la transacción.</p><p></p>|**EPIC-04**|
|Gestión de productos de artesanía. **/ HU-15**|<p>Seguimiento del pedido</p><p></p><p></p><p></p><p></p>|Como cliente, deseo poder rastrear el estado de mi pedido|<p>**Escenario 1:** Acceso al Estado del Pedido</p><p></p><p>**Dado** que he realizado un pedido en la plataforma </p><p>**Cuando** ingreso a mi cuenta de usuario y accedo a la sección de  "Historial de Pedidos".</p><p>**Entonces** el sistema muestra una lista completa de todos mis pedidos anteriores, incluyendo su estado actual, como "En proceso", "Enviado" o "Entregado".</p><p></p><p>**Escenario 2:** Seguimiento del Envío</p><p></p><p>Dado que he recibido la confirmación de que mi pedido ha sido enviado.</p><p>**Cuando** accedo a la página de detalles de mi pedido.</p><p>**Entonces** el sistema me proporciona la información del estado de mi pedido</p><p></p><p>**Escenario 3:** Confirmación de Entrega Exitosa</p><p></p><p>**Dado** que he rastreado mi envío y he visto que está programado para ser entregado hoy.</p><p>**Cuando** recibo la confirmación de entrega por parte del transportista.</p><p>**Entonces** el sistema actualiza el estado de mi pedido a "Entregado" de manera automática y precisa en la plataforma.</p>|**EPIC-04**|
|Gestión de productos de artesanía. **/ HU-16**|<p></p><p>Cambiar de Idioma a Español/Inglés</p><p></p>|Como usuario quiero tener la opción de cambiar el idioma del sitio entre español e inglés.|<p>**Escenario 1:** Cambiar idioma a Español</p><p></p><p>**Dado** que soy un usuario del sitio web y prefiero ver el contenido en español,</p><p>**Cuando** busque la opción de cambio de idioma en el sitio,</p><p>**Entonces** podré seleccionar "Español" y ver todo el contenido del sitio en español.</p><p></p><p>**Escenario 2:** Cambiar idioma a Inglés</p><p></p><p>**Dado** que soy un usuario del sitio web y prefiero ver el contenido en inglés,</p><p>**Cuando** busque la opción de cambio de idioma en el sitio,</p><p>**Entonces** podré seleccionar "Inglés" y ver todo el contenido del sitio en Inglés.</p><p></p>|**EPIC-05**|
|Gestión de productos de artesanía. **/ HU-17**|Navegación en la landing page|Como usuario quiero navegar libremente por la landing page para dirigirme a mis necesidades.|<p>**Escenario :**  Navegar por la landing page</p><p></p><p>**Dado** que soy un usuario nuevo/constante, deseo movilizarme para acceder a las distintas funcionalidades.</p><p>**Cuando** entre a cualquier botón de la toolbar, o Inicio,</p><p>**Entonces** podré cambiar con libertad la pagina.</p><p></p>|**EPIC-06**|
|Gestión de productos de artesanía. **/ HU-18**|carrusel de productos destacados|Como usuario visitante del landing page, quiero ver un carrusel de imágenes que muestren una variedad de productos destacados y llamativos.|<p>**Escenario 1:** Visualización del carrusel de productos destacados</p><p></p><p>**Dado** que soy un usuario visitante del sitio.</p><p>**Cuando** Ingrese a la página de inicio de la landing page.</p><p>**Entonces** Observo que en la parte superior de la página de inicio hay un carrusel de imágenes que se muestran automáticamente.</p>|**EPIC-06**|
|Gestión de productos de artesanía. **/ HU-19**|Tipos de productos en la landing page|Como usuario visitante del sitio, quiero ver los tipos de productos que ofrece|<p>**Escenario 1:** Visualización de productos en la página de inicio</p><p></p><p>**Dado** que soy un usuario visitante del landing page.</p><p>**Cuando** Ingreso a la página de inicio de la landing page.</p><p>**Entonces** Observo que en la parte superior  de la página de inicio hay una sección de productos.</p><p></p>|**EPIC-06**|
|Gestión de productos de artesanía. **/ HU-20**|sección de "Acerca de nosotros"|Como visitante del sitio, quiero una sección de "Acerca de nosotros" que presente información sobre la empresa, su misión, valores y el equipo detrás de la plataforma.|<p>**Escenario 2:** Exploración de la sección "Acerca de nosotros"</p><p></p><p>**Dado** que estoy en la sección "Acerca de nosotros" del sitio.</p><p>**Cuando** Navego por la landing page.</p><p>**Entonces** encuentro información clara y concisa sobre la historia de la empresa, su origen</p>|**EPIC-06**|
|Gestión de productos de artesanía. **/ HU-21**|Footer|que me permita seguir las cuentas de redes sociales de la plataforma para obtener más información y mantenerme al día con las últimas noticias y actualizaciones.|<p>**Escenario 1:** Acceso a enlaces de redes sociales desde la página de inicio</p><p></p><p>**Dado** que soy un visitante del sitio.</p><p>Cuando Accedo a la página de inicio de la landing page.</p><p>**Entonces:** observo que en la parte inferior o lateral de la página de inicio hay íconos de redes sociales, como Facebook, Instagram, Twitter, etc.</p>|**EPIC-06**|
||||||

### Technical Stories

   <table>
      <body>
         <tr style="text-align:center">
            <td> TS001 </td>
            <td> Obtener Usuarios </td>
            <td> 
            <strong> Como </strong> desarrollador backend en Maki,
            <strong> quiero </strong> obtener la información de los usuarios artesanos y clientes a través de una API <strong> para </strong> permitir al equipo de frontend utilizar los datos del usuario en la interfaz. </td>
            <td> 
            <h5>Escenario 01: Obtener Usuarios Exitosamente</h5>
            <strong> Dado </strong> que tengo autorización en el uso de la API y al endpoint de Usuarios,
            <strong> Cuando </strong> envío una solicitud GET para la obtención de datos del usuario, <strong> Entonces </strong>  el servidor responde con un código de estado 200 OK <strong> Y </strong> recibo la información de los usuarios en un response de formato JSON que contiene al menos un usuario con los siguientes campos: <br> 
            - Id: {ID del usuario}<br>
            - Email: {Email del usuario}<br>
            - Password: {Contraseña del usuario}<br>
            - Business Name: {Nombre del negocio del usuario (si es artesano)}<br>
            - Business Address: {Direccion del negocio del usuario (si es artesano)}<br>
            - Name: {Nombre del usuario}<br>
            - Surname: {Apellido del usuario}<br>
            - Photo: {Foto del usuario}<br>
            - Phone: {Telefono del usuario}<br>
            - Address: {Direccion del usuario}<br>
            <h5>Escenario 02: Obtener Usuarios con Parámetro Erróneo</h5>            
            <strong> Dado </strong> que tengo autorización en el uso de la API y al endpoint de Usuarios,
            <strong> Cuando </strong>envío una solicitud GET para la obtención de datos del usuario con un parámetro erróneo o inexistente,
            <strong> Entonces </strong> 
            el servidor responde con un código de estado 400 Bad Request <strong> Y </strong> recibo un mensaje de error en el response indicando que el parámetro es incorrecto o no existe.
            </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td> TS002 </td>
            <td> Obtener Productos </td>
            <td> 
            <strong> Como </strong> desarrollador backend en Maki,
            <strong> quiero </strong> obtener la información de los productos a través de una API <strong> para </strong> permitir al equipo de frontend utilizar los datos del producto en la interfaz. </td>
            <td> 
            <h5>Escenario 01: Obtener productos Exitosamente</h5>
            <strong> Dado </strong> que tengo autorización en el uso de la API y al endpoint de productos,
            <strong> Cuando </strong> envío una solicitud GET para la obtención de datos del producto, <strong> Entonces </strong>  el servidor responde con un código de estado 200 OK <strong> Y </strong> recibo la información de los productos en un response de formato JSON que contiene al menos un producto con los siguientes campos: <br> 
            - Id: {ID del producto}<br>
            - Price: {Precio del producto}<br>
            - Description: {Descripcion del producto}<br>
            - Width: {Dimension del producto}<br>
            - Depth: {Dimension del producto}<br>
            - Height: {Dimension del producto}<br>
            - Name: {Nombre del producto}<br>
            - Category: {Categoria del producto}<br>
            - Artisan: {ID del artesano que realizo el producto}<br>
            - Material: {Materiales del producto}<br>
            - Image: {Foto del producto}<br>
            <h5>Escenario 02: Obtener productos con Parámetro Erróneo</h5>            
            <strong> Dado </strong> que tengo autorización en el uso de la API y al endpoint de productos,
            <strong> Cuando </strong>envío una solicitud GET para la obtención de datos del usuario con un parámetro erróneo o inexistente,
            <strong> Entonces </strong> 
            el servidor responde con un código de estado 400 Bad Request <strong> Y </strong> recibo un mensaje de error en el response indicando que el parámetro es incorrecto o no existe.
            </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td> TS003 </td>
            <td> Obtener Categorias </td>
            <td> 
            <strong> Como </strong> desarrollador backend en Maki,
            <strong> quiero </strong> obtener la información de las Categorias a través de una API <strong> para </strong> permitir al equipo de frontend utilizar los datos de la Categoria en la interfaz. </td>
            <td> 
            <h5>Escenario 01: Obtener Categorias Exitosamente</h5>
            <strong> Dado </strong> que tengo autorización en el uso de la API y al endpoint de Categorias,
            <strong> Cuando </strong> envío una solicitud GET para la obtención de datos de la Categoria, <strong> Entonces </strong>  el servidor responde con un código de estado 200 OK <strong> Y </strong> recibo la información de las Categorias en un response de formato JSON que contiene al menos un producto con los siguientes campos: <br> 
            - Id: {ID de la categoria}<br>
            - Name: {Nombre de la categoria}<br>
            <h5>Escenario 02: Obtener Categorias con Parámetro Erróneo</h5>            
            <strong> Dado </strong> que tengo autorización en el uso de la API y al endpoint de Categorias,
            <strong> Cuando </strong>envío una solicitud GET para la obtención de datos de la Categoria con un parámetro erróneo o inexistente,
            <strong> Entonces </strong> 
            el servidor responde con un código de estado 400 Bad Request <strong> Y </strong> recibo un mensaje de error en el response indicando que el parámetro es incorrecto o no existe.
            </td>
            <td> </td>
        </tr>
        <tr style="text-align:center">
            <td> TS004 </td>
            <td> Obtener Diseños </td>
            <td> 
            <strong> Como </strong> desarrollador backend en Maki,
            <strong> quiero </strong> obtener la información de los Diseños a través de una API <strong> para </strong> permitir al equipo de frontend utilizar los datos del Diseño en la interfaz. </td>
            <td> 
            <h5>Escenario 01: Obtener Diseños Exitosamente</h5>
            <strong> Dado </strong> que tengo autorización en el uso de la API y al endpoint de Diseños,
            <strong> Cuando </strong> envío una solicitud GET para la obtención de datos del Diseño, <strong> Entonces </strong>  el servidor responde con un código de estado 200 OK <strong> Y </strong> recibo la información de los Diseños en un response de formato JSON que contiene al menos un Diseño con los siguientes campos: <br> 
            - Id: {ID del diseño}<br>
            - Name: {Nombre del diseño}<br>
            - Caracteristics: {Caracteristicas del diseño}<br>
            - Photo: {Imagen del diseño}<br>
            - UserId: {ID del usuario que solicito el diseño}<br>
            <h5>Escenario 02: Obtener Diseños con Parámetro Erróneo</h5>            
            <strong> Dado </strong> que tengo autorización en el uso de la API y al endpoint de Diseños,
            <strong> Cuando </strong>envío una solicitud GET para la obtención de datos del Diseño con un parámetro erróneo o inexistente,
            <strong> Entonces </strong> 
            el servidor responde con un código de estado 400 Bad Request <strong> Y </strong> recibo un mensaje de error en el response indicando que el parámetro es incorrecto o no existe.
            </td>
            <td> </td>
        </tr>
      </body>
   </table>



## 3.3. Impact Mapping.
**Cliente**

![Imagen](https://cdn.discordapp.com/attachments/754867305468395543/1224100752532836482/clien.jpg?ex=663355ea&is=6632046a&hm=1f18fc336569d0abe372f8361d2d449d6fee9f19e6ac7e13bdb48bdb46acc4cc&)



**Artesano**


![Imagen](https://cdn.discordapp.com/attachments/754867305468395543/1224100925342220289/artessa.jpg?ex=661c43d3&is=6609ced3&hm=ff50e15b1020edc51bfd4c24769840d111d1863b9ad0f8bdddf595c99edaa405&)

## 3.4. Product Backlog.

#
|Orden|User Story Id|Titulo|Descripción|Story Points|
| :- | :- | :- | :- | :- |
|1|**HU01**|Registrar Cuenta|Como usuario, deseo crear una nueva cuenta para entrar a la plataforma.|5|
|2|**HU02**|Iniciar Sesión|Como usuario deseo iniciar sesión con la cuenta que cree para poder acceder a las funciones de la aplicación.|3|
|3|**HU03**|Recuperación de la Cuenta|Como usuario, deseo poder recuperar mi cuenta en caso de que olvide mi contraseña o dirección de correo electrónico, para evitar tener que crear una nueva cuenta.|3|
|4|**HU-04**|Cierre de sesión|Como usuario de la plataforma, deseo poder cerrar sesión en mi cuenta para proteger mi privacidad y seguridad cuando finalice mi sesión de uso.|3|
|5|**HU-05**|Editar información del perfil|Como usuario, deseo tener la opción de editar la información de mi perfil para mantenerla actualizada.|8|
|6|**HU-06**|Buscar Artesanías|Como cliente quiero buscar productos de artesanía|8|
|7|**HU-07**|Personalizar artesanías al cliente.|Como cliente quiero encontrar diferentes tipos de artesanía para personalizarlas a mi gusto|8|
|8|**HU-08**|Gestión de favoritos de artesanía|Como cliente, quiero poder agregar artesanías a una lista de favoritos para poder acceder rápidamente a ellas en el futuro.|5|
|9|**HU-09**|Registro de Negocio de Artesano en la Plataforma|Como artesano, quiero poder registrar mi negocio en la plataforma para promocionar y vender mis productos de artesanía.|8|
|10|**HU-10**|Ver los modelos de diseños personalizados que quieren los clientes|Como artesano, quiero poder ver los modelos de diseños personalizados que solicitan los clientes para adaptar mi producción y satisfacer sus necesidades.|5|
|11|**HU-11**|Acceso a información específica de una pieza artesana.|Como usuario cliente deseo obtener más información específica de una pieza que le llamó la atención.|5|
|12|**HU-12**|Acceso a la opción de editado de publicaciones|Como usuario artesano me gustaría tener acceso a una herramienta de editado de mis publicaciones para cambiar los datos.|8|
|13|**HU-13**|Agregar Producto al Carrito|Como cliente, deseo poder agregar productos que me interesen a mi carrito de compras|3|
|14|**HU-14**|Proceso de Pago|Como cliente, deseo poder realizar el pago de mis productos|5|
|15|**HU-15**|Seguimiento del pedido|Como cliente, deseo poder rastrear el estado de mi pedido|5|
|16|**HU-16**|Cambiar de Idioma a Español/Inglés|Como usuario quiero tener la opción de cambiar el idioma del sitio entre español e inglés.|3|
|17|**HU-17**|Navegación en la landing page|Como usuario quiero navegar libremente por la landing page para dirigirme a mis necesidades.|5|
|18|**HU-18**|Carrusel de productos destacados|Como usuario visitante del sitio, quiero ver un carrusel de imágenes que muestren una variedad de productos destacados y llamativos.|3|
|19|**HU-19**|Tipos de productos|Como usuario visitante del sitio, quiero ver los tipos de productos que ofrece|3|
|20|**HU-20**|Sección de "Acerca de nosotros"|Como visitante del sitio, quiero una sección de "Acerca de nosotros" que presente información sobre la empresa, su misión, valores y el equipo detrás de la plataforma.|5|
|21|**HU-21**|Footer|Que me permita seguir las cuentas de redes sociales de la plataforma para obtener más información y mantenerme al día con las últimas noticias y actualizaciones.|5|

