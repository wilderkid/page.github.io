### Djanog 

#### start your first project 
`django-admin startproject mysite`

#### start your first app (move to the folder manage.py exist)
`python manage.py startapp polls`

#### move to views.py
``` 
from django.http import HttpResponse

def index(request):

	return HttpResponse('hello world')
```

