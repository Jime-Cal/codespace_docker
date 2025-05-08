# Introducci¢n a Docker ??

Docker es una plataforma que permite desarrollar, enviar y ejecutar aplicaciones dentro de contenedores. Los contenedores son entornos ligeros, port tiles y autosuficientes que incluyen todo lo necesario para ejecutar una aplicaci¢n: c¢digo, librer¡as, dependencias, etc.

## ¨Por qu‚ usar Docker?

- **Portabilidad:** "Funciona en mi m quina" deja de ser un problema. Un contenedor corre igual en desarrollo, testing o producci¢n.
- **Aislamiento:** Cada contenedor se ejecuta de forma independiente, sin interferir con otros servicios o procesos.
- **Eficiencia:** A diferencia de las m quinas virtuales, los contenedores comparten el kernel del sistema operativo, por lo que consumen menos recursos.
- **Escalabilidad:** Docker se integra f cilmente con herramientas de orquestaci¢n como Kubernetes para escalar aplicaciones autom ticamente.

## Conceptos Clave

- **Imagen (Image):** Plantilla inmutable usada para crear contenedores. Por ejemplo, una imagen de Node.js, Python o MySQL.
- **Contenedor (Container):** Instancia en ejecuci¢n de una imagen.
- **Dockerfile:** Archivo de texto que contiene instrucciones para construir una imagen.
- **Docker Hub:** Repositorio p£blico de im genes Docker.

## Comandos B sicos

```bash
# Verificar instalaci¢n de Docker
docker --version

# Descargar una imagen desde Docker Hub
docker pull nombre_imagen

# Ejecutar un contenedor
docker run nombre_imagen

# Ver contenedores en ejecuci¢n
docker ps

# Construir una imagen a partir de un Dockerfile
docker build -t nombre_imagen .

# Detener un contenedor
docker stop nombre_contenedor

# Eliminar un contenedor
docker rm nombre_contenedor

