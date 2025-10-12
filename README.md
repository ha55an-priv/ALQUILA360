# ALQUILA360

# Alquila360

Sistema de gestión de alquileres y mantenimiento de propiedades.  
Permite gestionar contratos, cuotas automáticas, pagos, tickets de mantenimiento y reportes para administradores, propietarios, inquilinos y técnicos.



## 🔹 Tecnologías usadas

- **Frontend:** NextJS, React, TailwindCSS  
- **Backend:** NestJS, TypeScript  
- **Base de datos:** MySQL / PostgreSQL  
- **Deploy:** Railway (gratuito)  
- **Version control:** Git / GitHub  


## 🔹 Características principales

- Gestión de contratos de alquiler y generación automática de cuotas.  
- Registro de pagos manuales y automáticos, con recibos PDF.  
- Tickets de mantenimiento con fotos, prioridad y seguimiento del estado.  
- Reportes de morosidad, ingresos, ocupación y tickets.  
- Roles definidos: Administrador, Propietario, Inquilino y Técnico.  
- Seguridad, auditoría y respaldos automáticos de los registros y comprobantes.  





# 1️⃣ Ir al directorio del proyecto
cd "C:\Users\LENOVO\Documents\SIS INFO\Alquila360"

# 2️⃣ Asegurarse de estar en main y actualizado
git checkout main
git pull origin main

# 3️⃣ Crear y subir ramas de features

# Auth y Roles (ya hecho, pero por consistencia)
git checkout -b feature/auth-roles
git push --set-upstream origin feature/auth-roles

# Contratos y Cuotas
git checkout main
git pull origin main
git checkout -b feature/contratos-cuotas
git push --set-upstream origin feature/contratos-cuotas

# Pagos y Recibos PDF
git checkout main
git pull origin main
git checkout -b feature/pagos-recibos
git push --set-upstream origin feature/pagos-recibos

# Tickets de Mantenimiento
git checkout main
git pull origin main
git checkout -b feature/tickets-mantenimiento
git push --set-upstream origin feature/tickets-mantenimiento

# Reportes y Dashboard
git checkout main
git pull origin main
git checkout -b feature/reportes-dashboard
git push --set-upstream origin feature/reportes-dashboard

# Backup y Auditoría
git checkout main
git pull origin main
git checkout -b feature/backup-auditoria
git push --set-upstream origin feature/backup-auditoria



## 🔹 Instalación local

1. Clonar el repositorio:
bash
git clone https://github.com/TU_USUARIO/Alquila360.git
2. Entrar en el directorio:

cd Alquila360


3.Instalar dependencias del backend:

cd backend
npm install


4. Instalar dependencias del frontend:

cd ../frontend
npm install


5. Crear un archivo .env basado en .env.example con tus variables de entorno (DB, JWT, etc.).

Correr backend:

cd ../backend
npm run start:dev


Correr frontend:

cd ../frontend
npm run dev
