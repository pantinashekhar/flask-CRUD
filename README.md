# flask-CRUD
It is a simple task master application.

First create static and templates in vscode alongwith app.py file.

All the flask code in python is written in this just log on to virtual environment and keep and main.css in static/css folder while templates will have base.html which is the base file 
where you can have the html boilerplate extension in vscode and created over that.Rest index.html and update.html extends base.html,both files to be kept in templates.

After logging into virtualenv using
pip install virtualenv
virtualenv test
test\Scripts\activate

Then run python app.py  but before that you need to have a db created so the code is written but there might be requirement for you to put the following in python prompt
from app import app,db
app.app_context().push()
db.create_all()
Once test.db is created in sqlite you can run python app.py and delete or update the task master.




