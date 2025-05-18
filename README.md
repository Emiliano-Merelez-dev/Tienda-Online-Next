# Descripción
# 🛒 E-commerce App

Aplicación de comercio electrónico desarrollada con tecnologías modernas. Cuenta con autenticación, administración de productos, carrito de compras, filtros dinámicos y panel de administración. Integra backend con PostgreSQL y prisma, frontend con Next.js y estilos con Tailwind CSS.

---

## 🚀 Tecnologías utilizadas

- Next.js 14
- React
- Tailwind CSS
- PostgreSQL
- Prisma ORM
- Zustand (manejo de estado)
- Server Actions (Next.js)
- Docker (para levantar base de datos)

---

## ✨ Funcionalidades principales

- Registro e inicio de sesión de usuarios
- Carrito de compras persistente
- Filtros por categoría, precio y más
- CRUD completo de productos desde el panel de administración
- Deploy en Vercel




## Correr en dev


1. Clonar el repositorio.
2. Crear una copia del ```.env.template``` y renombrarlo a ```.env``` y cambiar las variables de entorno.
3. Instalar dependencias ```npm install```
4. Levantar la base de datos ```docker compose up -d```
5. Correr las migraciones de Primsa ```npx prisma migrate dev```
6. Ejecutar seed ```npm run seed```
7. Correr el proyecto ```npm run dev```
8. Limpiar el localStorage del navegador.




## Correr en prod
