
## Crear llaves SSH

    1. El comando genera una llave publica y otra privada en la carpeta personal .ssh

        $ ssh-keygen -t rsa -b 4096 -C "andresganc@gmail.com"


    2. Debe verificar que tendo ssh corriendo

        $ eval $(sshagent -s)
            answer: Agent pid 4724

    3. Agrego la llave privada al sistema ssh local (Propio)

        $ ssh-add /home/andres/.ssh/id_rsa
            answer: identity added



ssh://git-codecommit.us-east-2.amazonaws.com/v1/repos/nc-components-react
