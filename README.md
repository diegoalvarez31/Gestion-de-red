# Gestion-de-red

## **Operaciones básicas de adminitración de repositorios**

# Para que sirve el repositorio en github

- GitHub aloja tu repositorio de código y te brinda herramientas muy útiles para el trabajo en equipo, dentro de un proyecto.

- Además de eso, puedes contribuir a mejorar el software de los demás. Para poder alcanzar esta meta, GitHub provee de funcionalidades para hacer un fork y solicitar pulls.

- Realizar un fork es simplemente clonar un repositorio ajeno (genera una copia en tu cuenta), para eliminar algún bug o modificar cosas de él. Una vez realizadas tus modificaciones puedes enviar un pull al dueño del proyecto. Éste podrá analizar los cambios que has realizado fácilmente, y si considera interesante tu contribución, adjuntarlo con el repositorio original.
  
1- ***Conceptos básicos***
  
 - **Repositorio**: Es un espacio donde se almacenan distintas cosas. Se puede guardar material fisico o simbólico, pero en este caso se almacena información digital.  
   
- **Git**: Gestiona el repositorio y añade datos dentro del repositorio trabajado. Es facil de usar y permite multiples flujos de trabajo.
  
2- ***Procedimiento***
  + Una vez creado el repositorio, copiamos la dirección de nuestro repositorio, esta se encuentra en la parte superior, en *"clone or download"*. Copiamos la dirección https://github.com/diegoalvarez31/Gestion-de-red.git: e ingresamos a git y utilizamos el comando `git clone`seguido del enlace.

3- ***Configuración de usuario y correo***
- `git config --global user.name "diegoalvarez31"`
- `git config --global user.email diegoalvares2009@hotmail.com`  

4- ***Creación de carpetas***
+ `mkdir Gestion de red`
+  `cd Gestion de red/`

***Archivo de texto***
+  `vi index.txt` Allí editamos el archivo con "a", guardamos los cambios con :w despues de esto salimos con :wq

* En la misma carpeta Gestión creamos un archivo de texto INDEX, y una carpeta llamada RED

**creacion de carpeta RED**
- `mkdir RED`
-  `cd RED/`
 
Salimos de esta carpeta con  el comando `cd ..`

volvemos a quedar en la carpeta Gestion de red y allí ejecutamos los siguientes comandos 

- `git add -A`
- `git status`
- `git commit -m "Commit 1"`
- `git log`
- `git push`
- `git pull`

5- ***Resumen comandos empleados***
   
 - `git clone`: Clona el repositorio en X dirección, en este caso en la ruta C:/GITHUB/
 
 ![alt text](https://github.com/diegoalvarez31/Gestion-de-red/blob/master/SI%20GIT%20CLONE.PNG)
   
 - `git config --global user.name` y `git config --global user.email` : Estos son parametros necesarios globalmente 
 
 ![alt text](https://github.com/diegoalvarez31/Gestion-de-red/blob/master/SI%20GIT%20GLOBAL.PNG)
    
 - `mkdir` : Se crea una carpeta 
 
 - `cd Ruta del proyecto/` : Se ingresa a la carpeta o ruta establecida
 
 - `ls`: Lista todos los archivos que se encuentran dentro de la ruta
 
 ![alt text](https://github.com/diegoalvarez31/Gestion-de-red/blob/master/SI%20LS.PNG)
 
 - `git add -A` : Agregar archivos que se van a agregar a nuestro repositorio 
 
 ![alt text](https://github.com/diegoalvarez31/Gestion-de-red/blob/master/SI%20GIT%20ADD.PNG)

-  `git status` : Permite ver los archivos que seran agregados al repositorio

 ![alt text]

-  `git commit -m "Commit 1" ` : Guardar copia local de los cambios que se hicieron en el repositorio

![alt text](https://github.com/diegoalvarez31/Gestion-de-red/blob/master/SI%20GIT%20COMMIT.PNG)

-  `git log` : Ver los commits que se han hecho recientemente 

![alt text](https://github.com/diegoalvarez31/Gestion-de-red/blob/master/SI%20GIT%20LOG.PNG)

-  `git push ` : Subir cambios al repostorio

![alt text](https://github.com/diegoalvarez31/Gestion-de-red/blob/master/SI%20GIT%20PUSH.PNG)

-  `git pull` : Descargar los cambios recientes que se le han hechos al repositorio


**Comandos mas utilizados en github**
-	**git help** Muestra una lista con los comandos más utilizados en GIT.

-	**git init** Podemos ejecutar ese comando para crear localmente un repositorio con GIT y así utilizar todo el funcionamiento que GIT ofrece
-	**git add + path** Agrega al repositorio los archivos que indiquemos.
-	**git checkout –b** Crea un nuevo branch y automáticamente GIT se cambia al branch creado, clonando el branch desde donde ejecutamos el comando.
-	**git branch** Nos muestra una lista de los branches que existen en nuestro repositorio.
-	**git checkout** Nombre de branch Sirve para moverse entre branches, en este caso vamos al branch que indicamos en el comando.
-	**git merge** Nombre de branch Hace un merge entre dos branches, en este caso la dirección del merge sería entre el branch que indiquemos en el comando, y el branch donde estemos ubicados.
-	**git push origin** Nombre de branch  Luego de que hicimos un git commit, si estamos trabajando remotamente, este comando va a subir los archivos al repositorio remoto, específicamente al branch que indiquemos.
-	**git pull origin** Nombre de branch  Hace una actualización en nuestro branch local, desde un branch remoto que indicamos en el comando.


