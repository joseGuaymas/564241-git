# Extensiones

* Material Icons Theme

* GitLens

# Workflow

1. git status
2. git add <nombre de archivo>
3. gi commit -m "mensjae del commit"
4. git push para subir al remoto

# Configurar remoto

1. git remote add origin http://github/jhoseGuaymas....
2. git push -u origin main

# Ayuda git en local

1. git --help commit
2. git --help status

# Para comparara los cambios con respecto al WD con respecto al repo (ultimo commit)
1. git diff 

# git log

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

# Crear rama

```sh
git branch dev -- crea rama nombrada dev
git switch dev -- se mueve a la rama dev
git branch -- lista las ramas
```

# git commit amend

```sh
modifica, agrega archivos no agregados en el ultimo commit
```

# git merge dev
```sh
fusionomos dos ramas
```