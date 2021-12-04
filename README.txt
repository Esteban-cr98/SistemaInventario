Este proyecto se desarrolló utilizando la versión "Open JDK 11" de Java.

Para la instalación del aplicativo solución al probema planteado, se deben seguir los siguientes pasos:

1- Descargar los archivos incluídos en la actual ruta de GIT.

2- Utilizar un gestor de base de datos Mysql para importar el archivo "konectadb.SQL" el cual crea tanto la estructura de la base de datos, como los datos que esta contiene.

3- Existen dos formas de ejecutar el aplicativo: 
3.1- Utilizando el archivo "PruebaKonecta.jar" se puede hacer la ejecución localmente siempre y cuando se cuente con un JRE de Java. Adicionalmente se debe asegurar que el archivo "application.properties" esté en la misma carpeta que el archivo anteriormente mencionado. Cumpliendo estas condiciones, solo basta con dar docle click al archivo .jar y este se ejecutará en la ruta: "http://localhost:8080/listar".

3.2- Utilizando el archivo "PruebaKonecta.war" y disponiendo de un servidor de aplicaciones (tomcat, glassfish, etc) se puede hacer el despliegue en cualquier servidor (O incluso localmente). Solo debe asegurarse que la base de datos esté corriendo en el mismo servidor.