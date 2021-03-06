# Gestion
# **Operaciones básicas de administración de repositorios**

## ***Para que sirve el repositorio en github***

- GitHub aloja tu repositorio de código y te brinda herramientas muy útiles para el trabajo en equipo, dentro de un proyecto.

- Además de eso, puedes contribuir a mejorar el software de los demás. Para poder alcanzar esta meta, GitHub provee de funcionalidades para hacer un fork y solicitar pulls.

- Realizar un fork es simplemente clonar un repositorio ajeno (genera una copia en tu cuenta), para eliminar algún bug o modificar cosas de él. Una vez realizadas tus modificaciones puedes enviar un pull al dueño del proyecto. Éste podrá analizar los cambios que has realizado fácilmente, y si considera interesante tu contribución, adjuntarlo con el repositorio original.
  
1- ***Conceptos básicos***
  
 - **Repositorio**: Es un espacio donde se almacenan distintas cosas. Se puede guardar material fisico o simbólico, pero en este caso se almacena información digital.  
   
- **Git**: Gestiona el repositorio y añade datos dentro del repositorio trabajado. Es facil de usar y permite multiples flujos de trabajo.
  
2- ***Procedimiento***
  + Una vez creado el repositorio, copiamos la dirección de nuestro repositorio, esta se encuentra en la parte superior, en *"clone or download"*. Copiamos la dirección https://github.com/Catalinahdez17/Gestion.git: e ingresamos a git y utilizamos el comando `git clone`seguido del enlace.

3- ***Configuración de usuario y correo***
- `git config --global user.name "Catalinahdez17"`

- `git config --global user.email catalinahdez1246@gmail.com`  

4- ***Creación de carpetas***
+ `mkdir Gestion`
+  `cd Gestion/`

***Archivo de texto***
+  `vi index.txt` Allí editamos el archivo con "a", guardamos los cambios con :w despues de esto salimos con :wq

* En la misma carpeta Gestión creamos un archivo de texto INDEX, y una carpeta llamada CH y dentro de esta un archivo de texto llamado CH.

***Creación de carpeta CH***
- `mkdir CH`
-  `cd CH/`
-  `vi CH.txt`
 
Salimos de esta carpeta con  el comando `cd ..`

volvemos a quedar en la carpeta Gestion y allí ejecutamos los siguientes comandos 

- `git add -A`
- `git status`
- `git commit -m "Commit 1"`
- `git log`
- `git push`
- `git pull`

5- ***Resumen comandos empleados***
   
 - `git clone`: Clona el repositorio en X dirección, en este caso en la ruta C:/Users/Angelica/Documents/GITHUB/
 
 ![alt text](https://github.com/Catalinahdez17/Gestion/blob/master/git%20clone.PNG)
   
 - `git config --global user.name` y `git config --global user.email` : Estos son parametros necesarios globalmente 
 
 ![alt text](https://github.com/Catalinahdez17/Gestion/blob/master/GIT%20GLOBAL.PNG)
    
 - `mkdir` : Se crea una carpeta 
 
 ![alt text](https://github.com/Catalinahdez17/Gestion/blob/master/Mkdir.PNG)
 
 - `cd Ruta del proyecto/` : Se ingresa a la carpeta o ruta establecida
 
 ![alt text](https://github.com/Catalinahdez17/Gestion/blob/master/CD.PNG)
 
 - `ls`: Lista todos los archivos que se encuentran dentro de la ruta
 ![alt text](https://github.com/Catalinahdez17/Gestion/blob/master/ls.PNG)
 
 - `git add -A` : Agregar archivos que se van a agregar a nuestro repositorio 
 
 ![alt text](https://github.com/Catalinahdez17/Gestion/blob/master/Git%20add.PNG)

-  `git status` : Permite ver los archivos que seran agregados al repositorio

 ![alt text](https://github.com/Catalinahdez17/Gestion/blob/master/git%20status.PNG)

-  `git commit -m "Commit 1" ` : Guardar copia local de los cambios que se hicieron en el repositorio

![alt text](https://github.com/Catalinahdez17/Gestion/blob/master/Git%20commit%20si.PNG)

-  `git log` : Ver los commits que se han hecho recientemente 

![alt text](https://github.com/Catalinahdez17/Gestion/blob/master/git%20log.PNG)

-  `git push ` : Subir cambios al repostorio

![alt text](https://github.com/Catalinahdez17/Gestion/blob/master/git%20push.PNG)

-  `git pull` : Descargar los cambios recientes que se le han hechos al repositorio

6- ***Verificación de carpetas***

  Una vez se halla empleado el comando `git push `, es posible verificar que las carpetas creadas se hayan subido exitosamente al repositorio "Gestion", como se muestra a continuación 

![alt text](https://github.com/Catalinahdez17/Gestion/blob/master/ch.PNG)
![alt text](https://github.com/Catalinahdez17/Gestion/blob/master/index.PNG)

7- ***Comandos mas utilizados en github***
-	**git help** Muestra una lista con los comandos más utilizados en GIT.

-	**git init** Podemos ejecutar ese comando para crear localmente un repositorio con GIT y así utilizar todo el funcionamiento que GIT ofrece
-	**git add + path** Agrega al repositorio los archivos que indiquemos.
-	**git checkout –b** Crea un nuevo branch y automáticamente GIT se cambia al branch creado, clonando el branch desde donde ejecutamos el comando.
-	**git branch** Nos muestra una lista de los branches que existen en nuestro repositorio.
-	**git checkout** Nombre de branch Sirve para moverse entre branches, en este caso vamos al branch que indicamos en el comando.
-	**git merge** Nombre de branch Hace un merge entre dos branches, en este caso la dirección del merge sería entre el branch que indiquemos en el comando, y el branch donde estemos ubicados.
-	**git push origin** Nombre de branch  Luego de que hicimos un git commit, si estamos trabajando remotamente, este comando va a subir los archivos al repositorio remoto, específicamente al branch que indiquemos.
-	**git pull origin** Nombre de branch  Hace una actualización en nuestro branch local, desde un branch remoto que indicamos en el comando.




