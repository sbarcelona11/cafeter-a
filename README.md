# Cafeter-a

## API Rest 
Este API Rest fue construido como un api de ejemplo.
### Requisitos
- NodeJs 12 o superior
- Npm instalado

### Instalacion
1 - Clonar o descargar el repositorio.
2 - Ejecutar npm install para instalar las dependencias.
3 - Ejecutar la aplicación con ```npm start``` si desea levantar el modo desarrollo.
4 - Para correr en modo produccion, ejecutar ```npm run start:prod```

### Uso
Una ves que la aplicacion este corriendo, podremos consumir la informacion de los diferents endpoints.
La documentacion para este API Rest, esta contenida en archivo ```cafeteria.postman_collection.json``` el cual tienen que importar dentro de Postman.
Cada endpoint tiene un ejemplo de uso dentro.

### Docker
Para correr la aplicacion en un contenedor de Docker, se debe ejecutar el siguiente comando:
```docker build -t cafeteria .```
```docker run -p 4000:4000 cafeteria```

### Docker-compose
Para correr la aplicacion en un contenedor de Docker, se debe ejecutar el siguiente comando:
```docker-compose up```

### Deploy on AWS
```pm2 start npm --name "cafeteria" -- start```
```pm2 stop```
```pm2 logs```
```pm2 status```

### Contacto
* [Sebastian Barcelona](https://www.linkedin.com/in/sebastian-barcelona-01565297/)
