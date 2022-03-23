# touch-gloves

## To Start building the App do the following:

python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install flask
python -m flask run
python -m flask run --host=0.0.0.0 --port=80

To Stop building the app:

1. Stop the app by using Ctrl+C in the terminal.

Best practices during app development:
Depedencies management best practices.
While I was still in my .venv, I ran the following command in my terminal
pip freeze > requirements.txt
