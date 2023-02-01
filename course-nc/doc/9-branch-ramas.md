
### Branch - Ramas

<br>

<img src="../img/git-branch.jpg">

<br><br>

    - Las ramas se pueden usar para hacer forks de una version en cualquier punto del repositorio


    - Tambien se pueden usar las ramas para que un equipo o dev trabaje en una parte del projecto y otro equipo en otra parte
        y despues juntar estas ramas en una sola.



    - Ver las ramas existentes

        $ git branch



    - Mostrar todas las ramas

        $ git branch -a

        o 

        $ git branch --all



    - Crear una rama nueva

        - Al crear una rama nueva inicial mente va a mostrar que el head esta en las dos ramas tanto en el main como en la nueva rama. 

        $ git branch dev-layout



    - Para cambiar de rama uso

        $ git checkout dev-layout



    - Push de la rama nueva

        $ git push origin dev-layout



    - Renombrar Rama

        1. $ git checkout <old_name>

        2. $ git branch -m <new_name>

        3. $ git push origin -u <new_name>

        4. $ git push origin --delete <old_name>



    - Eliminar rama

        - Para eliminar una rama de nuestro repositorio local ejecutaremos el siguiente comando:

            $ git branch -d nombre_rama


        -En el caso de que esa rama contenga trabajos sin fusionar, el comando anterior nos devolverá el siguiente error:

        $ git branch -D nombre-rama


        - En el caso de querer eliminar una rama del repositorio remoto, la sintaxis será la siguiente:

            $ $ git push origin :nombre-rama




    - Git branch --all (Podriamos ver ramas creadas por otros equipos de trabajo)

        $ git branch --all

        o 

        $ git branch -a
        
    


    - Mostrar ramas con comentarios

        $ git show-branch




    - Mostrar ramas con comentarios y mas detalles

        $ git show-branch --all

        

