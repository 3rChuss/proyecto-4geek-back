# Proyecto final 4Geeks Academy
@Jesus Abril

## Iniciar un proyecto desde 0 con python 🐍 y flask 🌶
> Pasos previos
> 1. Crear nuestro repositorio en git y una carpeta en nuestra máquina para alojar el proyecto.
> 2. Instalar python en nuestra maquina y pip (en gitpod no hace falta). [Manual para windows/linux/mac](https://tecnonucleous.com/2018/01/28/como-instalar-pip-para-python-en-windows-mac-y-linux/)
> 3. Instalar el entorno virtual (pipenv o venv).
> > python 3 -m venv .venv (iniciar con _linux_ *source venv/bin/activate* | _windows_ *venv/scripts/activate*).
> > *gitpod* pipenv shell (esto creara nuestro entorno virtual y se iniciará).


## 1. Instalar paquetes
Ya con el entorno virtual funcionando, vamos a ejecutar los siguientes comandos.
```python
pipenv install flask Flask-JWT flask-sqlalchemy sqlalchemy flask-migrate psycopg2-binary python-dotenv flask-cors gunicorn cloudinary flask-admin flask_swagger
```
Añadimos una variable de entorno
`export FLASK_APP=mySuperapp/wsgi.py `