# To-Do List – Gestión de Tareas Full Stack


## 📌 Descripción del Proyecto

Este repositorio contiene el **Frontend** de la aplicación **To-Do List**, una interfaz web que permite a los usuarios gestionar sus tareas de manera sencilla e intuitiva.

El frontend consume una **API REST** desarrollada con Node.js y Express, permitiendo:

* Crear tareas
* Listar tareas
* Marcar tareas como completadas
* Editar tareas
* Eliminar tareas

La aplicación se encuentra desplegada en **Netlify** y se comunica con el backend desplegado en la nube.

---

## 🧰 Tecnologías Utilizadas

* **HTML5**
* **CSS3**
* **JavaScript**
* **Fetch API** (consumo del backend)
* **Netlify** (despliegue)
* **Git & GitHub**

---

## 🗂️ Estructura del Proyecto

```
frontend/
│
├── index.html
├── styles.css
├── script.js
├── README.md
```

---

## ⚙️ Requisitos Previos

Para ejecutar este proyecto necesitas:

* Navegador web moderno
* Git
* Backend en funcionamiento (local o en producción)

---

## 🔗 Conexión con el Backend

El frontend se conecta a la API REST del backend mediante **fetch**.

Ejemplo de URL del backend:

```
https://bd-practicas-despliegue.onrender.com
```

Desde el archivo `script.js` se realizan las peticiones HTTP a los distintos endpoints.

---

## 🌐 Endpoints Consumidos

* `GET /tasks` → Obtener todas las tareas
* `POST /tasks` → Crear una nueva tarea
* `PUT /tasks/:id/complete` → Marcar tarea como completada
* `PUT /tasks/:id` → Editar tarea
* `DELETE /tasks/:id` → Eliminar tarea

---

## ▶️ Ejecución en Local

### 1️⃣ Clonar el repositorio

```
git clone https://github.com/JuanPabloBeltran/despliegue-todo-juanpablobeltran.git
```

### 2️⃣ Acceder al proyecto

```
cd despliegue-todo-juanpablobeltran
```

### 3️⃣ Ejecutar el frontend

Puedes abrir directamente el archivo `index.html` en tu navegador o usar una extensión como **Live Server**.

---

## ☁️ Despliegue en Netlify

El frontend está desplegado en **Netlify**.

Proceso de despliegue:

1. Conectar el repositorio a Netlify
2. Seleccionar la carpeta raíz del proyecto
3. Netlify realiza el deploy automáticamente

🌐 **Sitio en producción:**

[https://proyecto-juanbeltran.netlify.app/](https://proyecto-juanbeltran.netlify.app/)

---

## 📌 Estado del Proyecto

* ✅ Interfaz funcional
* ✅ Conexión con API REST
* ✅ Despliegue en producción
* 🔄 Posibles mejoras visuales

---

## 🚀 Próximas Mejoras

* Mejorar diseño y experiencia de usuario
* Agregar validaciones en formularios
* Manejo visual de errores
* Implementar frameworks CSS (Bootstrap / Tailwind)
* Migrar a React

---

## 👨‍💻 Autor

Desarrollado por **Juan Pablo Beltran Rodriguez** como práctica de **Desarrollo Full Stack**.

🔗 **Repositorio Frontend:**
[https://github.com/JuanPabloBeltran/despliegue-todo-juanpablobeltran.git](https://github.com/JuanPabloBeltran/despliegue-todo-juanpablobeltran.git)

🔗 **Repositorio Backend:**
[https://github.com/JuanPabloBeltran/back-todo-juanpablobeltran.git](https://github.com/JuanPabloBeltran/back-todo-juanpablobeltran.git)

☁️ **API en Producción:**
[https://bd-practicas-despliegue.onrender.com/](https://bd-practicas-despliegue.onrender.com/)

