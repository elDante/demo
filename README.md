# demo

### Installation
1. copy `demo/settings_local.example.py` to `demo/settings_local.py`
2. fill `demo/settings_local.py`
3. `python manage.py migrate`
4. `python manage.py collectstatic`
5. use `demo/wsgi.py` for uwsgi
