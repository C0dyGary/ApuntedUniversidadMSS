# Iniciar un nuevo repositorio en git

## crea un nuevo repositorio en la línea de comando

```bash
git init #<== inicia el repositoryo
echo "write whatever" >> README.md
git add README.md
git commit -m "first commit"
git branch -M "main"
git remote add origin https://github.com/usernick/nameRepository.git #<== url de tu repositorio
git push -u origin "main"
```

## …o inserte un repositorio existente desde la línea de comando

```bash
git remote add origin https://github.com/namenick/namerepository.git #<== url de tu repositorio
git branch -M  "main"
git push -u origin "main"
```

## comandos

comando a utilizar frecuentemente

```bash
git status
git add nombredelarchivo.extecion #achivo.txt
git commint -m "descripciondelamodificacion"
git push -u origin "nombre de la rama" #main
```
