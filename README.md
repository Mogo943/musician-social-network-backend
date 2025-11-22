# 🎵 Plataforma de Conexión para Músicos (Backend API)
**Proyecto Final — Bootcamp Soy Henry | Full Stack Developer**

[![NestJS](https://img.shields.io/badge/NestJS-11.0-E0234E?logo=nestjs&logoColor=white)](https://nestjs.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.7-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-4169E1?logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Swagger](https://img.shields.io/badge/Swagger-OpenAPI-85EA2D?logo=swagger&logoColor=black)](https://swagger.io/)

## 🎨 Front
[Frontend Repository](https://github.com/Mogo943/musician-social-network-frontend)

---
## 📋 Descripción del Proyecto

Backend RESTful desarrollado como pieza central del Proyecto Final de la carrera Full Stack en Soy Henry. El sistema impulsa una red social de nicho diseñada para conectar músicos, facilitar la formación de bandas y gestionar oportunidades laborales.

A diferencia de un backend tradicional, esta arquitectura implementa **Domain-Driven Design (DDD)** sobre **NestJS**, priorizando la escalabilidad, la seguridad modular y la integración con servicios externos (Cloudinary, Auth0, Mercado Pago).

---

## 📚 Documentación Técnica & Arquitectura

Para facilitar la colaboración y el mantenimiento, hemos generado una documentación viva de la arquitectura:

* 👉 **[Explorar Arquitectura en DeepWiki](https://deepwiki.com/pf-henry-g3/back)** (Diagramas de flujo, Relaciones y Módulos)
* 📄 **Swagger API:** Disponible en el endpoint `/docs` al iniciar el servidor localmente.

---

## 🚀 Funcionalidades Principales

### 🔐 Seguridad y Autenticación
* **Sistema Híbrido:** Autenticación vía **Auth0** (Social Login) y Local (JWT + Bcrypt).
* **RBAC:** Control de acceso basado en roles (Admin, SuperAdmin, User) mediante Guards y Decoradores personalizados.

### 🎸 Módulos de Negocio
* **Gestión de Perfiles:** Músicos con instrumentos, géneros y experiencia.
* **Motor de Búsqueda:** Búsquedas globales y filtradas (por instrumento, ubicación, género) optimizadas en base de datos.
* **Bandas y Vacantes:** Lógica compleja para unir miembros a agrupaciones y postular a trabajos.

### ☁️ Integraciones y Servicios
* **Pagos:** Integración con **Mercado Pago** para donaciones.
* **Archivos:** Carga y validación de imágenes con **Cloudinary** y Multer.
* **Emailing:** Sistema de notificaciones transaccionales.

---

## 🛠 Tecnologías Usadas

| Categoría | Herramientas |
| :--- | :--- |
| **Core** | Node.js, NestJS, Express, TypeScript |
| **Base de Datos** | PostgreSQL, TypeORM (Migraciones y Entidades) |
| **Calidad (QA)** | Jest (API Testing), Class-Validator, ESLint |
| **Infraestructura** | Docker, Git/GitHub |
| **Docs & Tools** | Swagger (OpenAPI), Postman/Insomnia, DeepWiki |

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=git,github,js,nestjs,nodejs,npm,ts,postgres,postman,vscode,docker" />
  </a>
</p>

---

## ⚙️ Instalación y Despliegue

```bash
# 1. Clonar el repositorio
git clone [https://github.com/pf-henry-g3/back.git](https://github.com/pf-henry-g3/back.git)
cd back

# 2. Instalar dependencias
npm install

# 3. Variables de Entorno
# Configurar el archivo .env basándose en .env.example
# (Requiere credenciales de DB, Auth0 y Cloudinary)

# 4. Ejecutar Migraciones
npm run migration:run

# 5. Iniciar Servidor
npm run start:dev
```

### 📫 Autores
- 💼 [**Agostina Gaggioli**](https://www.linkedin.com/in/agostina-gaggioli-4495ba234/)
- 💼 [**Carlos Mogollon**](https://www.linkedin.com/in/carlosmogollon-it/)
- 💼 [**Santiago Rivero**](https://www.linkedin.com/in/santriv06/)
- 💼 [**Fernando Arancibia**](https://github.com/fernando-arancibia)
- 💼 [**Ignacio Aguirre**](https://www.linkedin.com/in/ignacioaguirresite/)
- 💼 [**Nicolas Scilipoti**](https://www.linkedin.com/in/nicolas-scilipoti/)





