# Mi segundo commit (día 2)

## git diff:

Muestra las diferencias o cambios en nuestro archivo
- `git diff --staged`: Enumera todos los cambios en el archivo

## git status:

Muestra si algo fue cambiado

## git add: 

- `git add .`: Añadir todos los archivos cambiados al área de Staging
- `git add -u`: Añadir solo los archivos cambiados al área de Staging

Nota: Un Staging viene siendo un área de pruebas. Ten en cuenta que si hacemos muchos cambios es posible que rompas algo de tu archivo principal, de ahí la necesidad de contar con un staging o entorno de pruebas.
Se trata de una copia exacta de nuestro archivo principal donde podemos probar cambios

`Git branch`: Sirve para enlistar o crear nuevas ramas de nuestro repositorio.

`git branc`: Enlistar ramas
`git branc <rama>`: Crea una nueva rama
`git branc -D <rama>`: Elimina una rama


## Git checkout

Git checkout sirve para intercambiar ramas o commits

- `git switch <rama>`: Cambiar una rama


**Glosario**
- **remote**: server a los cuales subir cambios
- **origin**: server default para subir los cambios

## Git commit

Guarda los cambios del staging area.

- `git commit -m "Comentario`: Hace un commit con un comentario
- `git commit -am "Comentario`: Es el equivalente de:
    ```bash
    git add -u
    git commit -m "Comentario"
    ```

## Git push

Subir los cambios al *remote* (server)
- `git push <remote> <branch>`: Subir cambios de nuestro branch al server remote
    
- `git push` por default sube los cambios de nuestro branch al *upstream* branch, la cual es la branch default para sincronizar cambios.

