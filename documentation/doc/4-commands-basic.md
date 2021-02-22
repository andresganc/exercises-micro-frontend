
### Comandos basicos

<br>

<img src="../img/git-basic-01.png">

<br> <br>

#### Git Status

    - Comando para mirar el estado del repositorio

        $ git status


#### Git add .

    - Agrega los cambios en un archivo historial.txt dentro del staging (Estado temporal)

    - Se pueden agreagar otros archivos 

        $ git add .

    
    - O se pueden eliminar las modificaciones con git rm

        $ git rm miarchivo.js

        $ git rm -cached miarchivo.js



#### Git Diff

    - Ver las diferencias y cambioos que se realizaron

        $ git diff



#### Git Commit

    - El commit comenta la modificacion que se realizo y agrega esas modificaciones al repositorio 

    - Se puede usar git commit solo y no dejar un mensaje (Pero es una mala practica)

        $ git commit

    - Siempre es muy importante dejar un mensaje de cuales fueron las modificaciones que se hicieron. 
    
        $ git commit -m "Mensaje de las modificaciones que se hicieron"



#### Git Push 

    - El git push lo que hace es subir los cambios realizados localmente al servidor

    - Con git push origin main o git push origin master (Rama principal antiguamente) : Donde main o master hace referencia a la rama que se quiere hacer el push 
        
        $ git push origin main

        o 

        $ git push origin master

    

#### Git Log

    - Se pueden ver todo el historial de commit y modificaciones que se han hecho.
    
        $ git log 

    
    - O se pude usar git log --stat se pueden ver los cambios mas detalladamente

        $ git log -stat






    