NeoBarber Backend

Backend del sistema **NeoBarber**, desarrollado con **Node.js, Express y MongoDB**, que permite gestionar usuarios, autenticación, servicios, barberos y citas.

Este repositorio incluye además la **colección de pruebas en Postman** y el **formato de evidencias en Excel** requerido para la actividad del SENA.

---

## 🚀 Tecnologías utilizadas

- Node.js
- Express
- MongoDB (Base de datos NoSQL)
- JWT (Autenticación)
- Postman (Pruebas de API)

---

## ⚙️ Instalación y ejecución

### 1. Clonar el repositorio

```bash
git clone https://github.com/TU-USUARIO/neobarber-backend.git
cd neobarber-backend
2. Instalar dependencias
npm install
3. Configurar variables de entorno

Crear un archivo .env basado en .env.example

Ejemplo:

PORT=3000
MONGO_URI=mongodb://localhost:27017/neobarber
JWT_SECRET=tu_clave_secreta
4. Ejecutar el servidor
npm run dev

El servidor estará disponible en:

http://localhost:3000
🧪 Pruebas con Postman

La colección de pruebas se encuentra en:

postman/neobarber_12_pruebas_.postman_collection.json
Incluye:
12 casos de prueba
CRUD completo del módulo de servicios
Pruebas positivas (correctas)
Pruebas negativas (errores controlados)
Validación de autenticación con JWT
Cómo usarla:
Abrir Postman
Importar la colección
Ejecutar en orden:
1. Login cliente
2. Login admin
3. Crear servicio
4. Obtener barberos
5. Crear cita
📊 Evidencia de pruebas

El formato diligenciado se encuentra en:

evidencia/casos_prueba_neobarber.xlsx
Contiene:
Casos de prueba definidos
Resultados esperados y obtenidos
Pruebas aprobadas
Pruebas fallidas (negativas)
Evidencias para validación
🔐 Funcionalidades del sistema
Registro de usuarios
Inicio de sesión con JWT
Gestión de servicios (CRUD)
Gestión de barberos
Gestión de citas
Control de acceso por roles
🎯 Objetivo del proyecto

Desarrollar y validar una API REST para la gestión de una barbería, aplicando buenas prácticas de desarrollo y pruebas de software mediante herramientas como Postman.

👨‍💻 Autor

Pablo Prado

📌 Notas
Asegúrate de tener MongoDB en ejecución antes de iniciar el servidor
Algunas pruebas requieren usuario administrador previamente creado
Las variables de Postman deben configurarse correctamente para ejecutar todas las prueba
