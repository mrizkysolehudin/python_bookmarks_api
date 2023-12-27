


###
source venv/Scripts/activate
deactivate


###
python -m virtualenv venv
pip install flask


source venv/Scripts/activate
export FLASK_ENV=development
export FLASK_APP=app
flask run


export FLASK_APP=src
flask run


pip install python-dotenv
mkdir .flaskenv


















