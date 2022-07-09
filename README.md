To run this project, run the following code:



Create a virtual environment
``` bash
$ python3 -m venv venv
$ . venv/bin/activate
```

After setting up virtual environment, run the following command to install the required packages.

``` bash
$ pip3 install -r requirements.txt
```

Run the backend
``` bash
$ export FLASK_APP=app
$ flask run
```

Run the following command to transfer everything to the requirements.txt
``` bash
$ python3 -m pip freeze > requirements.txt
```