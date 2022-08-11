
### Git Remote
- Git remote lo usamos pàra saber si el proyecto esta conectado a un repositorio remoto.

        
        $ git remote
            - Muestra la conexion remota (Origin)


        $ git remote -v
            - Muestra la conexion remota con el fetch y el push


        $ git remote show origin
            - Muestra la conexion remota con el fetch y el push y la Rama (Branch)

<br>

### ENLASAR PROYECTO LOCAL A REPOSITORIO REMOTO

#### 1. Create project si no se tiene (Opcional)
    $ git init

    o

    $ npx create-react-app my-project

    o 
    
    $ npx create-next-app my-project

    o

    $ expo init my-project


#### 2. Links project => Repository
    $ git remote add origin URL


#### 3. Opcional si se necesita eliminar por si se cometio algun error (Opcional)
    $ git remote remove origin



#### 4. Comprobar si se hizo el enlace correctamente
    $ git remote
        Debe aparecer origin

    o 

    $ git remote -v
        Para mas detalles


#### 5.1 Si no hay rama y Readme.md inicial en el repositorio (AWS)

    $ git push origin master

    o 

    $ git push origin main


#### 5.2 Areglar conflicto si hay rama y Readme.md creada (Github)

    $ git pull 

    o 

    $ git pull origin main --allow-unrelated-histories




    

