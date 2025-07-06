# Clase 7: 
Servicio de docker scout

# Fecha: 
01/07/2025

# Objetivos
    - docker scout (Permite analizar las vulnerabilidades)
    - creación de tags de la imagen
    - Versionamientos MAJOR.MINOR.PATCH
    - logueo en docker con usuario y contraseña para controlado de versionamiento
    - docker compose se basa en registros 
    - tag semanticos
    - subir a docker hub
    - Creación de servicios 

    
# Comandos utilizados

    docker-compose up 

    

    mkdir docker-node-scout 

    Servicio que permite analizar las bulnerabilidades  

    mkdir docker-node-scout 

    $ npm init –y 

    $ npm install express 

    

    

    $ docker build -t jaquelin1889/minode-scout:0.1.0 -t jaquelin1889/minode-scout:latest . 

    $ docker images jaquelin1889/minode-scout 

    $ docker scout cves jaquelin1889/minode-scout:0.1.0 

    $ docker build -t jaquelin1889/jaquelin1889/minode-scout:0.2.0 -t jaquelin1889/minode-scout:latest . 

    $ docker images 