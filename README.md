# ResQPets
# User stories

## A continuación se detallaran las user stories identificadas para nuestro proyecto:

<table>
  <thead> 
    <tr>
      <th>User Story ID</th>
      <th>Título</th>
      <th width = 30%>Descripción</th>
      <th width = 50%>Criterios de aceptación</th>
      <th width = 5%>Relacionado con EpicID</th>
    </tr>
  </thead>
  <tbody>
    <tr> <!--US01-->
      <td>US01</td>
      <td>Inicio de sesión</td>
      <td>Como usuario quiero poder ingresar al sitio web con mi nombre de usuario y contraseña para visualizar la información con mi cuenta</td>
      <td>
      <strong>Dado que</strong> el usuario tenga una cuenta registrada en la pagina web<br> 
      <strong>Cuando</strong> el usuario de click en la opción de iniciar sesión<br>
      <strong>Y</strong> Ingrese sus datos como nombre de usuario y contraseña<br>
      <strong>Entonces</strong> se mostrara al usuario su cuenta</td>
      <td>EP01</td>
    </tr>
    <tr> <!--US02-->
      <td>US02</td>
      <td>Registro de usuario individual</td>
      <td>Como usuario quiero poder crear una cuenta para poder utilizar las funcionalidades del sitio web</td>
      <td>
      <strong>Dado que</strong> el usuario haga click en el botón de registrarse<br> 
      <strong>Cuando</strong> el usuario ingrese sus datos<br>
      <strong>Y</strong> de click en el botón de registrar<br>
      <strong>Entonces</strong> se registrara la cuenta del usuario en el sitio web</td>
      <td>EP01</td>
    </tr>
    <tr> <!--US03-->
      <td>US03</td>
      <td>Registro de organización</td>
      <td>Como usuario miembro de una organización quiero poder crear una cuenta para poder utilizar las funcionalidades del sitio web</td>
      <td>
      <strong>Dado que</strong> haga click en el botón de registrar organización<br> 
      <strong>Cuando</strong> El usuario ingrese los datos de la organización<br>
      <strong>Y</strong> de click en el botón de validar datos y registrar organización<br>
      <strong>Y</strong> los datos sean validados correctamente<br>
      <strong>Entonces</strong> Se registrara la cuenta de la organización en el sitio web</td>
      <td>EP01</td>
    </tr>
    <tr> <!--US04-->
     <td>US04</td>
     <td>Buscar Mascotas</td>
     <td>Como adoptante potencial, quiero poder buscar mascotas disponibles para adopción por raza, edad, sexo, tamaño y ubicación.</td>
     <td>
     <strong>Dado que</strong> el usuario está buscando una mascota<br>
     <strong>Cuando</strong> el usuario ingresa los criterios de búsqueda<br>
     <strong>Entonces</strong> la aplicación muestra una lista de mascotas que coinciden con los criterios</td>
     <td>EP01</td>
    <tr> <!--US05--> 
     <td>US05</td>
     <td>Ver Perfil de Mascota</td>
     <td>Como adoptante potencial, quiero poder ver el perfil de una mascota específica, incluyendo fotos, videos, información sobre su raza, edad, sexo, tamaño, temperamento y necesidades especiales.</td>
     <td>
     <strong>Dado que</strong> el usuario ha encontrado una mascota que le interesa<br>
     <strong>Cuando</strong> el usuario hace clic en el perfil de la mascota<br>
     <strong>Entonces</strong> la aplicación muestra la información completa de la mascota</td>
     <td>EP01</td>
    </tr>
    <tr> <!--US06-->
      <td>US06</td>
     <td>Contactar con la Organización</td>
     <td>Como adoptante potencial, quiero poder contactar con la organización responsable de la mascota que me interesa para hacer preguntas y programar una visita.</td>
     <td>
     <strong>Dado que</strong> el usuario quiere más información sobre una mascota<br>
     <strong>Cuando</strong> el usuario hace clic en el botón de contacto<br>
     <strong>Entonces</strong> la aplicación muestra la información de contacto de la organización
     </td>
     <td>EP01</td>
    </tr>
    <tr> <!--US07-->
      <td>US07</td>
     <td>Completar Formulario de Adopción</td>
     <td>Como adoptante potencial, quiero poder completar un formulario de adopción online para iniciar el proceso de adopción de la mascota que he elegido.</td>
     <td>
     <strong>Dado que</strong> el usuario ha decidido adoptar una mascota<br>
     <strong>Cuando</strong> el usuario hace clic en el botón de "Adoptar"<br>
     <strong>Entonces</strong> la aplicación muestra el formulario de adopción
     </td>
   <td>EP02</td>
  </tr>
  <tr> <!--US08-->    
    <td>US08</td>
     <td>Recibir Notificaciones</td>
     <td>Como adoptante potencial, quiero recibir notificaciones sobre el estado de mi solicitud de adopción para poder estar al tanto del proceso.</td>
     <td>
     <strong>Dado que</strong> el usuario ha enviado una solicitud de adopción<br>
     <strong>Cuando</strong> hay un cambio en el estado de la solicitud<br>
     <strong>Entonces</strong> la aplicación envía una notificación al usuario
     </td>
   <td>EP02</td>
  </tr>
  <tr> <!--US09-->
    <td>US09</td>
   <td>Crear Perfil de Organización</td>
   <td>Como representante de un refugio o una organización de rescate, quiero poder crear un perfil para mi organización, incluyendo información sobre nuestra misión, las mascotas que tenemos disponibles para adopción y cómo contactarnos.</td>
   <td>
   <strong>Dado que</strong> la organización no tiene un perfil en la aplicación<br>
   <strong>Cuando</strong> el representante de la organización ingresa la información de la organización<br>
   <strong>Entonces</strong> la aplicación crea el perfil de la organización
   </td>
   <td>EP03</td>
  </tr>
  <tr> <!--US10-->   
  <td>US10</td>
   <td>Añadir Mascotas</td>
   <td>Como representante de un refugio o una organización de rescate, quiero poder añadir fotos y videos de las mascotas disponibles para adopción, así como editar su información.</td>
   <td>
   <strong>Dado que</strong> la organización tiene nuevas mascotas disponibles<br>
   <strong>Cuando</strong> el representante de la organización ingresa la información de la mascota<br>
   <strong>Entonces</strong> la aplicación añade la mascota al perfil de la organización
   </td>
   <td>EP03</td>
  </tr>
  <tr> <!--US11-->   
    <td>US11</td>
    <td>Leer sobre Adopción Responsable</td>
    <td>Como usuario general, quiero poder encontrar información sobre la adopción responsable de mascotas para poder tomar una decisión informada antes de adoptar.</td>
    <td>
    <strong>Dado que</strong> el usuario quiere saber más sobre la adopción responsable<br>
    <strong>Cuando</strong> el usuario hace clic en la sección de "Adopción Responsable"<br>
    <strong>Entonces</strong> la aplicación muestra información sobre el tema
    </td>
    <td>EP05</td>
  </tr>
  <tr> <!--US12-->   
   <td>US12</td>
   <td>Conocer Organizaciones de Protección Animal</td>
   <td>Como usuario general, quiero poder conocer las diferentes organizaciones que trabajan en la protección de animales en mi ciudad para poder apoyar su labor.</td>
   <td>
   <strong>Dado que</strong> el usuario quiere ayudar a los animales<br>
   <strong>Cuando</strong> el usuario busca una organización en la aplicación<br>
   <strong>Entonces</strong> la aplicación muestra una lista de organizaciones en la zona
   </td>
   <td>EP05</td>
  </tr>
  <tr> <!--US13-->   
     <td>US13</td>
     <td>Donar a Organizaciones</td>
     <td>Como usuario general, quiero poder donar a organizaciones que ayudan a animales en situación de calle para contribuir a su bienestar.</td>
     <td>
     <strong>Dado que</strong> el usuario quiere apoyar a las organizaciones<br>
     <strong>Cuando</strong> el usuario accede a la sección de donaciones<br>
     <strong>Entonces</strong> la aplicación muestra diferentes métodos para realizar donaciones (ej. tarjeta de crédito, transferencia bancaria)
     </td>
     <td>EP05</td>
  </tr>
