
### Git Checkout

#### Git Checkout

    - Git checkout me sirve para 2 cosas volver a versiones anteriores o cambiar de ramas

        - Cambiar de rama

            $ git checkout dev-layout

            - Para volver a la rama main

            $ git checkout main

    - Para volver en el tiempo y ver archivos anteriroes 

        - Priemero con git log busco a donde quiero ir, Copio el indice o id de ese commit y lo uso con git checkout  

        - Se agrega el comando git checkout el id del commit y el archivo que quiero volver
            
            $ git chekout 3fd88c8dfb01ac1fcb7b99cd750eee791d6f0ca8 miarchivo.js

        - Podria guardar con add, commit y push ese estado anterior y sobreescribir el actual

        - O regresar al actual con

            $ git checkout master miarchivo.js

