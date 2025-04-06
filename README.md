# 🧠 Task Manager en Django

Proyecto de práctica para aprender desarrollo backend con Python y Django.  
Permite gestionar tareas con funciones básicas de creación, visualización y administración desde el panel de Django o vistas web.

---

## 🚀 Funcionalidades

- Modelo `Task` con campos: título y estado (completado)
- Vista web para mostrar todas las tareas (`/tasks/`)
- Admin de Django habilitado (`/admin`)
- Template HTML funcional con bucles de renderizado
- Estructura escalable para añadir formularios y estilos

---

## 🛠 Tecnologías utilizadas

- Python 3.13
- Django 5.2
- SQLite3
- HTML5 (Django templates)
- Git & GitHub

---

## 📦 Instalación y uso local

1. Clona el repositorio:

```bash
git clone git@github.com:SaicoBys/task_manager.git
cd task_manager
```

2. Activa el entorno virtual:

```bash
source env/bin/activate
```

3. Ejecuta el servidor:

```bash
python manage.py runserver
```

4. Abre el navegador en:

- [http://127.0.0.1:8000/tasks/](http://127.0.0.1:8000/tasks/)
- [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)

---

## 📌 Estructura del proyecto

```bash
task_manager/
├── task_manager/          # Configuración principal
├── tasks/                 # App de gestión de tareas
│   └── templates/
│       └── tasks/
│           └── task_list.html
├── manage.py
├── requirements.txt
├── .gitignore
├── README.md              # Versión pública
└── DEV_NOTES.md           # Bitácora personal
```

---

## 📈 Próximos pasos

- [ ] Crear tareas desde el sitio web
- [ ] Añadir botones de completado
- [ ] Mejorar diseño visual
- [ ] Dockerizar la app
- [ ] Subir a producción y conectar con [saicobys.me](https://saicobys.me)

---

## 👤 Autor

**Jacob M. (@SaicoBys)**  
Desarrollador en formación, compartiendo su camino de aprendizaje.