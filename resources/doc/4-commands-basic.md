
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

        - git rm --cached miarchivo.js Elimina los archivos del área de Staging y del próximo commit pero los mantiene en nuestro disco duro.
        $ git rm --cached miarchivo.js

        - git rm --force miarchivo.js Elimina los archivos de Git y del disco duro. Git siempre guarda todo, por lo que podemos acceder al registro de la existencia de los archivos, de modo que podremos recuperarlos si es necesario (pero debemos usar comandos más avanzados).
        $ git rm miarchivo.js



#### Git Diff

    - Ver las diferencias y cambioos que se realizaron

        $ git diff

    - O puedo comparar una modificacion con otra con los id de cada commit

        $ git diff fc39271432e4ad5ba1e63db3843d542bb4b9d598 1eb9969bc55f23f5e22433572ddbec69684f27c3



#### Git Commit

    - El commit comenta la modificacion que se realizo y agrega esas modificaciones al repositorio 

    - Se puede usar git commit solo y no dejar un mensaje (Pero es una mala practica)

        $ git commit

    - Siempre es muy importante dejar un mensaje de cuales fueron las modificaciones que se hicieron. 
    
        $ git commit -m "Mensaje de las modificaciones que se hicieron"

    - Tambien se puede usar el commit con el tag -am que es add y mensaje (Hace las 2 funciones a la vez - No funciona con el commit inicial) 

        $ git commit -am "Ejemplo del commit con el tag am"


#### Git Push 

    - El git push lo que hace es subir los cambios realizados localmente al servidor

    - Con git push origin main o git push origin master (Rama principal antiguamente) : Donde main o master hace referencia a la rama que se quiere hacer el push 
        
        $ git push origin main

        o 

        $ git push origin dev-layout

    

#### Git Log

    - Se pueden ver todo el historial de commit y modificaciones que se han hecho.
    
        $ git log 
            - Para salir usar la letra q (quiet)

    
    - O se pude usar git log --stat se pueden ver los cambios mas detalladamente

        $ git log --stat


    - Mostrar todo el historial de commits

        $ git log --all


    - Mostrar todo el historial de commits con grafico

        $ git log --all --graph 


    - Mostrar todo el historial de commits

        $ git log --all --graph --oneline



#### Crear Alias

    - Se pueden crer alias en lineas de comando que se usen con frecuencia y que sea muy largos
        o dificiles de aprender

        $ alias arbol = "git log --all --graph --oneline"      


    
#### Crear Alias

    - Se pueden crer alias en lineas de comando que se usen con frecuencia y que sea muy largos
        o dificiles de aprender

        $ alias arbol = "git log --all --graph --oneline"       


    
#### GitK

    - Gitk muestra un entorno grafico del repositorio con todo su historial y recorrido

        $ gitk




    