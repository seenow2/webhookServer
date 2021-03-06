# webhookServer
# A simple demo by django to recieve alerts from promethues and show them in web.

$ usage: docker run -it -p 8000:8000 seenow888/django-webhook:seenow /bin/bash 
# After docker is run, attach it 
$ cd /srv/webhk 
$ python manage.py runserver 0.0.0.0:8000 
# then , you can browse in IE : http://hostIP:8000/index
