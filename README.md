# To-Do List – Gestión de Tareas Full Stack

Este proyecto es una aplicación Full Stack para la gestión de tareas, donde los usuarios pueden crear, listar, marcar como completadas, editar y eliminar tareas.
El backend está construido con Node.js + Express y utiliza PostgreSQL como base de datos alojada en Railway.

Tecnologías Utilizadas
Área	Tecnologías
Backend	Node.js, Express, CORS, Dotenv, PostgreSQL
Base de Datos	PostgreSQL en Railway
Frontend (Pendiente)	HTML, CSS, JavaScript o React
Control de Versiones	Git + GitHub
Deployment	Railway

--- 

## Variables de Entorno (Railway / .env.local)

Debes crear un archivo .env.local o variables en Railway con las siguientes claves:

DB_HOST=tramway.proxy.rlwy.net
DB_USER=root
DB_PASSWORD=AXTxLbdYRDhKbCjCcGiuiLkjuWwmuglD
DB_NAME=railway
DB_PORT=35810

---

## Endpoints de la API
Método	Endpoint	Descripción
GET	/tasks	Obtener todas las tareas
POST	/tasks	Crear nueva tarea { title: "" }
PUT	/tasks/:id/complete	Marcar tarea como completada
DELETE	/tasks/:id	Eliminar una tarea

Ejemplo de JSON creado:

{
  "id": 1,
  "title": "Mi primera tarea",
  "completed": false
}

## Cómo Ejecutar el Backend Localmente

Clona el repositorio:

git clone https://github.com/sebastianmanriquetorres/todo_list.git
cd todo_list/backend


Instala dependencias:

npm install


Crea tu archivo .env.local y agrega tus credenciales.

Ejecuta el servidor:

npm run dev

## Deploy en Railway

El backend está configurado para funcionar automáticamente con las variables de entorno.

Solo necesitas:

Conectar el repositorio

Agregar las variables de entorno

Railway deploya automáticamente

## Próximos pasos

- Crear interfaz web (frontend)
- Conectar el frontend con el backend mediante fetch/axios
- Estilizar con CSS o frameworks (Tailwind/Bootstrap)

## Autor

Desarrollado por Sebastián Manrique como práctica de desarrollo Full Stack.

GitHub: https://github.com/JuanPabloBeltran/despliegue-todo-juanpablobeltran.git
Netlifly: https://proyecto-sebastian-manrique.netlify.app
Render: https://bd-practicas-despliegue.onrender.com/
