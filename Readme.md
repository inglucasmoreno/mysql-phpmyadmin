
# Base de datos MYSQL - phpMyAdmin 🛢️ 
Repositorio basico - Docker Mysql y PhpMyadmin

![Build](https://img.shields.io/badge/build-passing-brightgreen)
![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

## 📑 Tabla de Contenidos  
1. [Descripción](#📝-descripción)  
2. [Requerimientos previos](#✨-requerimientos-previos)  
3. [Instalación](#🛠️-instalación)  
4. [Uso](#🧑‍💻-uso)  
5. [Contribuciones](#🤝-contribuciones)  
6. [Licencia](#📜-licencia) 
7. [Contacto](#📧-contacto) 

## 📝 Descripción  
- Este repositorio permite levantar un docker con una base de datos MySql y un administrados phpMyAdmin.

## ✅ Requerimientos previos
- Se debe tener instalado previamente `docker` y `docker-compose`

## 🛠️ Instalación  
```bash
# Clonar el repositorio
git clone https://github.com/tu_usuario/game-soft.git
```

- Crear un archivo `.env` con las siguientes variables de entorno
```bash
MYSQL_ROOT_PASSWORD=
MYSQL_USER=
MYSQL_PASSWORD=
COMPOSE_PROJECT_NAME=db-mysql
```

## 🧑‍💻 Uso

```bash
# Iniciar servicios con docker compose
docker compose up -d
```

- Ingresar en el navegador a la direccion `http://localhost:8081` para abrir phpMyAdmin
- Puede comenzar a trabajar con su servicio de MySQL conectandolo a sus aplicaciones a traves del puerto 3310

## 🤝 Contribuciones  
¡Toda contribución es bienvenida! Por favor sigue los pasos:  
1. Haz un fork del repositorio.  
2. Crea una rama (`git checkout -b feature/nueva-funcionalidad`).  
3. Envía un pull request.

## 📜 Licencia  
Este proyecto está bajo la licencia MIT. Consulta el archivo [LICENSE](./LICENSE) para más detalles.

## 📧 Contacto  
Hecho por [Ing. Moreno Lucas Omar](https://github.com/inglucasmoreno). 