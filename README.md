# To run this projects please follow below instructions

## Install django in ubuntu
```
sudo apt install python3-django
django-admin --version
```

## Setup the environment or otherwise you can run python3
```
python3 -m venv myenv
source myenv/bin/activate
```

## Now, Create a projects

```
django-admin startproject myprofile
cd myprofile
python manage.py migrate 
python manage.py runserver 10.11.105.101:8000
```
