# Microservicios Hola Mundo

Este proyecto es un ejemplo simple de microservicios que responden con "Hola Mundo". Está compuesto por dos microservicios, cada uno ejecutándose en su propio contenedor Docker.

## Estructura del Proyecto

```
microservicios-hola-mundo
├── servicio1
│   ├── src
│   │   └── app.js
│   ├── Dockerfile
│   └── package.json
├── servicio2
│   ├── src
│   │   └── app.js
│   ├── Dockerfile
│   └── package.json
├── docker-compose.yml
└── README.md
```

## Requisitos

- Docker
- Docker Compose

## Instrucciones

1. Clona este repositorio en tu máquina local.
2. Navega al directorio del proyecto.
3. Ejecuta el siguiente comando para construir y ejecutar los microservicios:

   ```
   docker-compose up --build
   ```

4. Accede a los microservicios en las siguientes URLs:
   - Servicio 1: [http://localhost:3000](http://localhost:3000)
   - Servicio 2: [http://localhost:3001](http://localhost:3001)

## Descripción de los Microservicios

- **Servicio 1**: Un microservicio que responde con "Hola Mundo" en la ruta raíz.
- **Servicio 2**: Otro microservicio que también responde con "Hola Mundo" en la ruta raíz.

