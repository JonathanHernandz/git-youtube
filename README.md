# Comandos utiles de Git

1. `git init` 
2. `git add .` Toma todos los archivos y los prepara para una fotografia tambien conocido como commit
3. `git reset .` Hace lo contrario al anterior 
4.  `git commit -m "comentario"` Hace la fotografia
5. `git checkout -- .` devuelve la version donde se hizo el commit
6. `git log`
7. `git commit --amend` modifica el ultimo commit, la tecla `i` para poder ingresar texto, ingresamos el texto y despues presionamos la tecla `esc`, ingresamos `:` y la tecla `wq!`
`w` write para escribir, `q` para salir, `!` para hacerlo al instante
8. `git checkout -b rama-heroes` creamos una nueva rama `b` para crear una nueva rama
9. `git checkout master` nos cambiamos de rama
10. `git branch` saber en que rama estamos
11. `git push` los ultimos cambios los va a guardar en github
12. `git commit -am` hace los pasos git add y git commit a la vez