# 🐾 PetShop E-commerce

Una plataforma de comercio electrónico moderna y responsive para una tienda de mascotas, con funcionalidades completas de carrito de compras, autenticación de usuarios y gestión de productos.

## 🛠 Stack Tecnológico

![React](https://img.shields.io/badge/React-18.3-blue?logo=react)
![Vite](https://img.shields.io/badge/Vite-5.4-purple?logo=vite)
![Node.js](https://img.shields.io/badge/Node.js-18-green?logo=node.js)
![Express](https://img.shields.io/badge/Express-4.21-black?logo=express)
![MySQL](https://img.shields.io/badge/MySQL-8.0-orange?logo=mysql)
![Docker](https://img.shields.io/badge/Docker-Latest-blue?logo=docker)
![Nginx](https://img.shields.io/badge/Nginx-Latest-green?logo=nginx)

## 🚀 Características Principales

- 🔐 Sistema completo de autenticación (registro, login, recuperación de contraseña)
- 🛒 Carrito de compras con persistencia
- 📱 Diseño responsive y moderno
- 🎨 Interfaz de usuario intuitiva con animaciones suaves
- 🔄 Gestión de estado con Context API
- 🌐 Backend RESTful con Express
- 🗄️ Base de datos relacional MySQL
- 🐳 Containerización con Docker
- 🔄 Proxy reverso con Nginx

## 📦 Instalación

### Requisitos Previos

- Docker y Docker Compose
- Node.js 18+
- Git

### Pasos de Instalación

1. Clonar el repositorio:
```bash
git clone https://github.com/tu-usuario/2025-frontend-ivoschugurensky.git
cd 2025-frontend-ivoschugurensky
```

2. Iniciar los contenedores con Docker Compose:
```bash
 docker commpose up -d --build && docker compose logs -f
```

3. El proyecto estará disponible en:
   - Frontend: http://localhost:8080
   - Backend: http://localhost:4000
   - Base de datos MySQL: puerto 3306

## 🛠 Uso Básico

### Desarrollo Local

Levantar el proyecto:
```bash
npm install
npm run dev
```



## 🏗 Estructura del Proyecto

```
.
├── frontend/                 # Aplicación React
│   ├── src/
│   │   ├── components/      # Componentes React
│   │   ├── context/        # Context API
│   │   └── routes/         # Rutas de la aplicación
│   └── public/             # Archivos estáticos
│
├── backend-petshop/         # Servidor Express
│   ├── controllers/        # Controladores
│   ├── models/            # Modelos Sequelize
│   ├── routes/            # Rutas API
│   └── config/            # Configuración
│
└── docker-compose.yml      # Configuración Docker
```

## 📜 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo LICENSE para más detalles.

## ✨ Créditos

- Desarrollado por Ivo Schugurensky

