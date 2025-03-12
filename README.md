<div align='center'>
<h1>Django and React Authentication</h1>
</div>

# 1. **Environment and Django setup**
    
- *create environment*

    ```python -m venv env```

- *Install Dependencies*

    - django
    - django-rest-framework (https://www.django-rest-framework.org/)
    - django-cors-headers (https://pypi.org/project/django-cors-headers/)
    - djangorestframework-simplejwt (https://django-rest-framework-simplejwt.readthedocs.io/en/latest/)


    ```pip install Django djangorestframework django-cors-headers djangorestframework-simplejwt PyJWT```

- *Activate environment*
    
    ```env/Script/activate```

- *Create Project and App*
    
    - Project name "backend"

    ```django-admin startproject backend```

- *Create requirements.txt for hosting purposes*

    ```pip freeze > requirements.txt```

- *Create an app in the backend project called users*

    ```python manage.py startapp users```