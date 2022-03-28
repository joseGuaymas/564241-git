# Clonar un repo de git

```sh
git clone <url-repo>
```
## REMOTOS 

# Muestra el alias del remoto que tengo en el repo local

```sh
git remote 
```
# Muestra de forma verbosa mas info de los remotos

```sh
git remote -v
```
# 
# GIT ADD Selecionar qué agregar a los commits 

> Interativamente va mostrando que chunk (hunk) quiero agregar al stage

```sh
git add -p # la flag -p es path
```

> Comandos
1. y: si
2. n: no
3. s: split
# Para colaborar con otro proyecto


1. Realizar un fork de otro proyecto
2. Bajo desde mi cuenta el proyecto localmente
3. Hago cambio en el local, lo subo a mi repo forked
4. Finalmente hago un pull request

# Git BRANCH ramas continuacion clase_02

# Borrar rama

```sh
git branch -d <rama_a_borrar>
```

# FORZAR Borrado de la rama

```sh
git branch -D <rama_a_borrar>
```
# Crear la rama y moverme a la rama creada

```sh
git checkout -b <rama_nueva>
```
## MERGE 

# Actualizar rama actual, importar los cambios de otra rama 

```sh
git merge <nombre_rama>
```

