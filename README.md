# Documentation #

## Introduction ##

This project is the solution to a programming task given to me by Unisport A/S as part of the job interviews.

The project required me to make simple python webservice that lists products using data available at this link: http://www.unisport.dk/api/sample/

The project would have a view of the list of all the products, a list for all the kids project as well as a page system for the two lists and lastly a view of individual products.

To make this webservice I used the Django web framework which provides many useful functions for both testing the webservice and deploying it.

## Required dependencies ##

This is a list of dependencies required to run the program as well as instructions on how to install them.

#### Python 2.7.X ####

The program is made to be used with Python 2.7.X. If you dont have Python 2.7.X installed on your system you can download the latest version here: https://www.python.org/downloads/ .
Make sure that you download Python 2.7.X and not the newer Python 3.X.X.

#### Django 1.11.1 ####

The program is made using the Django web framework.
The easiest way to install the framework is by using pip which is bundled together with Python 2.7.X.
To install Django 1.11.1 open a command prompt or terminal and type:

```
pip install Django==1.11.1
```

Other ways to get Django installed can be found on their website: https://www.djangoproject.com/download/

## Usage ##

To view the webservice on a local server you can through your command prompt or terminal navigate to the directory containing the manage.py file and input the following command:

```
python manage.py runserver
```

This will make it possible to open your browser and access the webservice through the URL http://127.0.0.1:8000/

To run the tests you can again use your command prompt or terminal and again navigate to the same directory as the manage.py file and run the following command:

```
python manage.py test
```

Once you have accessed the webservice through your browser you should then be redirected to the /products/ view and from there you can follow the links to either view the kids only products, the inidividual products or the next/previous page of the list.

## File documentation ##

In the sea of files auto generated by Django these are the ones that I have modified/created and are the ones that control the behaviour and appearance of the webservice.

#### sample/urls.py ####

#### products/urls.py ####

#### products/views.py ####

#### products/tests.py ####