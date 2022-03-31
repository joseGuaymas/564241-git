# Clase 4

## Tipos de MERGE

# Abortar MERGE

```sh
git merge --abort
```

## GIT Alias

```sh
git config --global alias.s "status --short"
git config --global alias.l "log --oneline"
git config --global alias.lg "log --oneline --decorate --all --graph"

```

# Quitar ALIAS

```sh
git config --global alias.set "config --global"
```

# Consultar los alias que tengo configurados

```sh
git config --get --regexp --global alias 
```

# Borrar alias

```sh
git config --global --unset alias.set
```


# Rcuperar archivos borrados

```sh
git restore .
```

```sh
git restore <nombre-archivo>
```

## COMANDOS REMOTE

# Borrar el remoto

```sh
git remote rm <nombre-remoto>
```

# Subir mas de una rama al remoto

```sh
git push origin <nombre-rama-1 nombre-rama-2 nombre-rama3>
``` 

# Listar ramas que estan en el además de listar las locales 

```sh
git branch -av
```
