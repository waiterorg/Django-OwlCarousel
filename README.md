# Django-OwlCarousel

...
virtualenv .venv
source .venv/bin/activate
pip install -r requirements.txt
cd SlideShow
pyhton manage.py createsuperuser
python manage.py runserver
...

# For Login With Google
go http://127.0.0.1:8000/admin/
under Social Applications click Add and fill in the details

    Provider: Google
    Name: OAuth App
    Client id: <The client ID in google>
    Secret key: <The Secret key in google>
    Sites: 127.0.0.1:8000
