# Extensiones

* Material Icons Theme

* GitLens

# Workflow

1. git status
2. git add <nombre de archivo>
3. gi commit -m "mensjae del commit"
4. git push para subir al remoto

# Configurar remoto

1. git remote add origin http://github/joseGuaymas....
2. git push -u origin main

# Ayuda git en local

1. git --help commit
2. git --help status

# Para comparar los cambios en el WD con respecto ultimo commit del repo 
1. git diff 

## Git log

# git log resumido

```sh
git log --oneline
```
# git log especifico (ultimas dos lineas)

```sh
git log --oneline -2
```

# Commits entre fechas

```sh
git log --since="2021-05-01"
git log --before="2021-05-01"
git log --after="2021-05-01"
```

## Ramas (BRANCH)

# Crear rama (crea rama nombrada dev)


```sh
git branch dev 
``` 

# Para posicionarse en una rama (se mueve a la rama dev)

```sh
git switch dev
○6```

# Lista las ramas

```sh
git branch 
```

# Modificar, agregar archivos no incluidos en el ultimo commit

```sh
git commit --amend
```

# Fusionomos dos ramas

```sh
git merge dev
```