Primero, me encargué de poner en una carpeta específica los archivos en los que trabajé, en este caso index.html y styles.ccs, además de crear el respositorio en GitHub
En la terminal de VS code ejecuté el comando git init para que se creara un respositorio en la carpeta en la que estaba trabajando.
Después, me encargué de conectar mi repositorio local con el de Github por medio de la instrucción: git remote add origin https://github.com/DiegoAdabache/Museo-Soumaya.git
En seguida se creó la rama en la que se trabajaría con el comando git checkout -b user/Diego/pagina-museo 
Esta vez se usó el comando git add. para perfilar todos los documentos en los que se trabajó en la carpeta.
Se hizo el commit de los archivos con el comando git commit -m "Primera versión Soumaya", lo cual el sistema respondió:

[user/Diego/pagina-museo (root-commit) af95f32] Primera versión Soumaya
 2 files changed, 340 insertions(+)
 create mode 100644 index.html
 create mode 100644 styles.css

 Por último, se hizo el push git push -u origin user/Diego/pagina-museo, dando como respuesta:
 
 Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 20 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 4.01 KiB | 4.01 MiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'user/Diego/pagina-museo' on GitHub by visiting:
remote:      https://github.com/DiegoAdabache/Museo-Soumaya/pull/new/user/Diego/pagina-museo
remote:
To https://github.com/DiegoAdabache/Museo-Soumaya.git
 * [new branch]      user/Diego/pagina-museo -> user/Diego/pagina-museo
branch 'user/Diego/pagina-museo' set up to track 'origin/user/Diego/pagina-museo'.
PS C:\Users\diego\DESARROLLO-WEB\museo-soumaya> git branch
* user/Diego/pagina-museo
PS C:\Users\diego\DESARROLLO-WEB\museo-soumaya>
