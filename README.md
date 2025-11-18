# Readme.md
Planificación de un proyecto (ingeniería de software)
Hemos elegido el modelo en v 
Esta metodología resulta adecuada para proyectos donde los requisitos están bastante claros desde el principio y no se espera que cambien demasiado a lo largo del desarrollo. El cliente ya sabe lo que necesita y su idea es estable, por lo que no hace falta una metodología flexible como las ágiles.

  Especificación de requisitos
Se recoge lo que el cliente quiere y se define claramente qué debe hacer el sistema.
  Análisis de requisitos
Se estudian y organizan los requisitos para asegurarse de que son realizables y están bien entendidos.
  Diseño de la arquitectura
Se diseña la estructura general del sistema y cómo se relacionarán sus partes.
  Diseño de módulos
Se define el funcionamiento detallado de cada componente o módulo.
  Programación
Se escribe el código de todos los módulos siguiendo el diseño previo.
  Pruebas unitarias
Se comprueba que cada módulo funciona correctamente por separado.
  Pruebas de integración
Se prueba que los módulos funcionan bien juntos y que se comunican sin errores.
  Pruebas de sistema
Se verifica el sistema completo para comprobar que cumple con los requisitos técnicos.
  Pruebas de aceptación
El cliente valida que el sistema cumple lo que pidió y autoriza la entrega final.

Roles
Si el proyecto se realiza de manera individual, una sola persona asume todos los roles: analista, diseñador, programador y probador.
Si hubiera varios miembros, se podrían dividir en analista de requisitos, diseñador técnico, programadores y responsables de pruebas.

Reuniones y productos
Aunque la metodología en V no se basa en reuniones tan frecuentes como las metodologías ágiles, se realizan reuniones al inicio de cada fase para revisar documentación y asegurar que todo esté correctamente definido antes de avanzar. Los productos más importantes son el documento de requisitos, los diagramas de diseño, el código fuente y los informes de pruebas.

Requisitos funcionales
1. El usuario podrá crear una reserva indicando fecha, hora y datos básicos.
2. El sistema evitará reservas duplicadas o solapadas.
3. El administrador podrá ver un calendario con todas las reservas.
4. El administrador podrá modificar y eliminar reservas.
5. El sistema guardará las reservas en una base de datos.
6. El usuario recibirá un mensaje de confirmación de la reserva.

Requisitos no funcionales
1. La interfaz será sencilla e intuitiva.
2. El sistema deberá ser estable y funcionar sin errores frecuentes.
3. La aplicación debe cargar en menos de dos segundos en condiciones normales.
4. Se deberá proteger la base de datos frente a accesos no autorizados.
5. El diseño debe poder ampliarse en caso de añadir nuevas funciones.

   Control de versiones
Git y GitHub para mantener copias del proyecto, revisar cambios y almacenar versiones anteriores.

IDE
Visual Studio Code como entorno principal de desarrollo.

Lenguaje de programación
JavaScript con Node.js para el backend y HTML, CSS y JavaScript para el frontend. Se trata de un conjunto de tecnologías accesible y adecuado para un proyecto de este tipo.

Base de datos
SQLite si se busca simplicidad o MySQL si se quiere un sistema más completo.

Documentación
Markdown para los documentos del repositorio.
Draw.io para diagramas del sistema.

Pruebas
Postman para probar rutas del servidor.
Jest o Mocha para realizar pruebas unitarias en el backend.

Fases en las que se usan
Documentación: análisis y diseño.
IDE y lenguajes: implementación.
GitHub: durante todo el proyecto.
Herramientas de pruebas: desde las pruebas unitarias hasta las de validación.

El proyecto comienza con la reunión con el cliente y el análisis detallado de los requisitos. A continuación se diseña la arquitectura general del sistema y después se elabora el diseño detallado de cada módulo. Cuando toda la planificación está completa, se inicia la implementación del código, siguiendo lo planificado en el diseño.

Después se realizan las pruebas unitarias, integración y validación, asegurando que cada parte funciona por separado, que se integra correctamente con las demás y que el sistema cumple lo que el cliente pidió. Finalmente, se entrega el producto y se inicia la fase de mantenimiento, donde se corrigen posibles errores y se aplican mejoras si el cliente lo solicita.
