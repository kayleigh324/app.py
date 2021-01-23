# app.py
Creating an app using Flask and Python

First setting up folder from terminal using Visual Code Studio

$ cd Desktop
$ mdkir feedback_app
$ cd feedback_app
feedback_app$ 

Now we are in the root of the new folder so we can begin installing the required packages..

feedback_app$ sudo apt install python3-venv
feedback_app$ python3 -m venv feedback_app-env
feedback_app$ source feedback_app-env/bin/activate

Now your terminal should look like this with the virtual environment at the beginning of the $..

(feedback_app-env) feedback_app$

Now to install the rest of the packages..

(feedback_app-env) feedback_app$ pipenv install flask

(feedback_app-env) feedback_app$ pipenv install flask-sqlachemy

(feedback_app-env) feedback_app$ pipenv install gunicorn

(feedback_app-env) feedback_app$ pipenv install psycopg2-binary

Once these are installed we are ready to go!!





