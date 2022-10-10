# Steps to create basic flask-template

Always use CMD for commands execution

python -m venv flask-template
flask-template\Scripts\activate 
pip install Flask twilio
cd flask-template
pip freeze > requirements.txt
pip install -r requirements.txt
mkdir app
cd app
mkdir templates
mkdir static

Before runing application

set FLASK_APP=app
set FLASK_ENV=development
flask run