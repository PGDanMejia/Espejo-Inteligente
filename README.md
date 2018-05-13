# Smart-Mirror
Raspberry powered mirror which can display the news, weather, and time.
Un espejo que trabaja con un Raspberry el cual puede mostrar noticias(Las que decidas), clima y fecha y hora

## Instalacion y Actualización
### Codigo
Si tienes [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) instalado, obten el repositorio.

```
git clone git@github.com:HackerHouseYT/Smart-Mirror.git
```

**De forma alternativa, puedes descargar el zip que contienen el proyecto(Boton verde en el repositorio de la pagina)**

Ve al folder donde se encuetra el repositorio

```
cd Smart-Mirror
```

### Instala todas las dependencias
Asegurate de tener instalado [pip](https://pip.pypa.io/en/stable/installing/) antes de hacer esto

```
sudo pip install -r requirements.txt
```

```
sudo apt-get install python-imaging-tk
```

### Añade tu api token
Asegurate de tener instalado vim en tu sistema `sudo apt-get install vim`
Usa `vim` para editar tu archivo

```
vim smartmirror.py
```

Reemplaza `weather_api_token` con el token que recibio de https://darksky.net/dev/

## Ejecucion
Para correr la aplicacion, ejecute el siguiente comando en el folder del repositorio

```
python smartmirror.py
```

## Demo e instrucciones de construccion 
(click a la imagen para ir al video)
[![Link to youtube how-to video](http://i.imgur.com/cMyaSHT.png)](https://youtu.be/fkVBAcvbrjU)

