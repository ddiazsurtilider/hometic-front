ACTIVIDAD
La actividad consiste en desarrollar un sitio web, teniendo en cuenta la línea grafica definida en los Mockups; deberá tener en cuenta que se espera tener un módulo de acceso y de roles, se considera puntos extra la definición de negocio de forma libre a su experiencia y conocimientos:
FRONTEND (25 puntos)
Con base en el mockup entregado realizar la implementación a través de las siguientes tecnologías:
-Angular (versión 14 o más). Puede utilizar bibliotecas de estilos a su elección (Ej. Bootstrap, SASS, Tailwind, Material UI, etc).
-Desarrollar una SPA (Aplicación Web de una sola Página.
-Realizar la autentificación por token.
-Proteger las rutas.
-Una vez el usuario inicie sesión, se deberá poder ver su nombre y rol dentro de la aplicación e imagen del perfil. Debe generar un módulo que permita listar todos los datos y que además permita hacer todas las operaciones CRUD del módulo (administrador).
-Se deben generar alertas y notificaciones que permitan al usuario conocer el estado de cada acción que ejecuta dentro del sitio web. (Ej. si es inicio de sesión correcto o incorrecto etc...)
BACKEND (25 puntos)
Desarrollar usando Java 21 con springboot 3.4.0
-Desarrollar tres servicios:
1. Conexión por Api entre frontend y backend para generar un token de autentificación.
2. Generar la implementación de una Api para mostrar en la tabla del mockup la información guardada en la base de datos.
3. Implementar un filtro o buscador general para la tabla realizada anteriormente.
4. Nota: Sí realíza el despliegue del backend por medio de flujos CI/CD en Azure DevOps tendrá puntos adicionales.

NOTA: Documentar el código realizado.
BASES DE DATOS (25 puntos)
1.	Debe definir y generar el MER de la base de datos, teniendo en cuenta las tablas para admin y roles, adicional: si consideró un flujo de negocio, hacer mención de las mismas.
2.	De acuerdo con la solicitud anterior realizar la base de datos en SQL Server versión 2022.
3.	Exportar el script correspondiente de la base de datos con sus respectivas tablas.
4.	Se debe desarrollar toda la interfaz de autenticación y su funcionalidad, es necesario generar un módulo de registro, la información de usuarios y roles se puede ingresar de manera manual en la base de datos, al acceder dependiendo el rol me debe generar la vista con los permisos correspondientes.
ENTREGABLES
· Url del repo donde está todo el código del frontend.
· Url del repo donde está todo el código del backend.
· MER de la base de datos.
· Script SQL que permite generar la base de datos y los datos necesarios para utilizar el aplicativo.
· Matriz de roles y usuarios con sus respectivas credenciales.
. Todo el código debe estar versionado utilizando git, además de que se debe trabajar con las siguientes 2 ramas:
-	o develop: rama donde se debe trabajar todo el desarrollo.
-	o máster: rama donde debe estar vacía.
Puntaje total: 100 puntos
NOTA:  Cuando termines la prueba porfavor remítela al mismo correo a través del cual se te envió. Puedes enviar por el correo el link del repositorio en el cuál plasmaste el desarrollo de la prueba.
