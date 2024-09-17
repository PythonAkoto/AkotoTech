# Akoto Tech
Lets help the world with lines of code!

This is a simple application designed to showcase the various projects I am currently working on, as well as some legacy projects from over the years.

This is a web app that uses the Flask framework for the backend and Vanilla JS for the frontend.


# Requirements
Create a virtual envrionment by typing the following in the terminal:
```
python -m venv venv
```

Activate the vertual environment:
```
venv\Scripts\activate       # Windows
source venv/bin/activate    # macOS / OS X / Linux
```

`pip -r requirements.txt` to install the required libraries.

You also need to create a `Profile` with the following:
```
web: gunicorn main:app
```


To run the app 