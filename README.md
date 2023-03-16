# DESAFIO - EVALUACIÓN HTML - CSS - HITGUB
## Realizado por: Claudia Pirela - 15-03-2023

# RECORDAR COMANDOS PARA GIT
Para iniciar en git
```bash
git init
```
Para agregar todos los cambios
```bash
git add .
git add --all
```
Usar el commit con el git add todo en uno
Con archivos ya creados
```bash
git commit -am "titulo del commit
```
Para Regresar a estado normal del último commit (DESHACER)
```bash
git reset .
```
Para reconstruir todo los archivos 
y modificaciones sobre el último commit.
```bash
git checkout --
```
Para conocer cuantos commit se han realizado.
```bash
git log
```
Para cambiar el nombre del último nombre, 
pulsar la letra "w" y la letra "a" para iniciar a modificar, 
para guardar ESC y luego wq! y enter
```bash
git commit --amend
```
Para crear una rama.
```bash
git branch nombre_rama
```
Para crear y dirigirme rápidamente a la nueva rama.
```bash
git chekout -b nombre_nueva_rama
```
Para ver todo el listado de la rama.
```bash
git branch
```
Para eliminar una rama especifica.
```bash
git branch -d nombre_rama_especifica
```
Para cambiarse de rama.
```bash
git checkout
```
# RECORDAR COMANDOS PARA GITHUB
Para crear el repositorio remoto de GitHub
Recomendación: Copiar el link cuando crea nuevo repositorio
desde el GitHub y pegar.
```bash
git remote ruta_del_gitHub
```
Para subir a GitHub.
```bash
git push -u origin rama_a_subir
```
Para conocer si hay actualiaciones en el 
repositorio de GitHub 
```bash
git fetch
```
Para descargar todas las actualizaciones pero especificamente de una rama due deseas.
Recomendación: Ubicarse en la rama que desea descargar los cambios.
```bash
git pull
```
# CONFIGURACIÓN DE GIT
Para VER LA VERSIÓN DE GIT 
```bash
git --version
```
Para configurar nuestro nombre 
```bash
git config -- global user.name "tu_nombre"
```
Para configurar nuestro correo
Recomendación: Usar el mismo correo de GitHub
```bash
git config -- global user.email "tu_email"
```

