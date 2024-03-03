# Movie-Rater-API

## Windows. Run the server
- Open powershell in the project folder and run the following commands to setup the environment and run the server. Make sure you have python installed on your machine. If not, you can download it from [here](https://www.python.org/downloads/);
- Setup environment;
```bash
python -m venv env
```
- Install Django
```bash
pip install django
```
- Install Django Rest Framework
```bash
pip install djangorestframework
```
- Install corsheaders
```bash
pip install django-cors-headers
```
- Activate environment
```bash
env\Scripts\activate
```
- Run server
```bash
python manage.py runserver
```
- Or run the server available to the network (mobile development, for example)
```bash
python manage.py runserver 0.0.0.0:8000
```
- Deactivate environment
```bash
deactivate
```
- Create superuser
```bash
python manage.py createsuperuser
```
## Linux. Run the server
- Open terminal in the project folder and run the following commands to setup the environment and run the server. Make sure you have python installed on your machine. If not, you can download it from [here](https://www.python.org/downloads/);
- Setup environment
```bash
python3 -m venv env
```
- Install Django
```bash
pip3 install django
```
- Install Django Rest Framework
```bash
pip3 install djangorestframework
```
- Install corsheaders
```bash
pip3 install django-cors-headers
```
- Activate environment
```bash
source env/bin/activate
```
- Run server on the localhost
```bash
python3 manage.py runserver
```
- Or run the server available to the network (mobile development, for example)
```bash
python3 manage.py runserver 0.0.0.0:8000
```
- Deactivate environment
```bash
deactivate
```
- Create superuser
```bash
python3 manage.py createsuperuser
```
