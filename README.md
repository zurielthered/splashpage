# Splash Page
## A splash page for EngSciMath.com

### Configuration

- Clone this repository

- Set environmental variables:
  - `SECRET_KEY` --> `export SECRET_KEY={autogenerated_secret_key}`
  - `SLACK_KEY` --> A slack key for the EngSciMath work station. Ask in #admin if you don't know how to get one!

- Ensure Python is installed. Either 2.7 or 3.6 should work.

- Install pip, then install virtualenv. Create a new virtualenv with the command `virtualenv venv`, then `souce venv/bin/activate`

- At the root of the repository, use the command `pip install -r requirements.txt` to install dependencies.

- Still at the root of the repository, use the command `export FLASK_APP=main.py`.

- We can use `flask run` and an apache proxy for now - setting up NGINX and gunicorn can be a stretch goal or something we do later
