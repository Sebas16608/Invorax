# Invorax

## Problema
Muchas pequeñas empresas gestionan su inventario y sus ventas de forma desorganizada, lo que provoca perdidas de tiempo, perdidas de productos, errores en el stock y dificultades para conocer el estado del negocio

## Solucion
Invorax permite gestionar el inventario y las ventas de forma ordenada, rápida y accesible desde cualquier dispositivo con conexión a internet.


# Estructura del Proyecto Actual (version 1)
```bash
├── manage.py
├── invorax
│   ├── asgi.py
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── __pycache__
│       ├── __init__.cpython-312.pyc
│       └── settings.cpython-312.pyc
├── inventory
│   ├── admin.py
│   ├── apps.py
│   ├── __init__.py
│   ├── migrations
│   │   └── __init__.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
├── core
│   ├── admin.py
│   ├── apps.py
│   ├── __init__.py
│   ├── migrations
│   │   └── __init__.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
├── accounts
│   ├── admin.py
│   ├── apps.py
│   ├── __init__.py
│   ├── migrations
│   │   └── __init__.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
├── companies
│   ├── admin.py
│   ├── apps.py
│   ├── __init__.py
│   ├── migrations
│   │   └── __init__.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
├── sales
│   ├── admin.py
│   ├── apps.py
│   ├── __init__.py
│   ├── migrations
│   │   └── __init__.py
│   ├── models.py
│   ├── tests.py
│   └── views.py
└── schema.png ```

utilizando la imagen de referencia para generar las tablas de la Base de Datos
![Schema](backend/schema.png)
