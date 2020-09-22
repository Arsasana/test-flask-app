# test-flask-app

Verified to run with Python 3.8 and Flask 0.12.5 and 1.1.2

Within a virtual environment, run
  
      pip install -r requirements.txt
      python runserver.py 

# Creating a Virtual Environment

Use pyenv to create and manage virtual environments

On Mac,

    $ brew install pyenv # this installs pyenv

    $ pyenv install 3.8.2 # this will install python 3.8.2

    $ pyenv local 3.8.2 # this will ensure python is currently set to 3.8.2 installed locally for the user with pyenv

    $ python -V && which python # confirm python version and path

    $ python -m venv venv # create virtual environment
    
    $ source venv/bin/activate # activate virtual environment
    
