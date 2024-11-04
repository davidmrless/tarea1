# Introduccion a Git 

## Descripción

El programa que subimos es muy simple, lo unico que hace es imprimir un Hola Git, lo realmente importante de la terea es familiarizarse con los comandos para crear repositorios en GitHub desde la terrminal de GitBash 

## Instrucciones de uso

Para usar el programa deberas de clonar el repositorio desde tu computadora y despues dependiendo de en que editor estes los pasos serán distintos, pero no es distinto a ehecutar cualquier otro programa

## Comandos utilizados

- git config --global user.name "Nombre Usuario"
- git config --global user.email "miEmail@mail.com"
- git init
- git remote add ALIAS URL-GIT-REPOSITORIO-REMOTO
- touch .gitignore
- git add -A
- git commit -m "mensaje del commit"
- git push ALIAS NOMBRE-RAMA
- git status 

## Nostas sobre el archivo .gitignore

el archivo .gitignore es creado para poder ignorar archivos que no son requeridos por el programa, ya sea por las razones que sean, en este caso se ignora el archivo debug.log porque asi se pide en la tarea 

Para ver que el archivo debug.log no se subio antes de agregar subir los archivos con el comando git add es necesario ejecutar el comando git status y verificar que el archivo debug.log no aparezca como tracked