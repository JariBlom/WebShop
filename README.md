# WebShop
Surffin webshop

Om de website te kunnen runnen moet python geinstalleerd zijn en in je path staan, in ubuntu gebeurd dat standaard, voor Mac zou ik deze link volgen om het zo Linux-like mogelijk aan te kunnen pakken:
https://docs.python-guide.org/starting/install3/osx/

Dan is het het makkelijkst om het volgende te typen in een command prompt:
$ pip install virtualenv

Vervolgens vanuit de directory 'Webshop/django-ecommerce-wagtail':
$ source env/bin/activate

Als het goed is kun je nu de volgende dingen doen:
$ python manage.py makemigrations
$ python manage.py migrate
$ python manage.py runserver

Volg vervolgens de link die verschijnt in de command line naar je lokaal gehoste website!
Credits naar:
Charles Ouellet
Hier vind je zijn tutorial, waar dit skelet vandaan komt
https://snipcart.com/blog/django-ecommerce-tutorial-wagtail-cms


