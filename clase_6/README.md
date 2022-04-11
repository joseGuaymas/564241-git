# Clase 06

## GIST 
Permite compartir pedacitos de código (Snipets)
y tener seguimiento de estos.

## GITHUB CLI
Herramienta de consola adicional de Github con más comandos. 
http://cli.github.com

## GIT REBASE

Tenemos que estar parados en la rama destino de donde queremos recivir los cambios.

```sh
git rebase <rama-origen>
```

## REBASE INTERACTIVO

```sh
git rebase -i
```

* Ordenar commits
* Correjir mensajes de lo commits
* Unir commits

# Continuo el rebase

```sh
git rebase --continue
```

### Abortar la misión

```sh
git rebase --abort
```

### Crear submodulo

```sh
git submodule init
```

```sh
git submodule add <url> <nombre-carpeta>
```

### Actualizar submódulo

```sh
git submodule update
```

### Borrar y cambiar nombre archivos desde el bash

```sh
git mv
```

```sh
git rm
```
