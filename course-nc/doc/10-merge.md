
### Merge - Unir

    - El merge se usa para unir un version con otra version o una rama con otra rama

        $ git merge main

    - Los merge se pueden usar para unir ramas que estuvieron trabajando diferentes equipos o devs

        - Estando en la rama main hago

            $ git merge dev-layout
                - Traeria todo lo de dev-layout hacia main

    - Se puede usar para unir alguna modificacion de emergencia por algun bug encontrado en la rama principal

        1. Se detecta el bug

        2. Se crea una rama nueva ( Normalmente para esto suelen llamarle a la rama hot fix - Solucion en caliente )

        3. Se trabaja en la rama modificando los bugs 

        4. una vez esten corregidos los bugs se hace un merge para unir esas correcciones con el repositorio principal o main


    