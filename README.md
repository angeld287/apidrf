# apidrf

Django Rest Framework

Esto es un ejemplo de servicio Rest en Django creado desde la pagina oficial http://www.django-rest-framework.org/#installation. El ejemplo se desarrollo en un ambiente de linux, a continuacion se describen las dependencias y los pasos de configuracion:

1- Python version: python2.7

2- System dependencies
    python pip: 

      sudo apt install python-pip

    virtualenv: 

      pip install virtualenv

  Configuration
  
  1- git clone https://github.com/angeld287/apidrf

  2- virtualenv env
  3- source env/bin/activate

  4- pip install django
  5- pip install djangorestframework
  6- pip install pygments

  7- pip install django-cors-headers
  
  8- edit de file apidrf\apidrf\settings.py to alow de your host.
  
      ALLOWED_HOSTS = ['localhost']
  
  9- cd apidrf
  
  10- python manage.py runserver
  
  ![](https://github.com/angeld287/apidrf/blob/master/img/1.png)  
  

