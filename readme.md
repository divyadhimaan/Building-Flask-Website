Building a simple flask website


Create a virtual Environment

1. installing virtual environment module -> `pip install virtualenv`
2. activate virtual environment -> `.\env\Scripts\activate.ps1 `

In case you see an error (restriction error)
go to powershell admin > run `Set-ExecutionPolicy unrestricted`

Install packages

1. `pip install flask`
2. create a file 'app.py'
write the boiler plate code


        from flask import Flask
        app = Flask(__name__)

        @app.route('/')
        def hello_world():
            return 'Hello, World!'

Voila! Your minimal flask application is ready.

Run python app.py 
