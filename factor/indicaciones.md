
markdown
# Proyecto Laravel

Este repositorio contiene un proyecto desarrollado con **Laravel** y **Vite**.

---

## 🚀 Requisitos previos

Antes de comenzar, asegúrate de tener instalado:

- PHP >= 8.x con extensiones: `openssl`, `pdo`, `mbstring`, `tokenizer`, `xml`, `ctype`, `json`, `curl`
- Composer
- Node.js y npm
- MySQL o PostgreSQL (según tu configuración)

---

## 📥 Instalación

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/tuusuario/tu-repo.git
   cd tu-repo
Instalar dependencias de PHP

bash
composer install
Instalar dependencias de frontend

bash
npm install
npm run dev   # o npm run build en producción
Configurar variables de entorno

Copia el archivo .env.example a .env:

bash
cp .env.example .env
Configura tus credenciales de base de datos y APP_URL dentro de .env.

Generar la clave de la aplicación

bash
php artisan key:generate
Ejecutar migraciones y seeders (si existen)

bash
php artisan migrate
php artisan db:seed   # opcional
Crear enlace de almacenamiento

bash
php artisan storage:link
▶️ Ejecución
Para iniciar el servidor de desarrollo:

bash
php artisan serve
La aplicación estará disponible en:

Código
http://localhost:8000
