
![Build Status](https://travis-ci.org/JeanneBM/PyCalculatorBlack.svg?branch=master)
[![Coverage Status](https://coveralls.io/repos/github/JeanneBM/PyCalculatorBlack/badge.svg?branch=master)](https://coveralls.io/github/JeanneBM/PyCalculatorBlack?branch=master)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Python 3.8](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-360/)

# PyCalculator  

The application is a simple tool for performing basic arithmetic operations. 

The user has 4 operations to choose. 
```
MENU:
1 - Addition 
2 - Subtraction
3 - Multiplication 
4 - Division
```

3 tool forms are available:
- REST API from http://localhost:5000
- From the terminal, built on:
  * class
  * loop if 

## Containers
```
sudo docker build Dockerfile
sudo docker container run -it --name name_of_a_container image_ID
```

## Tests

Commands:
```
pytest
python3 -m unittest
```


## Running gunicorn server
```
gunicorn --bind 0.0.0.0:5000 wsgi:app
```


## Black
```
black a_file_name.py
```
