🐾 Petshop 2025 - Frontend y Backend
Overview
Este proyecto es una solución para la gestión de un Petshop. Incluye dos componentes principales: un backend desarrollado en Node.js con Express y un frontend en React servido mediante Nginx. El backend gestiona categorías de productos, animales y detalles, además de implementar autenticación de usuarios y envío de correos electrónicos.

Project Structure
El proyecto está dividido en dos partes principales:

backend-petshop: Contiene la API desarrollada en Node.js.

frontend: Aplicación en React que se sirve utilizando Nginx.

Prerequisites
Docker

Docker Compose

Node.js (versión 18 o superior recomendada)

NPM

Getting Started
Build and Run with Docker Compose
Clona el repositorio:

bash
Copiar
Editar
git clone <repository-url>
cd 2025-frontend-ivoschugurensky
Construye y levanta los servicios:

bash
Copiar
Editar
docker-compose up --build
Manual Installation (Without Docker)
Clona el repositorio:

bash
Copiar
Editar
git clone <repository-url>
cd 2025-frontend-ivoschugurensky
Entra en el directorio del backend:

bash
Copiar
Editar
cd backend-petshop
Instala las dependencias:

bash
Copiar
Editar
npm install
Inicia el servidor:

bash
Copiar
Editar
npm start
Accessing the Application
Backend API: http://localhost:3000

Frontend React App: http://localhost (servida por Nginx en el puerto configurado)

Technologies Used
Node.js

Express

Sequelize (ORM)

MySQL

Docker

React

Nginx

JWT (autenticación basada en tokens)

Bcrypt (hashing de contraseñas)

CORS

Dotenv

Nodemailer

UUID

Configuration
La configuración del backend puede modificarse en el archivo:

arduino
Copiar
Editar
backend-petshop/config/config.json
Aquí se definen los parámetros de conexión a la base de datos MySQL.

Usage
El backend expone endpoints REST para gestionar animales, categorías y usuarios.

Los usuarios pueden autenticarse mediante JWT.

El backend puede enviar correos electrónicos para notificaciones utilizando Nodemailer.

El frontend en React se comunica con la API para mostrar y administrar la información.

Author ✍️
Ivo Schugurensky
