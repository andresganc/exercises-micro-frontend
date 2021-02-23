
# Git fetch

    - Git fetch trae los cambios del repositorio remoto al repositorio local pero no los copia en los archivos propios 
        hasta que no se haga un merge

        $ git fetch origin main

    - Despues necesitaria hacer un merge para unir y solucionar los conflictos de versiones si existen

        $ git merge

    
    - Pero exixte un comando que unifica el fetch y el merge: Que es el PULL

        $ git pull origin main 
