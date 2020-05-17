# Gestion
## **Operaciones básicas de adminitración de repositorios**
  
1- ***Conceptos básicos***
  
 - **Repositorio**: Es un espacio donde se almacenan distintas cosas. Se puede guardar material fisico o simbólico, pero en este caso se almacena información digital.  
   
- **Git**: Gestiona el repositorio y añade datos dentro del repositorio trabajado. Es facil de usar y permite multiples flujos de trabajo,
    
2- ***Procedimiento***
  + Una vez creado el repositorio, copiamos la dirección de nuestro repositorio, esta se encuentra en la parte superior, en *"clone or download"*. Copiamos la dirección https://github.com/Catalinahdez17/Gestion.git: e ingresamos a git y utilizamos el comando `git clone`seguido del enlace.

3- ***Configuración de usuario y correo***
- `git config --global user.name "Catalinahdez17"`

- `git config --global user.email catalinahdez1246@gmail.com`  

4- ***Creación de carpetas***
+ `mkdir Gestión`
+  `cd Gestion/`

***Archivo de texto***
+  `vi index.txt` Allí editamos el archivo con "a", guardamos los cambios con :w despues de esto salimos con :wq

* En la misma carpeta Gestión creamos un archivo de texto INDEX, y una carpeta llamada CH y dentro de esta un archivo de texto llamado CH.

**creacion de carpeta CH**
- `mkdir CH`
-  `cd CH/`
-  `vi CH.txt`
 
Salimos de esta carpeta con  el comando cd ..

volvemos a quedar en la carpeta Gestion y alli se ejecutamos los siguiente comandos 

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
    
 - `mkdir` : Se crea una carpeta 
 
 - `cd Ruta del proyecto/` : Se ingresa a la carpeta o ruta establecida
 
 - `ls`: Lista todos los archivos que se encuentran dentro de la ruta
 
 - `git add -A` : Agregar archivos que se van a agregar a nuestro repositorio 
 
 ![alt text](https://github.com/Catalinahdez17/Gestion/blob/master/Git%20add.PNG)

-  `git status` : Permite ver los archivos que seran agregados al repositorio

 ![alt text](https://github.com/Catalinahdez17/Gestion/blob/master/git%20status.PNG)

-  `git commit -m "Commit 1" ` : Guardar copia local de los cambios que se hicieron en el repositorio

![alt text](https://github.com/Catalinahdez17/Gestion/blob/master/git%20commit%201.PNG)

-  `git log` : Ver los commits que se han hecho recientemente 

![alt text](https://github.com/Catalinahdez17/Gestion/blob/master/git%20log.PNG)

-  `git push ` : Subir cambios al repostorio

![alt text](https://github.com/Catalinahdez17/Gestion/blob/master/git%20push.PNG)

-  `git pull` : Descargar los cambios recientes que se le han hechos al repositorio



