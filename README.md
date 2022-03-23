# touch-gloves

## Step 0: Clone this repo

## Step 1: Once you've cloned this repo onto your local machine, you need to first start the virtual environment:

> python3 -m venv .venv
> source .venv/bin/activate

## Step 2: To setup your own virtualenv when cloning this repo which has the dependencies saves as part of the requirements.txt file:

> pip install -r requirements.txt

## Step 3: Upgrade pip and install flask inside your virtualenv:

> python -m pip install --upgrade pip
> python -m pip install flask
> python -m flask run


### If you run into weird server process already running type errors, run the following line to map your port to 80 instead:
> python -m flask run --host=0.0.0.0 --port=80

## Step 4: Ready to exit your virtual environment after saving your work? To Stop building the app:

> Ctrl+C in the terminal.

### Best practices during app development:

Depedencies management best practices.
While I was still in my .venv, I ran the following command in my terminal to "freeze" the dependencies.
How? In your terminal environment - still in venv run:

> pip freeze > requirements.txt
