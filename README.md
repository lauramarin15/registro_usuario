## Requisitos
- Python 3.10 o superior
- pip
- postgresql
- virtualenv / venv

## Clonar el repositorio
git clone https://github.com/lauramarin15/registro_usuario.git
cd registro_usuario

## entorno virtual en manage.py
python3 -m venv venv
source venv/bin/activate

## instala django
pip install django

## migraciones en manage.py
python manage.py makemigrations
python manage.py migrate

## ejecuta el servidor 
python manage.py runserver

## navegador 
http://127.0.0.1:8000/