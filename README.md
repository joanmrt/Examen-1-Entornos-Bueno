# EXAMEN ENTORNOS

Nota de Joan para Máximo: No tengo portatil propio y en este PC solo tengo Linux, si se me salta algun "date" puedes comprobar que no esta hecho antes porque en casa uso Windows con PowerShell. Disculpa las moléstias.

## Parte A

![image](https://user-images.githubusercontent.com/74322611/205120436-417f78e4-2e54-4e84-94df-57685a012c7a.png)


Una vez creado el repositorio de github, añadimos el texto de prueba llamado "prueba.txt", commiteamos con el comentario "Primer Commit", lo enlazamos con el repositorio con git remote. Yo como tengo por defecto la rama master he puesto master en vez de main. Podemos comprobar el estado de los commits con git status.

## Parte B

![image](https://user-images.githubusercontent.com/74322611/205120581-f822e31c-2dfd-41e8-bc5d-e52441d1a644.png)

![image](https://user-images.githubusercontent.com/74322611/205120670-a6f1c943-b30d-4a59-a974-30d94b9e0902.png)

Para comprobar los commits que hemos hecho, podemos usar "git log --oneline -all" para que nos muestre una lista de todos los commits realizados.
Para hacer checkout y movernos por los commits, usamos "git checkout <hash>" (hash es el codigo que ha salido en la lista que identifica a cada commit).
En el commit en el que añadimos el archivo tenemos una linea, el segundo dos lineas y el ultimo, tres. Para volver podemos hacer "git checkout master".

