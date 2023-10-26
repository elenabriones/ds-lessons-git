# comandos terminal:
    pwd --> donde estoy?  en que carpeta?
    ls --> que hay dentro de la carpeta
    cd .. --> para ir arriba
    cd #nombrecarpetadondequeremos ir
    python main.py--> para ejecutar el proyecto
    clear -> borra pantalla

GIT is free and open source
    sistema de control de versiones distribuido
    tiene mayor seguridad que pasar codigo por otras vias
    tiene dos environments (entornos)
        local
            Working directory --> la carpeta //para pasar al siguiente estado se hace  add
            Staging Area --> "sala de espera" lo que estamos desarrollando //para pasar al siguiente estado se hace  commit
            Local Repository --> Version grabada mas la modificacion que queremos ver
        remoto
comandos:
    git clone --> copia el codigo entero del repositorio remoto (primera vez)
    git pull --> Descargar el  codigo del repositorio remoto (siguientes veces)
    git branch --> Crea una rama para desarrollar sin cargarnos nada (añadiendo el nombre) y nos permite volver a atras
                --> listamos todas las ramas 
    git checkout --> cambiar de rama, si es con comando de fichero -- main.py  se va a la version del repositorio local
    git status --> nos dice el estado actual
    git revert --> ctl Z
    git add (si se añade " ." se sube todo)
    git commit  -m "comentario" --> se mueve al repositorio --> requiere comentario
    git push --> Poner el codigo a disposicion de 3os
    git merge --> fusionar
    git remote --> añadir informacion del repositorio
    git init --> empezar un proyecto desde cero
Principales respositorios del mercado:
    GitHub
    BitBucket
    GitLab

Problemas Local:
    - Gestion ficheros
    - Gestión librerias (gestion con github)

Git no acepta:
    - ficheros de mas de 101k
        - imagenez
        - datos
        - configuracion (tipo contraseñas)

para no subir datos añadir archivo dentro del proyecto ptincipal el archivo .gitignore
    se le pone la ruta
    se le pone ruta y nombre de archivo
    poniendo estructuras ...


si se hace git add de algo que no se quiere commitear se puede quitar con git restore.....