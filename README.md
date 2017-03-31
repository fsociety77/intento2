#//Set proxy
git config --global http.proxy http://usuario:clave@proxy.uc.edu.ve:5010
//Set usuario y email
git config --global user.name "cd"
git config --global user.email "cdvsnp@gmail.com"
//en la carpeta del proyecto
git init
//Ver estado
git status
//Añadir todos los archivos a seguimiento
git add -A
//Conectar a repositorio
git remote add origin https://github.com/fsociety77/intento2.git
git push -u origin master
//ver a que remotes estas
git remote -v

//Al salir (De los laboratorios de facyt)
git config --global --unset user.name
git config --global --unset user.email
git config --global --unset http.proxy