# Wordpress Dockerizado

Les comparto mi archivo de Docker compose, para realizar pruebas rápidas o muy bien para comenzar un trabajo con Wordpress

# Proceso
  - Clonar repositorio
  - Nos vamos a nuestra terminal y dentro del directorio del proyecto ejecutamos los siguientes comandos:
    ```sh
    $ docker-compose build
    $ docker-compose up
    ```

Recuerden verificar la disponibilidad de los puertos, ya que si alguno de los utilizados no podrá docker levantar el contenedor. Así que si así lo desean pueden modificar los puertos (`ports`)

Si todo salió bien, nos podemos ir a nuestro navegador e ingresar a la siguiente url `localhost:8000` , este nos debería de lanzar ya la vista inicial del Wordpress con el proceso de instalación.



**Comparte conocimiento...**