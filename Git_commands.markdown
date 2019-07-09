# Comandos usados en la consola de git

### First Time Git Configuration

* Configura tu nombre dentro del repositorio de Git - `git config --global user.name "<Your-Full-Name>"`
* Configura tu correo electronico - `git config --global user.email "<your-email-address>"`
* Se asegura de que la salida de Git tenga color - `git config --global color.ui auto`
* Muestra el estado original en un conflicto - `git config --global merge.conflictstyle diff3` `git config --list`


**Git & Code Editor**
* Atom Editor Setup - `git config --global core.editor "atom --wait"`
* VSCode Setup - `git config --global core.editor "code --wait"`

### Basic Commands
`ls` - used to list files and directories
`mkdir` - used to create a new directory
`cd` - used to change directories
`rm` - used to remove files and directories

### Git Ignore

En el archivo **.gitignore** se agregan los archivos que se quieren ignorar para no ser seguidos en el repositorio principal. Se agregan al repositorio.

### Basic Commands
* `git init` - Crea un nuevo repositorio en una direccion espesificada 
* `git clone` - Clona / Copia un repositorio existente a tu repositorio
* `git status` - Muestra el estado en el que se encuentran los archivos del proyecto dentro 
del repositorio cuenta con atributos 
* `git log` - Muestra la informacion de los commits hechos con anterioridad, despliega toda
la informacion, quien hizo el commit, correo, cambios realizados, en que archivos y 
lienas de codigo modificadas. Presionar Q para salir
* `git log --oneline` - muestra los cambios hechos en el repositorio de manera resumida
* `git log --stat` - Se utiliza para mostrar los archivos que se han cambiado en el commit, de la misma forma el numero de lineas que se han modificado, agregado o borrado.
* `git log -p` - Muestra los cambios hechos de los archivos modificados en los commits
* `git show` - Muestra la informacion de un de un solo commit en especifico utilizando un SHA como argumento
* `git add` - El comando es usado para mover archivos del Working Directory hacia el Staging Index. Se puede usar el atajo `$ git add .` para organizar los archivos restantes.
* `git commit` - Guarda los cambios en los archivos modificados y agregados en el Staging Index en el repositorio principal
* `git diff` - El comando se puede usar para ver los cambios que se han realizado pero que aún no se le ha hecho commit.
* `git tag -a` - Agrega un tag a un commit en especifico 
* `git tag -d` - Borra un tag a un commit en especifico 
* `git log --decorategit tag` - Agrega un tag a un commit en especifico 
* `git branch` El comando se utiliza para interactuar con las diferentes branches, se puede asignar un nombre colocandolo seguido del comando para crear un nuevo branch
* `git checkout` Sirve para cambiar de branch, se coloca el nombre seguido del comando
* `git merge` une los diferentes branchs, se pueden unir uno o varios branchs
* `git commit --amend` - Te permite modificar o cambiar el mensaje de un commit hecho anteriormente
* `git revert` - revierte lo que habia hecho en el commmit anterior, se tiene que asignar un SHA
* `git reset` - Este comando se utiliza para borrar commits, tiene tres parametros `--mixed` manda los archivos al directorio de trabajo, `--soft` manda los archivos al staging index. `--hard` los manda los arvhicos directo al directorio trash



