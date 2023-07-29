# Code Institute

to get it running:

(1 and 2 will be done automatically in gitpod)

1.
```
pip install -r requirements.txt
```

2.
```
pip install --no-binary :all: psycopg2
```

3.
remove .env-sample to .env file and add secret keys

4.
run styling with `npm run styling` and run the server with `npm run server`

5.
add your host to the allowed hosts in `/boutique_ado/settings.py`

6.
to load fixtures run `python3 manage.py loaddata categories` and then `python3 manage.py loaddata products`