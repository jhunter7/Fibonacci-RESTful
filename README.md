# Fibonacci-RESTful
This is the documentation which reviews the process of deploying a RESTful webservice which will accept input then return the corresponding Fibonacci numbers. 

This assignment was built on the Flask RESTful endpoint 
The functions are inputed via http address

Example:
http://localhost:5000/fibonacci?start=0&length=5
start= the start of the index of the corresponding sequence. Default is 0

length= the range of the Fibonacci sequence. The provided address length of 5, will return the sequence [0, 1, 1, 2, 3]

If the provided length is a negative number, the service will respond with a JSON error

## Installation instructions:

Create the following directories and move the corresponding .py files below the main structure: 
./endpoints/fibonacci_service_flask.py
./fibonacci/fibonacci.py
./tests/__init__.py

## run the setup
python setup.py develop

## Start the Microservice:
python endpoints/fibonacci_service_flask.py

## Execution of test cases:
python -m unittest tests
