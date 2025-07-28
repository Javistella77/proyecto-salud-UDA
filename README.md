# Proyecto de Salud 🏥

Sistema web de gestión de pacientes desarrollado en PHP y MySQL. Permite registrar usuarios, guardar historiales médicos y administrar planes de salud.

## 🚀 Funcionalidades

- Registro e inicio de sesión de usuarios
- Carga y visualización de historiales médicos
- Administración de planes (bronce, plata, oro)
- Panel para profesionales de la salud
- Integración con Mercado Pago
- Soporte para compartir vía `ngrok`

## 🛠️ Tecnologías utilizadas

- PHP
- HTML / CSS / JavaScript
- MySQL
- XAMPP (entorno local)
- ngrok (exposición a internet)
- Mercado Pago (pagos online)

## 🗃️ Base de datos

El archivo `proyecto_salud.sql` contiene la estructura de la base de datos.  
Podés importarlo desde phpMyAdmin o cualquier gestor compatible con MySQL.

## 🧪 Instalación local

1. Cloná o descargá este repositorio
2. Copiá los archivos a `C:\xampp\htdocs\ProyectoDeSalud`
3. Importá `proyecto_salud.sql` en tu base de datos
4. Iniciá Apache y MySQL desde XAMPP
5. Accedé desde tu navegador:  
   `http://localhost/ProyectoDeSalud`

## 🌐 Compartir el proyecto con ngrok

1. Instalá ngrok desde [https://ngrok.com/](https://ngrok.com/)
2. Iniciá sesión y autenticá tu cuenta
3. Desde consola, ejecutá: ngrok http 3000
4. Debes remplazar la URL de ngrok por las del proyecto
5. Para finalizar debes iniciar node accesiendo desde CMD con cd a la ubicació del proyecto y ejecutar con NODE el server.js Es decir: node server.js

