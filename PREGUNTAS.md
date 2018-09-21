# Ejercicio 1
Capacitación: Git, bash y docker
Integrantes:
- [Erika Tinoco]
- [Ronald Cutisaca]
- [Scrum Master]
1. ¿Qué es y para qué sirve GIT?
	Es un sistema de control de versiones, sirve para poder trabajar en un mismo proyecto de forma colaborativa.
2. ¿Que es Github o bitbucket?
	Son plataformas que permiten a los desarrolladores administrar las versiones de un proyecto.
3. ¿Qué es y para qué sirve el SSH?
	SSH es un protocolo de encriptación que facilita la comunicación entre dos sistemas. Sirve para poder comunicar estos sistemas de forma segura.
4. ¿Que pasa si cambio de PC? ¿Tendré que generar el SSH nuevamente?¿Por qué?
	Si cambio de PC es necesario generar otro SSH key ya que este, está almacenado en la PC.
5. ¿Qué es markdown? ¿Para qué sirve?
	Markdown es la sintaxis que se usa para dar formato a un texto plano. Sirve para darle estilos a archivos como este README. 
6. ¿Cómo inicializo y configuro un proyecto de git?
	Para inicializar un proyecto ingreso:
	git init
	Para configurarlo:
	git config

¿Porqué es necesario crear un contenedor con esta bandera -it ? ¿Qué pasa si no le pongo -it?

Es necesario para poder interactuar con el contenedor y ejecutar procesos dentro del mismo. Si no lo incluyo, no permitiría interactuar con el contenedor, sino que se ejecutaría en background los procesos que se establezcan.

¿Para qué sirve ejecutar el comando bash al ejecutar una imagen?

Para poder interactuar con la interfaz por defecto de un contenedor.

 ¿Cuál es la diferencia entre docker ps y docker ps -a?

 El docker ps lista los contenedores que están activos, mientras que con ps -a podemos ver todos los que existen.