<tr>  <!--US14--> 
  <td>US14</td>
   <td>Favoritos</td>
   <td>Como usuario general o adoptante potencial, quiero poder marcar mascotas como favoritas para recibir notificaciones cuando haya una mascota que coincida con sus preferencias.</td>
   <td>
   <strong>Dado que</strong> el usuario ha encontrado una mascota que le interesa<br>
   <strong>Cuando</strong> el usuario selecciona la opción de "favorito"<br>
   <strong>Entonces</strong> la aplicación guarda la mascota en una lista de favoritos
   </td>
   <td>EP07</td>
  </tr>
<tr> <!--US15-->  
  <td>US15</td>
   <td>Compartir en Redes Sociales</td>
   <td>Como usuario general o adoptante potencial, quiero poder compartir información sobre mascotas disponibles para adopción en mis redes sociales para ayudar a crear conciencia sobre el problema del abandono animal.</td>
   <td>
   <strong>Dado que</strong> el usuario quiere ayudar a encontrar un hogar a las mascotas<br>
   <strong>Cuando</strong> el usuario selecciona la opción de compartir<br>
   <strong>Entonces</strong> la aplicación permite compartir la información de la mascota en redes sociales populares
   </td>
   <td>EP07</td>
  </tr>
  </tr>
  </tbody>
<table>
