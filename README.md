# Spam and ham detection

requirement libraries are included in [requirements.txt](https://github.com/armando013005/ML-SPAM/blob/main/requirements.txt)

## Python 3.11.9 is required to run TensorFlow

### downloading different python version

to install a different python version inside the virtual environment go to [python downloads](https://www.python.org/downloads/) and download the version 3.11.9 in a directory that is comfortable for you, I prefer to install it directly on C:/

>DO NOT add this version to PATH

### Loading different version in a virtual environment

It is important to load the python version in the virtual environment to prevent global malfunctions

open the terminal of your preference, I personally use PowerShell inside VSCode, and then follow the next steps

- first install virtualenv globally

    `pip install virtualenv`

- After creating the virtual environment run the next line:

    `virtualenv --python="/usr/bin/python3.11" "/path/to/new/virtualenv/"`

    the first variable being the of the required version and the second variable being the path where the virtual environment will be set up ( usually `/venv`)

- finally, just activate the virtual environment with:
    `venv/Scripts/activate`

### Installing libraries from the .txt

to install the requirements, make sure that your virtual environment is activated the console tells you by displaying a text like this `(venv)` before every line

run:
`pip install -r requirements.txt`
to install the necessary libraries
