# Blogging Bench

Blogging bench is a basic flask app just for understanding basics of flask.
Purpose of this app is basic authentication and creating posts with very basic minimal UI.

[Live Preview](https://flaskr-blog-app.herokuapp.com "Blogging Bench") is available, hosted on heroku.

Git clone the repo to find the structure of the app.

#### Prerequisites and version used during development of this project
>1. Env  
>2. Python   '3.8'  
>3. Flask    '1.1.2'  
>4. Pip      '21.1.1'  
>5. Pytest   '6.2.3'  
>6. Coverage '5.5'  
>7. Sqlite3

**Follow this for basic setup installation guide(not pytest and coverage) [Installation Guide](https://flask.palletsprojects.com/en/1.1.x/installation/#installation)**

**For Pytest and coverage run**

```pip install pytest coverage```

##### Commands to make this up and running

> For OsX or Linux/Ubuntu

```
export FLASK_APP=app
export FLASK_ENV=development
flask run
```

> For Windows
```
set FLASK_APP=app
set FLASK_ENV=development
flask run
```

##### Commands to test
```
coverage run -m pytest
```

Thanks 🙏

Plug play and enjoy 😉
