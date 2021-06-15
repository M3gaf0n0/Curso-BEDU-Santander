## Iniciar proyecto de git

git init

## Preparar archivos para commit

git add .

_Así se agregan todos los archivos modificados_

## Crear commit con descripcion

git commit -m "MENSAJE"

## Agregar remoto _solo la primera vez_

git remote add origin url

## Enviar commit al servidor

git push -u origin branch

## Clonar remoto

git clone server

## Crear nueva branch

git checkout -b nombreBranch

## Cambiar branch

git checkout nombreBranch

## Eliminar branch

git branch -d nombreBranch

## Actualizar

git pull

## Fusionar

git merge nombreBranch

## Conflictos

git add filename

## Comparar branch

git diff source-branch target_branch

## Estado

git status

# Log

git log

## Descartar

git checkout - filename
git fetch origin
git reset -hard origin/master
