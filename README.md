# BOOK REVIEW 
<hr/>
<br/>

## PROJECT SCREENSHOT
>   here screen are comes

## CREATING FASK SERVER 
### Create server syntax 
```
from flask import Flask
app = Flask(__name__)

@app.route('/')
def hello_world():
    return 'Hello, World!'
```
### Run server command 
*   on linux export appName.py
```
$ export FLASK_APP=main.py
$ export FLASK_ENV=development
$ flask run
```
*   on window we need to set environment variable ps is powershell make sure venv is activated 
```
(venv) PS > $env:FLASK_APP = "app.py"
(venv) PS > $env:FLASK_ENV= "development"    # optional
(venv) PS > flask run
```

## DATABASE 
### postgres vs mysql 
*   postgres
    -   PostgreSQL is an object-relational database management system (ORDBMS) based on postgres
    -   based on object data model
    -   support sql structure-query-language
    -   docs: [![what is postgres]](https://www.postgresql.org/docs/13/intro-whatis.html)
    -   ORDBMS vs OODBMS
        --   OODBMS - object oriented database management system 
        --   OODBMS aimed at applications where an object-centric viewpoint is appropriate, mainly used in cpp or java
        --   ORDBMS focus on large data collections 
*   mysql   
    -   Mysql is an relational database management system (RDBMS) based on sql 
    -   based on relational data model
    -   docs: [![what is msql](https://dev.mysql.com/doc/refman/8.0/en/what-is-mysql.html)]
    -   RDBMS vs ORDBMS
        --  RDBMS stores only data.
        --  ORDBMS Stores data as well as methods to use it.
        --  ORDBMS Handles larger and complex data than RDBMS.

>   mongodb
    -   MongoDB is a document oriented database management system
    -   based on document data model
    -   use MongoDb query language (mql) does not support sql
    -   docs: [![what is mongodb](https://docs.mongodb.com/manual/introduction/)]
### postgres sql commong syntax 
*   heroku used for getting db based on postgres
    -   
### object relational mapping 
*   
    -
