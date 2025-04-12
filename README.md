# 🛒 StockPro - Sistema de Punto de Venta

**StockPro** es un sistema de punto de venta desarrollado en Django. Permite gestionar productos, stock, ventas y usuarios de manera eficiente para pequeños y medianos negocios.

---

## 🚀 ¿Cómo empezar?

### 1. Clonar el repositorio

```bash
git clone https://github.com/usuario/StockPro.git
cd StockPro

2. Crear y activar el entorno virtual

python -m venv venv
source venv/bin/activate  # Linux / Git Bash
venv\Scripts\activate     # Windows CMD

3. Instalar dependencias
pip install -r requirements.txt


4. Correr migraciones y el servidor
python manage.py migrate
python manage.py runserver


💻Equipo de desarrollo
**Misael 

**Gaspar

**Valentin

**Facundo

🔀 Estructura de ramas
main: Rama estable

test: Rama de desarrollo compartido

feature/nombre: Para nuevas funcionalidades

fix/nombre: Para solucionar errores

📦 Estructura del proyecto

StockPro/
├── venv/               # Entorno virtual (ignorado)
├── proyecto/           # Código fuente principal Django
│   ├── manage.py
│   └── proyecto/
│       ├── __init__.py
│       ├── settings.py
│       ├── urls.py
│       └── wsgi.py
└── .gitignore
✅ Buenas prácticas para colaborar
Hacer git pull antes de empezar a trabajar

Usar ramas individuales (feature/nombre)

Escribir mensajes de commit claros

No subir archivos de entorno ni personales (gracias al .gitignore)

🔒 .gitignore sugerido
gitignore
Copiar
Editar
venv/
__pycache__/
*.pyc
*.sqlite3
.env



📢 Licencia
Este proyecto es solo para fines educativos (Tesis) y no tiene una licencia específica por ahora.
