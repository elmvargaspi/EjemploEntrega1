Sincronizando carpeta Entregas con git

1. Para sincronizar:
 - Crear directorio (mkdir nombdir)
 - Ir al directorio (cd nombdir)
 - sincronizar con git (git init)
2. Configurar git
 - Indicar nombre (git config --global user.name "Eliana Vargas")
 - Indicar email (git config --global user.email "elmvargaspi@unal.edu.co")
3. Crear archivo y enviarlo a git
 - Cerar archivo (emacs README01.txt)
 - Añadir a git (git add README01.txt)
   	    	(git status)
 - Para enviar de forma definitiva (git commit -m "descipción")
4. Agregar .gitignore
 - crear (emacs .gitignore)
 - contenido (*~;*.x;*a.out)
 - añadir (git add .gitignore)
   	  (git status)
	  (git commit -m "descipción")
5. Configurar proxy unal
 - (export https="https://elmvargaspi:Jilmalima1@proxyapp.unal.edu.co:8080/"

6. Sincronizando local con el repositorio remoto
 - indicar el local (git remote add origin "nombdir"
 - indicar el remoto (git clone "url_repositorio_en_github")
7. Enviando cambios al Remoto
