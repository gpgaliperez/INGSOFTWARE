# INGSOFTWARE
3) ¿Cómo podemos documentar con git? 
Podemos documentar mediante readme.md

a) Realizar un readme para el código subido. ¿Qué cosas podrían? Versionar el README en el repositorio.
Aunque no exista un formato estandar, es recomendable incluir:
  -Descripción y contexto: Descripción de las funcionalidades, el contexto donde fue desarrollado y los problemas de desarrollo que ayudó a resolver.

  -Guía de usuario: Paso a paso dirigido al usuario final sobre cómo empezar a usar la herramienta digital. Si esta información es demasiado extensa, puede ir en un documento aparte, pero es una buena práctica nombrarlo en la documentación.

  -Guía de instalación: Instrucciones de instalación para reutilizar y configurar la herramienta digital. Esta sección está dirigida a desarrolladores. Se deben especificar:

       +Los requisitos del sistema operativo para la compilación (versiones específicas de librerías, software de gestión de paquetes y dependencias, SDKs y compiladores, etc.).

       +Las dependencias propias del proyecto, tanto externas como internas (orden de compilación de sub-módulos, configuración de ubicación de librerías dinámicas, etc.).
  
       +Pasos específicos para la compilación del código fuente y ejecución de tests unitarios en caso de que el proyecto disponga de ellos.

  -Autores Sección para dar créditos a los colaboradores de la herramienta.

  -Licencia para el código de la herramienta: Permisos que se otorgan a terceros para reutilizar la herramienta digital. Debe especificar el tipo de licencia y hacer referencia al archivo license.txt o licencia.txt con el contenido de la licencia. 


b) Si un externo realiza una modificación. Les gustaría que complete cosas en el PR para entender el cambio. 
¿Qué datos le pediría?, ¿Qué nos ofrece GitHub para ayudarnos con esto? 
Los PR pueden ser revisionados por otros colaboradores del repositorio, el desarrollador puede dejar mencionar los cambios que ha hecho, comentar sobre las nuevas funcionalidades, ramas creadas y las soluciones implementadas para resolver ciertas tareas. Estos colaboradores pueden revisionar o dar el visto bueno para que el PR se realice, o de lo contrario, realizar los cambios necesarios para evitar posibles conflictos, inclusive pueden dejar preguntas dirigidas al creador del PR sobre ciertas particularidades.
Github nos brinda la posibilidad de realizar estos comentarios, para facilitar la comunicación entre colaboradores. Además nos permite crear una plantilla para los PR e implementarla de forma que los colaboradores la usen por defecto (https://docs.github.com/en/free-pro-team@latest/github/building-a-strong-community/creating-a-pull-request-template-for-your-repository).
