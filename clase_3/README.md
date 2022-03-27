# Clonar un repo de git

```sh
git clone <url-repo>
```

si agrego un "." al final del comando crea la carpeta git en
el directorio que yo quiera (donde haya ubicado la copia del repo ajeno) puede
llevar el nombre que yo elija

# REMOTOS 

```sh
git remote muestra el alias del remoto que tengo en el repo local
```
# muestra de forma verbosa mas info de los remotos

```sh
git remote -v
```
# Selecionar qué agregar a los commits

```sh
git add -p
```

# Para colaborar con otro proyecto

```sh
Realizar un fork de otro proyecto
Bajo desde mi cuenta el proyecto localmente
Hago cambio en el local, lo subo a mi repo forked
Finalmente hago un pull request
```
# Git BRANCH ramas continuacion clase_02

```
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
# MERGE actualizar, importar los cambios de otra rama 

```sh
git merge <nombre_rama>
```