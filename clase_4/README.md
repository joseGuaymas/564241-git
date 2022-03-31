# Clase 4

## Tipos de MERGE

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
