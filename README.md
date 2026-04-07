# ESPAÑOL

# 🌐 Innovaspace Coworking - innovaspace.netlify.app

Aplicación web fullstack que permite publicar, explorar y reservar espacios de coworking.  

## 🧾 Descripción

Innovaspace Coworking es una plataforma donde los usuarios pueden registrarse, gestionar su perfil y realizar reservas en diferentes oficinas disponibles, mientras que los administradores pueden gestionar los espacios publicados.

La aplicación está desarrollada con una arquitectura **client-server**, separando un frontend en React de una API REST construida con Node.js y Express, conectada a una base de datos relacional.

Este proyecto fue desarrollado inicialmente como **proyecto final de bootcamp en equipo** y posteriormente mejorado individualmente para su presentación en portfolio profesional.

## 🚀 Características principales

- Registro y autenticación de usuarios.
- Activación de cuenta mediante código de registro.
- Gestión de perfil de usuario y avatar.
- Exploración de espacios de coworking disponibles.
- Sistema de reservas con fechas de entrada y salida.
- Sistema de valoración y comentarios sobre oficinas.
- Panel de administración para gestionar espacios y reservas.
- Recuperación de contraseña mediante e-mail.

## 🛠️ Stack Tecnológico

- **React** con JSX
- **Node.js** para el backend
- **Express** para la API REST
- **MySQL** como base de datos relacional
- **JavaScript**
- **CSS** modularizado
- **React Context API**
- **Vite** como bundler
- **Netlify** para el despliegue frontend
- **Render** para el despliegue backend

## 📂 Estructura del proyecto (resumida)

# Frontend
```
client/
├──src/
|  ├── components/
|  ├── contexts/   # Contexto de Autenticación
|  ├── hooks/      # Hooks personalizados
|  ├── pages/
|  └── App.jsx
├── .env.local     # Variables de entorno para el frontend
└── styles/        # Archivos CSS por sección
```
# Backend
```
server/
├──src/
|  ├── controllers/ # Lógica de negocio
|  ├── db/          # Base de datos y modelos
|  ├── middlewares/ # Middlewares de autenticación
|  ├── routes/      # Rutas de la API
|  └── utils/       # Funciones auxiliares
├── .env
└── app.js
```

## 🌍 Demo online

🔗 [innovaspace.netlify.app](https://innovaspace.netlify.app)
- Demo user:
    - Email: demo@innovaspace.com
    - Password: demo123

## Instalación local

Ver [INSTALLATION.md](INSTALLATION.md)

## 📬 Contacto

- Portfolio: [moliverdev.netlify.app](https://moliverdev.netlify.app)
- LinkedIn: [linkedin.com/in/moliverg](https://linkedin.com/in/moliverg)
- Email: olivermauro@outlook.com

## 📝 Licencia

Este proyecto es de código abierto solo con fines de presentación. Derechos reservados © 2025.

# ENGLISH

# 🌐 Innovaspace Coworking - innovaspace.netlify.app

Fullstack web application that allows users to publish, explore and book coworking spaces.  

## 🧾 Overview

Innovaspace Coworking is a platform wheres users can explore available offices, check their details, make reservations and leave ratings or comments about their experience, while admins can manage the listed spaces.

The application follows a **client-server architecture**, separating a React frontend from a REST API built with Node.js and Express connected to a relational database.

This project was originally developed as a **team bootcamp final project** and later improved individually for portfolio presentation.

## 🚀 Key Features

- User registration and authentication.
- Account activation via registration code.
- User profile and avatar management.
- Browse available coworking spaces.
- Reservation system with check-in and check-out dates.
- Office rating and comment system.
- Admin management of offices and bookings.
- Password recovery via email.

## 🛠️ Tech Stack

- **React** with JSX
- **Node.js** for the backend
- **Express** for the REST API
- **MySQL** relational database
- **JavaScript**
- **Modular CSS**
- **React Context API**
- **Vite** as bundler
- **Netlify** for frontend deployment
- **Render** for backend deployment

## 📂 Project Structure (brief)

# Frontend
```
client/
├──src/
|  ├── components/
|  ├── contexts/   # Auth context
|  ├── hooks/      # Hooks personalizados
|  ├── pages/      # App pages
|  └── App.jsx
├── .env.local     # Frontend environment variables
└── styles/        # CSS files by section
```
# Backend
```
server/
├──src/
|  ├── controllers/ # Business logic
|  ├── db/          # Database and models
|  ├── middlewares/ # Authentication middlewares
|  ├── routes/      # API routes
|  └── utils/       # Helper functions
├── .env            # Environment variables
└── app.js          # Backend entry point
```

## 🌍 Online Demo

🔗 [https://innovaspace.netlify.app](https://innovaspace.netlify.app)
- Demo user:
    - Email: demo@innovaspace.com
    - Password: demo123

## Local installation

See [INSTALLATION.md](INSTALLATION.md)    

## 📬 Contact

- Portfolio: [moliverdev.netlify.app](https://moliverdev.netlify.app)
- LinkedIn: [linkedin.com/in/moliverg](https://linkedin.com/in/moliverg)
- Email: olivermauro@outlook.com

## 📝 License

This project is open for presentation purposes only. All rights reserved © 2025.