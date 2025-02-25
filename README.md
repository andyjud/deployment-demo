#### Demo Deployment Project
Includes<br> 
- django-environ for Enviornment Variables<br> 
- dj-database-url for PostgreSQL connection<br> 
- whitenoise for static files<br> 
- gunicorn for webserver<br> 

<br> <br> 

#### Generate your own Secret Key - ! Important for deployment ! 
```
python manage.py shell
from django.core.management.utils import get_random_secret_key
print(get_random_secret_key())
exit()
```


