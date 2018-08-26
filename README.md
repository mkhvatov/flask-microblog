# Flask Microblog

This microblog was made based on the [Miguel Grinberg Flask Tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world).

The microblog allows you create your own account, write short messages (no more than 140 symbols), follow and unfollow other users.

To see and write messages you need to be registered and logged in.

# How to use

## The example on Heroku

[You can see the example on Heroku](https://mkhvatov-microblog.herokuapp.com/)

## Install virtual environment and requirements

``` #!bash

virtualenv -p python3 env
source env/bin/activate
pip install -r requirements.txt
```

## Upgrade the database migrations

This step you need to do only when you start the application for the first time.

``` #!bash

flask db upgrade
```

## Run local sever

``` #!bash

export FLASK_APP=microblog.py
flask run
```

Open [http://127.0.0.1:5000/](http://127.0.0.1:5000/)

# Project Goals

The code is written for educational purposes.