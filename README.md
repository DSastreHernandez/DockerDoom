# DockerDoom
Primero levantamos el numero de contenedores docker que queramos. Para este caso usamos este comando para simplemente hacer la prueba.
```
for i in {1..2} ; do docker run -d -t ubuntu:14.04; done
```
![Captura desde 2022-05-17 15-34-02](https://user-images.githubusercontent.com/91556389/168823382-33657a7f-0292-47fd-a3fb-492df07b4841.png)
Podemos ver con el comando "docker ps" que se han lanzado los contenedores. Y ahora descargamos el siguiente archivo.

https://web.archive.org/web/20160310005603/https://gideonred.com/bins/dockerdoomd.tar.gz

Y lo descomprimimos.

![Captura desde 2022-05-17 16-02-17](https://user-images.githubusercontent.com/91556389/168829523-cdd9ef74-82e9-46b6-b7d7-6d4ada03c6fd.png)

descargamos tambien un VNC en mi caso he descargafo [VNC VIEWER](https://www.realvnc.com/en/connect/download/viewer/linux/). Arrancamos el servico con el comando "./dockerdoomd" y guardamos el puerto que va a usar.

![Captura desde 2022-05-17 16-49-34](https://user-images.githubusercontent.com/91556389/168840974-97f139f5-7da4-4f53-9e90-3e1b2fa15d80.png)

Vamos a la VNC y iniciamos una nueva conexion poniendo localhost:: y justo despues el puerto, aceptamos y ya hemos 

![Captura desde 2022-05-17 18-56-37](https://user-images.githubusercontent.com/91556389/168869192-2e1a1099-4927-4513-b010-4e733ef05e4c.png)

Ponemos la contraseña de la conexion que ene este caso es 1234 y a jugar

![Captura desde 2022-05-17 18-57-58](https://user-images.githubusercontent.com/91556389/168869421-e339cff2-ae7c-42b6-9fea-6dbf89251c8e.png)
