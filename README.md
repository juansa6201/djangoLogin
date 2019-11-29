# Simple login template

Este es un login con redireccion creado con Django para registrar a los usuarios que se conectan a la red para posteriormente poder administrarlos, ya sea denegandoles el acceso, bloqueandoles algunios sitios y demas controles.

## Pasos para correr el sistema.

### Crear un virtualenvironment y correr los siguientes comandos:

1) ``` pip install -r requirements.txt ```

2) ``` python3 manage.py migrate ```

3) ``` python3 manage.py createsuperuser ```

4) ``` python3 manage.py runserver 0.0.0.0:8000```