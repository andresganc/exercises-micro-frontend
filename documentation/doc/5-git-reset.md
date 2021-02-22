

### GIT RESET

    - Git reset vuelve al versiones anteriores del repositorio

    - Existen 2 versiones de git reset. git reset --soft y git reset --hard


#### Git Reset Soft

    - Git reset Soft vuelve a un estado anterior dejando en el staging las modificaciones

        $ git reset --soft 3fd88c8dfb01ac1fcb7b99cd750eee791d6f0ca8



#### Git Reset Hard

    - Git reset Hard vuelve a un estado anterior quitando todas las modificaciones incluso las del staging

        $ git reset --hard 3fd88c8dfb01ac1fcb7b99cd750eee791d6f0ca8