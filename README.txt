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
 - Crear (emacs .gitignore)
 - Contenido (*~;*.x;*a.out)
 - Añadir (git add .gitignore)
   	  (git status)
	  (git commit -m "descipción")

5. Configurar proxy unal
 - (export https="https://elmvargaspi:Jilmalima1@proxyapp.unal.edu.co:8080/"

6. Sincronizando local con el repositorio remoto
 - Iindicar el remoto (git remote add "url_repositorio_en_github"(copiar de git))
 - Comando git push -u origin master (copiar git)
 - Introducir username
 - Introducir password git

7. Enviar archivos nuevos o cambios
 - Git add Nombarchivo.ejemplo
 - Git commit -m "descripción"
 - Git push -u origin master
 - Introducir username
 - Introducir password git

