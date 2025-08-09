# 📂 Intranet - Laravel + Filament

Este es un proyecto **demo** de una intranet desarrollada con [Laravel](https://laravel.com/) y [Filament](https://filamentphp.com/), pensado para demostrar la gestión interna de datos, usuarios y paneles administrativos de forma sencilla y escalable.

## 🚀 Características principales
- Panel de administración con **Filament**
- Gestión de usuarios y roles
- CRUDs dinámicos con interfaz moderna
- Autenticación y autorización integradas
- Arquitectura limpia y escalable

## 🛠 Tecnologías utilizadas
- **[Laravel](https://laravel.com/)** (versión 12.x o superior)
- **[Filament](https://filamentphp.com/)** (interfaz de administración)
- **PHP** 8.1 o superior
- **MySQL / MariaDB** (base de datos)
- **Composer** (gestión de dependencias)
- **Node.js + npm** (para assets y compilación)

## 📋 Requisitos previos
Antes de instalar el proyecto, asegúrate de tener instalado:
- PHP >= 8.1
- Composer
- MySQL o MariaDB
- Node.js y npm

## ⚙ Instalación

1. **Clonar el repositorio**

```bash
# Clonar el repositorio

https://github.com/DeathPaul1125/intranet.git

# Entrar al directorio
cd intranet
   
# Instalar dependencias
composer install
npm install && npm run dev

# Configurar variables de entorno
cp .env.example .env

# Generar key
php artisan key:generate

# Migrar base de datos
php artisan migrate --seed

# Levantar servidor
php artisan serve
