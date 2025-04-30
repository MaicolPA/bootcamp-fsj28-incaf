**Inicializando nuestro repositorio**
git init

**Verificar el estado de los archivos**
git status
git status -s

**Agregando los archivos al repositorio**
git add <nombrearchivo>
git add .
git add -all

**Agregamos los comentarios al repositorio LOCAL y un comentario del cambio**
git commit -m <comentario>

**Subiendo los cambios al repositorio remoto**
git push origin <ramaprincipal>

### Comandos Adicionales
**Configuración de usuario**
git config user.name
git config user.email
git config user.name <usuariogithub>
git config user.email <emailgithub>

**Verificando repositorio remoto**
git remote -v

**agregando repositorio remoto**
git remote add origin <enlacerepositoriogithub>

### Comando sobre ramas

git brach

git branch <nuevarama>

**creando una nueva rama y accediendo**
git checkout -b <nuevarama>

git checkout <rama>