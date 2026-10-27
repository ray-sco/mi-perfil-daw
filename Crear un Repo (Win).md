\- Creación de un Repositorio 

\- En GitHub

En GitHub pulsamos el icono + y seleccionamos New Repository (nuevo repositorio).
Asignamos el nombre de repositorio, establecemos la privacidad en público o privado, según corresponda.
No marcamos la opción de añadir un Readme y pulsamos el botón Create Repository.

\- En Terminal de Windows
En la carpeta de nuestro proyecto, ejecutamos una terminal.

Iniciamos el repositorio local con el comando:
*   git init

Nos aseguramos que la rama principal se llame "main" con:
*   git branch -M main

Creamos los archivos que conforman el repositorio de forma local.

Listamos los archivos  que vamos a subir con:
*	git add .

Si es la primera vez que vamos a subir un commit, tenemos que especificar nuestro correo y nombre:
*	git config --global user.email "tucorreo@mail.com" 
*	git config --global user.name "Tu Nombre"

Preparamos la subida con:
*   git commit -m "Primer commit"

Luego vinculamos el repositorio local con nuestra cuenta de Github:
*	git remote add origin https://github.com/ray-sco/Entornos-de-Desarrollo

Si es la primera vez que usamos push, se abrirá una ventana donde tenemos que identificarnos e iniciar sesión.

Finalmente subimos el commit con el comando:
*   git push -u origin main

Si todo ha salido bien, al realizar un git status recibimos el mensaje:
> Everything up-to-date
