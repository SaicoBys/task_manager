# 🗂️ Bitácora Personal – Task Manager

## 🧠 Propósito
Proyecto guiado para aprender el desarrollo backend con Django, estructuración de vistas, modelos, templates y conexión con GitHub.

---

## 📅 Última sesión: 6 de abril de 2025

---

## 🛠️ Comandos usados

```bash
# Crear entorno virtual
python3 -m venv env
source env/bin/activate

# Instalar Django y guardar dependencias
pip install django
pip freeze > requirements.txt

# Iniciar proyecto Django
django-admin startproject task_manager .

# Crear la app principal
python manage.py startapp tasks

# Migraciones
python manage.py makemigrations
python manage.py migrate

# Crear superusuario
python manage.py createsuperuser

# Iniciar servidor
python manage.py runserver
```

---

## 🚧 Tareas pendientes

- [x] Crear modelo `Task`
- [x] Vista `task_list`
- [x] Template `task_list.html` funcional
- [x] Panel de administración configurado
- [x] Conectar vistas con URLs
- [x] Subida a GitHub con SSH
- [x] Estructurar repositorio con README y notas personales
- [ ] Crear formulario para añadir tareas desde el navegador
- [ ] Estilo visual con CSS
- [ ] Marcar tareas como completadas desde la vista
- [ ] Dockerizar el proyecto
- [ ] Hacer deploy a producción
- [ ] Conectar dominio saicobys.me

---

## 💬 Notas personales

- Empecé este proyecto guiado para entender Django desde cero.
- Me gustó ver que puedo crear modelos y mostrarlos en el navegador.
- El admin de Django es muy poderoso para pruebas iniciales.
- Próxima meta: agregar formularios funcionales y estilos.
