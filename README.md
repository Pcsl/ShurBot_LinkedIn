# ShurBot_LinkedIn

El ShurBot que te permite aplicar a todas las ofertas con EasyApply en LinkedIn

### Aviso

Si durante la instalacion del bot tenemos cualquier problema que no aparezca en las instrucciones, buscar un tutorial en YouTube sobre como instalar X nos debería resolver ese problema. El ordenador de cada uno es un mundo(distintos Sistemas Operativos, programas instalados que puedan dar problemas, distintas versiones de los programas, etc.).

## Instrucciones de uso:

1. Instalamos `Visual Studio Code` https://code.visualstudio.com/

2. Instalamos el lenguaje de programación `Python` https://www.python.org/downloads/ Descargamos la última versión, que estará en un botón amarillo grande por el centro de la pantalla (Si tenéis algún problema, miraos algún tutorial en Youtube que seguramente os solucione todo)
3. Creamos una carpeta donde queramos, y ahí copiamos lo que hemos extraído del archivo `.zip`

4. Abrimos Visual Studio y le damos a `Open Folder`, abrimos desde el programa la carpeta que acabamos de crear al haber extraído el .zip

5. Instalamos la extensión de Python en Visual Studio. Para ello vamos a la barra izquierda y vemos el icono de los 4 cuadrados. Buscamos en la barra de búsqueda `python` e instalamos la primera extensión, la oficial de Microsoft
6. En la barra de la izquierda, arriba, hay un icono de 2 hojas, si hacemos click aparecerá el menú de documentos

7. Hacemos doble click en `easyapplybot.py` para ver el código del archivo

8. Ahora volvemos otra vez a donde clickamos anteriormente para ver el archivo, pero le damos click derecho, y le damos a `Run Python File in Terminal`, que saldrá de las últimas opciones disponibles

9. En la parte de abajo aparecera la terminal, igual se inicia automaticamente el bot o igual no. Si lo hace dará error, ya que falta configurarlo. Pulsamos Control + C varias veces y luego Enter, hasta que aparezca todo el rato la misma linea una y otra vez, eso es que no hay nada funcionando

10. Instalamos los paquetes que hacen falta. Para ello copiamos esto y lo pegamos en la terminal: `pip install -r requirements.txt` le damos a enter y ejecutará el comando.
    Si os da algún error, podéis probar a añadir `--user`, quedaría así: `pip install -r requirements.txt --user`

11. Ahora tenemos que modificar el archivo `config.ini` donde pone `username`, `password`, `position` y `location`. Ahí ponemos lo que nos interesa, nuestro usuario de LinkedIn y contraseña, y de `position` ponemos el trabajo que queremos y de `location` pues la ciudad o país que queramos. Guardamos los cambios en el archivo

12. Con todo listo, ejecutamos el programa, dándole a `Run Python File in Terminal` como antes

13. Ya deberia de estar funcionando. Como aclaración, decir que el CV, el teléfono y todo ese rollo no tiene nada que ver con el bot, eso lo configuramos nosotros en nuestra cuenta de LinkedIn para que cuando hacemos EasyApply salga el CV por defecto.

14. Para parar el bot, podemos ir a la terminal, clickar sobre ella, y pulsar `Control + C`

Varios shurs ya lo preguntaron. Este bot vale para **todos los trabajos y todos los lugares del mundo**. Que queremos buscar trabajo de _Android Developer en Madrid_, pues modificamos el archivo `config.ini` y listo. Que queremos buscar en otro sitio u otro puesto (_Comercial de ventas en Albacete_) pues cambiamos los parámetros `position` y `location` en el archivo y listo.
Para que los cambios tengan efecto hay que iniciar el bot después de haber guardado la nueva configuración en `config.ini`.
