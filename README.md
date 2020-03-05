# Gallery, aplicación android para compartir imágenes.

1	¿QUÉ ES GALLERY?
Gallery es una aplicación bajo la plataforma android desarrollada con Ionic Framework y Firebase, la cual permite capturar imágenes con el dispositovo y alojarlas en la base de datos Firebase, de manera que cualquier dispositivo que tenga instalado Gallery podrá ver las imágenes compartidas por los demás usuarios.
Gallery está compuesto primeramente por una interfaz en donde se pedirá su email y password con el fin de autenticarse en la base de datos, posteriormente se muestran las imágenes que han sido compartidas y además de ofrecer la opción de capturar imáganes para subirlas, es una aplicación parecida  a la red social conocida como Instagram.

2	COMPONENTES 
Los componentes de Gallery como ya se mencionó anteriormente es un framework reciente llamado Ionic y una base de datos para alojar las imágenes llamada Firebase. A continuación se describe cada uno de ellos.
2.1	IONIC FRAMEWORK
Ionic es una herramienta Open Source utilizada para desarrollar aplicaciones híbridas y multiplataforma, combinando las tecnologías más usadas convirtiéndose en un Meta-framework, debido a que utiliza AngularJS, SASS, Apache Córdova, NodeJS y Gulp entre otros. Al trabajar con AngularJS permite generar aplicaciones bajo MVC, de forma que se han de separar los componentes de vistas, los controladores que interactúan con las vistas y los modelos.
Ionic ofrece la creación de componentes mediante  directivas personalizadas, además de que permite utilizar estilos pre-construidos, para plataformas tanto para android como para iOS.
Ionic hace uso de NodeJS para poder crear los proyectos, construirlos, emularlos en un navegador web o mediante un ADV y compilarlos en cualquier plataforma.


2.2	FIREBASE
Firebase es un servicio que provee de un Backend en la nube con una fuente de datos en tiempo real y además cuenta con librerías para poder conectarnos a ella. El uso de Firebase permite crear aplicaciones con datos que se sincronizan en tiempo real a través de diversos dispositivos de manera que disminuye el tiempo de desarrollo. Una de las características que se utilizaron en la creación de Gallery es la de autenticación con Firebase, ya que permite un login con usuario y su contraseña, además de permitir la autenticación con conectores sociales como, Facebook, Twitter, Google, entre otros.
3	FUNCIONAMIENTO
La forma de funcionar de Gallery es mediante un primeramente un login, ingresando su correo electrónico y password el usuario puede ingresar a la App, o de otra manera es registrándose como lo muestra la Fig.1.   Una vez que se ha autenticado muestra las imágenes alojadas en la base de datos y permite agregar fotos e imágenes, guardándose automáticamente en Firebase como se observa en la Fig. 3.

4	CONCLUSIÓN
Como hemos visto, actualmente existen incontables tecnologías que facilitan el desarrollo de aplicaciones,  que en conjunto pueden volverse tan completas como nosotros queramos,  y que en este caso se optó por utilizar una servicio de alojamiento en la nube para almacenar nuestra aplicación.
