# Proyecto_Final_Fede_Origlia
Proyecto Final 45020 Federico Origlia

•	De la carpeta que se te ha puesto a disposición en GitHub, clickea sobre la misma con botón derecho del mouse elige la opcion abrir con VisualStudioCode,
•	En la terminal de la aplicación VSC, vas a colocar python manage.py runserver enter, 
•	Luego en la misma terminal te va aparecer entre las varias líneas, la siguiente línea http://127.0.0.1:8000/ que vas a copiar con ctrl+c,
•	Ahora vas a ir a tu  browser (Chrome, Firefox, etc) y vas a pegar la línera con ctrl+v + enter,
•	Se va a desplegar en la web del browser un menú de opciones de navegacion, ahí vas a poder elegir entre las varias aplicaciones,
•	Para ser ordenados elije la opcion 1, entonces vas a poner en el buscador del browser 127.0.0.1:8000/admin/ enter,
o	Te va a direccionar a la página de Administración de Django, como Nombre de Usuario vas a poner fedru y como Contraseña fede1234fede, ahí ya tienes acceso como usuario staff a a la aplicación de Blog Posts, en la misma vas a poder ingresar a Usuarios  donde podras ver quienes forman parte del staff y o no (para añadir, ver, eliminar), Grupos (no lo usaremos en la aplicación)  y Avatars (para asignarle el avatar a los usuarios existentes, si así lo deseas). Lo vas a poder hacer seleccionando el usuario, y la imagen del avatar a asignarle,
o	Para salir vas arriba a la derecha a Cerrar Sesion,
•	Volvemos a 127.0.0.1:8000 y ahora colocamos 127.0.0.1:8000/ejemplo-soft/ enter, te va a llevar a la pagina inicial del Blog, ahí vas a tener a disposicion los últimos blogs posteados, al cual puedes acceder en Leer Mas (y sales de ellos con la flecha volver del Browser arriba a la izquierda),
•	En el menú de opciones (arriba a la derecha), vas a poder seleccionar Inicio (te lleva al indice de la web del Blog),
•	Acerca de (te cuenta un poco ns. Historia),
•	Contacto donde vas a poder enviarnos mensajes acerca de ns. Posts, temas que te interesan, etc. Ahí nos vas a dejar tus datos, Nombre, e-mail y texto acerca del tema por el cual nos contactas,
•	Registrarse para poder formar parte de nuestros usuarios. Prueba a cargar el Usuario jose y la Constraseña jose1234jose luego enter en botón Registrarse, genial ya formas parte de nuestros usuarios. Ahora en el Browser vas a poder acceder a ver todos los Posts de nuestro Blog,
•	Cada vez que salgas del Blog con Salir o cerrar la aplicación puedes volver a ingresar clickeando en el botón Ingresar, (solo recuerda tu Usuario y Contraseña si ya te has dado de alta),
•	Otra forma de acceder a los distintos servicios del Blog es: Para ello volvemos a 127.0.0.1:8000 
o	Si ponemos 127.0.0.1:8000/ejemplo-soft/listar/ nos va a dar un listado de todos los Post publicados hasta la fecha que podremos ver uno a uno. Si somos usuarios registrados podremos Crear Post, Actualizar Avatar, Actualizar Perfil, leer Mensajes enviados. Además de Borrar, Actualizar o Ver los Posts a disposición,
o	Si ponemos 127.0.0.1:8000/ejemplo-soft/”indicar post que nos interesa”/detalle/  por ejemplo 127.0.0.1:8000/ejemplo-soft/1/detalle/ nos lleva al Post de detalle, o sea, nos permite ingresar en el Post para su lectura,
o	Si ponemos 127.0.0.1:8000/ejemplo-soft/crear/ para todos aquellos Usuarios Registrados, permite previo Ingresar, crear Posts,
o	Si ponemos 127.0.0.1:8000/ejemplo-soft/”indicar post que nos interesa”/borrar/  por ejemplo 127.0.0.1:8000/ejemplo-soft/1/borrar/ si sos usuario registrado, nos lleva al Post a ser Borrado previa confirmación,
o	Si ponemos 127.0.0.1:8000/ejemplo-soft/”indicar post que nos interesa”/actualizar/  por ejemplo 127.0.0.1:8000/ejemplo-soft/1/actualizar/ nos lleva al Post a ser Actualizado (solo para usuarios registrados), se puede Actualizar imagen, texto y/o la fecha de actualizacion,
Saliendo de Blog de Posts, veremos los aplicativos relativos a los usuarios, para ello:
•	Si ponemos 127.0.0.1:8000/ejemplo-soft/login/ para todos aquellos usuarios registrados, permite ingresar a todos los accesos permitidos a Usuarios Registrados (podremos Crear Post, Actualizar Avatar, Actualizar Perfil, leer Mensajes enviados. Además de Borrar, Actualizar o Ver los Posts a disposición),
•	Si ponemos 127.0.0.1:8000/ejemplo-soft/logout/ nos desloguea del Blog (idem a boton salir),
•	Si ponemos 127.0.0.1:8000/ejemplo-soft/avatars/”indicar avatar que nos interesa”/ actualizar/ por ejemplo 127.0.0.1:8000/ejemplo-soft/avatars/1/actualizar/ nos permite actualizar el Avatar de acuerdo al índice indicado, donde deberemos seleccionar el nuevo archivo del Avatar, o simplemente tildar en limpiar para luego proceder a Actualizar,
•	Idem para la información del Usuario, si ponemos 127.0.0.1:8000/ejemplo-soft/users/”indicar usuario que nos interesa”/ actualizar/ por ejemplo 127.0.0.1:8000/ejemplo-soft/users/1/actualizar/ nos permite actualizar los datos del Usuario  de acuerdo al índice indicado. Deberemos indicar Nombre, Apellidos y e-mail para luego indicar Actualizar,
Por ultimo, podremos hacer una gestión detallada (crear, listar, detalle) de los Mensajes enviados a ns. Blog, para ello debemos:
•	Colocamos 127.0.0.1:8000/ejemplo-soft/mensajes/crear/ enter, te va a llevar a la pagina de escribir mensajes, indicando tu nombre, e-mail, luego el texto del mensaje y Enviar,
•	Colocamos 127.0.0.1:8000/ejemplo-soft/mensajes/listar/ enter, si sos Usuario Registrado,  previo loguearse, te va a llevar a la pagina de todos los mensajes recibidos hasta ahora, donde vas a poder acceder a cada uno de ellos,
•	Por ultimo, Colocamos 127.0.0.1:8000/ejemplo-soft/mensajes/”indicar mensaje que nos interesa”/detalle/ por ejemplo, por ejemplo 127.0.0.1:8000/ejemplo-soft/mensajes/1/detalle/ enter, si sos Usuario Registrado, previo loguearse, te va a llevar a la pagina de detalle del mensaje seleccionado.
Y es todo lo que tenemos para decirte desde el Blog de Posts, espero te haya gustado…!
