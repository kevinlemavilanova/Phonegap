# Phonegap
Esta es una aplicación de Cordova en la que se hace uso de dos plugins:

# 1. "cordova-camera-plugin"
Para usar este plugin vamos a llamar a esta función desde el evento OnClick:
![alt text](https://github.com/kevinlemavilanova/Phonegap/blob/master/www/img/phonegap/Captura.PNG)

En esta función se realiza la foto, en ella se verifica si ha sido exitosa con:
![alt text](https://github.com/kevinlemavilanova/Phonegap/blob/master/www/img/phonegap/Captura2.PNG)
y si resulto en un fallo de permisos o cuaquier cosa:
![alt text](https://github.com/kevinlemavilanova/Phonegap/blob/master/www/img/phonegap/Captura3.PNG)

# 2. "cordova-vibration-plugin"
En este plugin simplemente tenemos que llmar a esta función y indicarle los milisegundos que quieres que vibre, en este caso se llama a esta función cuando resulto en error al sacar una foto.
![alt text](https://github.com/kevinlemavilanova/Phonegap/blob/master/www/img/phonegap/Captura4.PNG)
