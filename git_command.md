
# inicializar un proyecto/folder git
git init

# status del proyecto
git status

# agrega todos los archivos al stage
git add .

# commit
git commit -m "Commit inicial del proyecto"


# crea vinculo con repositorio remoto
git remote add origin https://github.com/jimene99/creproy.git

# subir cambios a git remoto
git push -u origin master

# para crear llaves ssh
ssh-keygen -t ed25519 -C "myemail@gmail.com"

# para agregar las llaves al agente
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519

# bajar los cambios desde github
git pull origin master

# trae los cambios del github
git fetch origin master

# mezcla los cambios del github
git pull

# subir cambios a git remoto
git push


# edita el archivo de configuracion global de git
git config --global -e

# alias para log
lg = log --oneline --decorate --all --graph
