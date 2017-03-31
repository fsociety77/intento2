#//Set proxy
git config --global http.proxy http://usuario:clave@proxy.uc.edu.ve:5010
//Set usuario y email
git config --global user.name "cd"
git config --global user.email "cdvsnp@gmail.com"
//en la carpeta del proyecto
git init
		
//Al salir (De los laboratorios de facyt)
git config --global --unset user.name
git config --global --unset user.email
git config --global --unset http.proxy