
### Branch - Ramas

<br>

<img src="../img/git-branch.jpg">

<br><br>

    - Las ramas se pueden usar para hacer forks de una version en cualquier punto del repositorio

    - Tambien se pueden usar las ramas para que un equipo o dev trabaje en una parte del projecto y otro equipo en otra parte
        y despues juntar estas ramas en una sola.

    - Ver las ramas existentes

        $ git branch

    - Crear una rama nueva

        - Al crear una rama nueva inicial mente va a mostrar que el head esta en las dos ramas tanto en el main como en la nueva rama. 

        $ git branch dev-layout


    - Para cambiar de rama uso

        $ git checkout dev-layout


    - Push de la rama nueva

        $ git push origin dev-layout
        
    
    - Mostrar ramas con comentarios

        $ git show-branch


    - Mostrar ramas con comentarios y mas detalles

        $ git show-branch --all

