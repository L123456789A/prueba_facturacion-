<p align="center">
  <a href="https://laravel.com" target="_blank">
    <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo">
  </a>
</p>

<p align="center">
  <a href="https://github.com/tuusuario/tu-repo/actions"><img src="https://github.com/tuusuario/tu-repo/workflows/tests/badge.svg" alt="Build Status"></a>
  <a href="https://packagist.org/packages/laravel/laravel"><img src="https://img.shields.io/packagist/dt/laravel/laravel" alt="Total Downloads"></a>
  <a href="https://packagist.org/packages/laravel/laravel"><img src="https://img.shields.io/packagist/v/laravel/laravel" alt="Latest Stable Version"></a>
  <a href="https://packagist.org/packages/laravel/laravel"><img src="https://img.shields.io/packagist/l/laravel/laravel" alt="License"></a>
</p>

## 📖 Proyecto Laravel

Este repositorio contiene un proyecto desarrollado con **Laravel** y **Vite**.  
Para que funcione correctamente después de clonar, sigue estas indicaciones:

```bash
# Clonar el repositorio
git clone https://github.com/tuusuario/tu-repo.git
cd tu-repo

# Instalar dependencias de PHP
composer install

# Instalar dependencias de frontend
npm install
npm run dev   # o npm run build en producción

# Configurar variables de entorno
cp .env.example .env
php artisan key:generate

# Ejecutar migraciones y seeders (si aplica)
php artisan migrate
php artisan db:seed   # opcional

# Crear enlace de almacenamiento
php artisan storage:link

# Iniciar servidor de desarrollo
php artisan serve

