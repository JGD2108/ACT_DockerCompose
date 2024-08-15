# Proyecto de Docker Compose

Este proyecto utiliza Docker Compose para orquestar múltiples servicios Docker, incluyendo dataflow, ea_grafty y un reverse-proxy basado en Nginx.

## Integrantes

- José Gómez
- Mariana Rodríguez

## Estructura del Proyecto

- Dataflow/: Contiene el Dockerfile y el código fuente para el servicio dataflow.
- EA_Grafty/: Contiene el Dockerfile y el código fuente para el servicio ea_grafty.
- reverse_proxy/: Contiene el Dockerfile y la configuración de Nginx para el servicio de proxy inverso.
- docker-compose.yaml: Archivo de configuración de Docker Compose.
- nginx.conf: Archivo de configuración de Nginx.

## Requisitos

- Docker
- Docker Compose

## Configuración

Asegúrate de que Docker y Docker Compose estén instalados en tu sistema.

## Ejecución

Para construir y ejecutar los servicios, utiliza el siguiente comando:

```sh
docker-compose up --build
