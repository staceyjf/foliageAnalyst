release: python3 manage.py migrate
<!-- delete line 1 potentially after the first git push heroku -->
web: gunicorn foliageanalyst.wsgi --log-file -