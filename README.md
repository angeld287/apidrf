# apidrf

Django Rest Framework

Esto es un ejemplo de servicio Rest en Django creado desde la pagina oficial http://www.django-rest-framework.org/#installation. El ejemplo se desarrollo en un ambiente de linux, a continuacion se describen las dependencias y los pasos de configuracion:

1- Python version: python2.7

2- System dependencies
      python pip: 

            sudo apt install python-pip

      virtualenv: 

            pip install virtualenv

 3- Configuration
  
        git clone https://github.com/angeld287/apidrf

        virtualenv env
        source env/bin/activate

        pip install django
        pip install djangorestframework
        pip install pygments

        pip install django-cors-headers
  
  
    Editar el archivo apidrf\apidrf\settings.py para que el proyecto permita el host
  
        ALLOWED_HOSTS = ['localhost']
  
        cd apidrf
  
        python manage.py runserver
  
  ![](https://github.com/angeld287/apidrf/blob/master/img/1.png)  
  

