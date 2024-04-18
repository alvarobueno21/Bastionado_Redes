# Parte 1: Vía realista

Para la primera parte, lo primero que haremos será Registrarnos en DigitalOcean, luego nos crearemos nuestro primer proyecto que será una máquina Ubuntu, elegiremos la opción de SSH y en un sistema Linux que tengamos a parte configurado y con SSH instalado, nos crearemos la clave con ssh-genkey y luego leeremos el fichero que acabamos de crear que contiene nuestra clave pública: cat id\_ed25519.pub, y el contenido del fichero lo copiamos en la configuración de nuestra maquina Ubuntu que está alojada en DigitalOcean .

El siguiente paso será conectarnos por SSH desde nuestro Linux a la máquina Ubuntu con el comando (ssh root@ip\_ubuntu) y una vez estamos dentro nos pedirá contraseña para entrar, para que no nos la pida metemos el siguiente comando (ssh-copy-id root@ip\_ubuntu) y la próxima vez que entremos ya no nos pedirá contraseña.

![gifparte1](img/parte1.gif)
