Welcome to my repository and enjoy the lecture

# The game
* To play rock, paper, scissors please run the next command:
```sh
-> cd game
-> python3 main.py
```

# PIP
* Installing libraries is just as easy as
```sh
-> pip install <name of library for example matplotlib>
```
To run the code execute:
```sh
-> cd charts
-> python3 main.py
```
or
```sh
-> cd app
-> python3 main.py
```

# Virtual Environments
Remember: to know all the dependencies you have in your project
you just hace to run
```sh
-> pip freeze
```

* Installing, openning and closing a virtual environment with python in windows
```sh
-> python3 -m venv <environment name>
-> .\<environment name>\Scripts\activate
-> deactivate
```
* Creating the requirements.txt
```sh
-> pip freeze > requirements.txt
```
* Installing the requirements.txt
```sh
-> pip install -r requirements.txt
```

# Rquests
* When you want to make a HTTP request with python this is the library you will use
```sh
-> pip install requests
-> cd web-server
-> python3 main.py
```

# Create your own web server 
You can also create your own web server with Python and Fast API
```sh
-> pip install fastapi
-> pip install "uvicorn[standard]"
-> cd web-server
-> uvicorn main:app --reload
```