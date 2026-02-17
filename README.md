# DOSW_LAB4_InicialJuanJuanKarol
Repositorio del lab 4 de DOSW :)
--
## 1. Preguntas

### a. ¿Qué es un arquetipo (Archetype) en Maven?  
En Maven, un arquetipo es considerado una plantilla o molde de proyecto que define un punto de partida para generar nuevos proyectos con una
estructura predefinida. Los arquetipos son diferenciables ya que contienen archivos de:  
  1. Configuración  
  2. Estructura directorios  
  3. Dependencias básicas


Los cuales permiten a los desarrolladores iniciar un proyecto sin la necesidad de configurar todo desde 0.
Su estructura inicial generalmente incluye lo siguiente:
  1. Estructura de directorios estándar.
  2. Archivo pom.xml preconfigurado.
  3. Clases de ejemplo.
  4. Recursos y archivos de prueba.



### b. ¿Para qué sirve el arquetipo maven-archetype-quickstart?  
Su utilidad es para crear de manera rápida la estructura básica de un proyecto Java con Maven, es una plantilla ya lista para usar.


### c. ¿Cuál es el comando con el cual se puede crear un proyecto basado en un arquetipo maven?  
Tenemos 2 formas de crear un proyecto basado en un arquetipo Maven:  
  1. mvn archetype:generate
     - Este comando al ejecutarlo funciona de modo interactivo, lo que quiere decir que Maven solicitará información sobre:
     -   El arquetipo a utilizar
     -   Group ID del proyecto
     -   Artifact ID del proyecto
     -   Version
     -   Paquete Base  
  2. mvn archetype:generate -DgroupId=com.ejemplo -DartifactId=mi-proyecto -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false
     -  Este comando al ejecutarlo funciona de manera no interactiva. Se encarga de crear el proyecto sin solicitar información adicional, utiliza únicamente los parametros especificados
       en la linea de comando.

### d. ¿Qué es un pull request en GitHub?  
Es la solicitud para subir fragmentos adelantados del trabajo realizado de manera local en mi equipo, permite comparar cambios y seleccionar cuales conservar.  

### e. ¿Cómo se crea un pull request en GitHub?
Hay dos maneras, una gráfica GUI y otra por línea de comandos  
  1. Por GUI es desde el sitio web de GitHub sen el boton de pull request, luego aparecerá una pestaña donde debe escoger la base y con lo que desea comparar.
  2. En linea de comando se utiliza automaticamente al hacer push o en su defecto con git merge.

  ### f. ¿Cómo se aprueba un pull request en GitHub?
  Se puede desde git bash en nano aparecerán los conflitctos o de manera GUI en el sitio web, así se verifica lo que se va a cambiar, se solucionan errores y se hace el merge.


  ### BIBLIOGRAFÍA

Apache Maven Project. (n.d.). Introduction to archetypes. Apache Software Foundation. https://maven.apache.org/guides/introduction/introduction-to-archetypes.html  

Apache Maven Project. (n.d.). Maven archetype quickstart. Apache Software Foundation. https://maven.apache.org/archetypes/maven-archetype-quickstart/  

Apache Maven Project. (n.d.). What is Maven? Apache Software Foundation. https://maven.apache.org/what-is-maven.html  

JUnit Team. (n.d.). JUnit 5 user guide. https://junit.org/junit5/docs/current/user-guide/  

VMware, Inc. (n.d.). Spring Boot reference documentation. https://docs.spring.io/spring-boot/docs/current/reference/html/  

Chacon, S., & Straub, B. (2014). Pro Git (2nd ed.). Apress. https://git-scm.com/book/en/v2  

GitHub, Inc. (n.d.). About pull requests. https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/about-pull-requests  

GitLab B.V. (n.d.). Merge requests. https://docs.gitlab.com/ee/user/project/merge_requests/  

Atlassian. (n.d.). Pull request tutorial. https://www.atlassian.com/git/tutorials/making-a-pull-request  
