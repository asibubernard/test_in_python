# 100% Test Coverage In Python
1. Python 3 >=

2. Pipenv    # virtual environment 
3. Unittest
        pipenv install unittest2 
        python test_app.py  # run test

4. Pytest
        pipenv install pytest
        pytest   # run test
        pytest -v  # Records 
    
5. Coverage
        pipenv install coverage
        coverage run app.py  # run test
        coverage report    
        coverage report - m   # shorthand for missing fields 
        coverage html    # open html to view records in browser.

6. Pytest-cov
        pipenv install pytest-cov
        pytest -v --cov=app
        pytest -v --cov=app --cov-report=html

