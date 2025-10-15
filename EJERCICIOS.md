# Ejercicio 1

Creo el archivo notas.md incluyendo 4 asignaturas, luego hice los comandos
de add, commit y push
``git add notas.md``
``git commit -m "feat: añade notas iniciales"``
``git push origin main``, le añadí las asignaturas restantes e hice el commit de nuevo con ``git commit -am "feat: amplía notas.md"`` y lo subí a GitHub con ``git push origin main``
Se guardaron los cambios correctamente.

# Ejercicio 2

Este ejercicio también salió bien. Creé la rama, edité notas.md, hice el commit,
fusioné la rama con la principal y luego borré la rama en local ``git branch -d feature-tareas`` y en remoto 
con ``git push origin --delete feature-tareas``.

# Ejercicio 3

Este ejercicio no salió tan bien. Creé el archivo con contenido, le hice el commit y lo borré
con 
``git rm temporal.txt``
``git commit -m "chore: elimina archivo temporal"``
``git push``
Hasta ahí todo bien pero al hacer el ``git restore temporal.txt`` decía que no encontraba ese archivo (porque estaba borrado) 
No encontré la manera de que lo restaurase.

# Ejercicio 4

Este ejercicio no salió nada cuando puse el ``git log --oneline --graph --all``. Sin embargo sí que salieron cosas al poner el 
``git diff HEAD~1 HEAD``
Lo que salió al poner el git diff fueron los cambios que se realizaron en los commits. Ponía en rojo el texto 
antiguo que ya no aparezca y en verde el texto nuevo.

# Ejercicio 5

En este me costó pero pude realizarlo en su totalidad. Creé la rama, edité la misma línea en rama y en main
hice commit en las 2 y luego las fusioné. El resto lo explico en el archivo conflicto.md

# Ejercicio 6

Creé ambas tags sin problema. La primera es la version 1.0, primero se crea y luego se sube a GitHub con push.
Usando 
``git tag v1.0``
``git push origin --tags``
La segunda es la version 1.1, con el nombre de "Primera version estable". Después se subir a GitHub
sin problema.
Usando
``git tag -a v1.1 -m "Primera versión estable"``
``git push origin --tags``