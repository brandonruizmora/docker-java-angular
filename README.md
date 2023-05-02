# Docker 

## Requerido

Docker desktop [Download link](https://docs.docker.com/get-docker/)

**o**

Docker ubuntu

Uninstall older versions  `sudo apt-get remove docker docker-engine docker.io containerd runc`

Install last version `sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin`

---

## Descripción 

Orquestación compleja con servicios y imágenes independientes.

- Postgres
- Adminer
- App Java
- App Angular

---

### Comandos orquestación

Crear imagenes 

`docker compose -f stack-billing.yml build`

Construir imagenes y inicializar contenedores

`docker compose -f stack-billing.yml up -d`

Finalizar contenedores

`docker compose -f stack-billing.yml stop`

Finalizar y eliminar contenedores

`docker compose -f stack-billing.yml down -d`
