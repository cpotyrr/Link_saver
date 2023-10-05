
# **Links register app**


## :construction: Install

*  Create virtual enviroment for application

```sh
python3 -m venv myvenv
```

* Download packages from requirements.txt

```sh
pip install -r requirements.txt
```

* Configure your redis-server configuration inside `link_saver.settings`
    * REDIS_HOST - Host of redis
    * REDIS_PORT = Port of redis


## :rocket: Usage

```sh
python manage.py runserver
```

## :white_check_mark: Run tests

```sh
python manage.py test
```

