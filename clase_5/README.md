# CLASE 05

## Apuntadores

### Apuntadores dinámicos

> HEAD ->

> HEAD^2 -> vuelve el apuntador HEAD a dos commits atrás 

# Apuntadores estáticos

> branches
> tags
> stasjes

# Git TAG

```sh
git tab -a v1.0.0 -m "Versiuón 1.0.0" # -a anotado | -m mensaje
```

# Crear TAG en un commit específico

```sh
git tab -a v1.0.0 <HASH> -m "Versiuón 1.0.0" # -a anotado -| m mensaje
```

# Ver detalles de los tags

```sh
git show <HASH> / <TAG>
```

# Lstar los tags

```sh
git tag
```

# Borrar tags

```sh
git tag -d <nombre-tag>
```

# Subir al remoto un tag

```sh
git push origin <nombre-tag>
```

# Subir todos los tags (no recomndable)

```sh
git push --tags
```

## Actualizar FORK
> Teniendo el fork entre mis repositorios

```sh
git remote add upstream <url-repo-remnto-original>
```

```sh
git pull upstream <rama> # Baja a mi repo los cambios que tenga el original
```

# GIT RESET (repaso)

```sh
git reset --mixed 
```

```sh
git reset HEAD^3 # Elimina los últimos 3 commits
```

# GIT REFLOG

## Muestra un log cde las referencias de todo lo que fue ocuriiendo en el repo en orden cronológico.

```sh
git reflog
```

## GIT STASH

> Área temporal que guarda lo que tengo en el working directory. Trabaja como si fuera una pila. 

# No se suben al remoto. Se puede consultar de manera local.

```sh
git stash # guarda la información en un espacio temporal
```

```sh
git stash list # listar los stash, muestra la pila
```

# Recupera el stash al working directory y si no hay conflicto  lo saca de la pila. Si hay conflicto lo deja.

```sh
git stash pop
```

# Para borrar stash (el último agregado)

```sh
git stash drop
```

# Crear rama a partir del último stash de la pila

```sh
git stash branch <nombre-rama>
```

