1-1 - Crea un directorio llamado repo01 en local (desde tu máquina) e ejecuta el comando pertinente para que dicho directorio para que se transforme el repositorio en local ¿Cómo podemos identificar que el repositorio se ha inicializado?  

Primero de todo nos pondremos donde queremos crear el repositorio, en mi caso en el escritorio.  
Despues crearemos nuestro repositorio con mkdir + el nombre del repositorio.  
Luego accedemos al repositorio con cd + nombre del repositorio.  
Y luego le decimos con git init que inicialize el repositorio.  
Con el comando "git init" veremos si esta iniciado o iniciaremos nuestro repositorio.  

![](./captura%201.png)

1.2 - Añade un documento llamado readme.md dentro del repositorio (recuerda que MD es la extensión de los ficheros Markdown) y documenta en su interior todos los pasos que vas a realizando para crear un repositior, etc. Puedes añadir fotos o lo que crear conveniente.  

Seguidamente nos iremos a github y crearemos el repositorio, una vez creado le diremos que ya tenemos uno creado, y los dara un link a nuestro repositirio virtual para que se sincronicen con el local que hemos creado.  
Para poder subir lo que tenemos, iremos a nuestro terminal dentro del VSC y le añadiremos lo sienguiente:  
git remote add origin https://github.com/UriR38/repo01.git
git branch -M main
git push -u origin main  
Una vez hecho esto, si nos vamos al repositorio en github veremos que se han sync.