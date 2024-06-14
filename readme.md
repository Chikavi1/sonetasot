# Registro de Citas para COVID en Jalisco

Este repositorio contiene el proyecto de registro de citas para COVID en Jalisco, que consta de un frontend en Angular y un backend en Node.js.

## Requisitos previos

Antes de ejecutar la aplicación, asegúrate de tener instalados los siguientes componentes en tu sistema:

- Docker
- Docker Compose

## Clonar el Repositorio

Primero, clona este repositorio y luego inicializa y actualiza los submódulos:

```bash
git clone https://github.com/Chikavi1/sonetasot.git
cd netasot
git submodule update --init
docker-compose up --build --force-recreate