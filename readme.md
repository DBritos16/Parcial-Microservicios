# Parcial Microservicios

### Pasos a seguir:
#### Creación de imagen:
Ejecutar el siguiente comando dentro de la carpeta front:
- docker build . -t dolar
- 
#### Creación de los servicios:
Ejecturar los siguientes comandos en la carpeta raiz donde se encuentre el .yml:
- docker swarm init
- docker stack deploy -c service-dolar.yml dolar-service

#### Prueba del servicio:
Ingresar a http://localhost:3000 para visualizar el servicio.