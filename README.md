# Women_Affair_classification
This is simple implementation of logistic Regression classification on Women Affair classification based on the marriage satisfaction , years of marriage, had some affair in past etc.


# Dependencies
    1. Python - Programming Language
    2. Flask - The framework used
    3. scikit-learn - machine learning framework
    4. Pip - Dependency Management

# Virtual environment 
    $ sudo apt-get install python-virtualenv
    $ python3 -m venv venv
    $ . venv/bin/activate
    $ pip install Flask

# Install all project dependencies using:
    $ pip install -r requirements.txt

# Running   
    $ export FLASK_APP=api.py
    $ export FLASK_ENV=development
    $ python -m flask run
    
    This launches a very simple builtin server, which is good enough for testing but probably not what you want to use in production.

    If you enable debug support the server will reload itself on code changes, and it will also provide you with a helpful debugger if things go wrong.

     If you have the debugger disabled or trust the users on your network, you can make the server publicly available simply by adding --host=0.0.0.0 to the command line:
      
      -- flask run --host=0.0.0.0
 
 # running from prompt
    We can use and start the WSGI server using conda/python prompt using 
    
    $ python app.py 
    
    or 
    
    $ python manage.py runserver
      
## Contirbuing 
    This API was developed based on:
    
    1. Flask documentation
    
    2. REST APIs with Flask and Python
    
    3. The Ultimate Flask Course
    
    4. Dataset - https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_boston.html
  
## License
    This project is licensed under the MIT License - see the LICENSE.md file for details

## introduction :
    ### Problem:- to build an end-to-end Flask API for the Prediction of Median value of owner-occupied homes in $1000's.
    -- there are in total we have 13 different features present in the dataset .

## I have collected the dataset from in-built sckit-learn dataset.
   [ https://www.kaggle.com/datasets/iamsouvik/software-requirements-dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_boston.html)
    ### Preprocessing and visualize is taken place and tried to present a way for feature selection , cross validation, building confusion matrix.
          
## Machine Learning supervised model strategy 
   the project is built in the prospect to learn about logistic regression , implemented the model and used hyper-parameter tuning in order to improve the accuracy.




