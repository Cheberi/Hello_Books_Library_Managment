[![Build Status](https://travis-ci.org/ezrqnkemboi/hello_books.svg?branch=master)](https://travis-ci.org/ezrqnkemboi/hello_books)
[![Coverage Status](https://coveralls.io/repos/github/ezrqnkemboi/hello_books/badge.svg?branch=master)](https://coveralls.io/github/ezrqnkemboi/hello_books?branch=master)
[![Maintainability](https://api.codeclimate.com/v1/badges/b92c5e43d5de4be7085b/maintainability)](https://codeclimate.com/github/ezrqnkemboi/hello_books/maintainability)

# Hello_Books API    

Hello-Books is a simple application that helps manage a library and its processes like stocking, tracking and renting books. With this application users are able to find and rent books. The application also has an admin section where the admin can do things like add books, delete books, increase the quantity of a book etc.

# Api Documentation

   http://hellobooks6.docs.apiary.io
   
# API Endpoints
|Endpoint                            | Functionality                    |HTTP method 
|------------------------------------|----------------------------------|-------------
|/books                       |Add a book                        |POST        
|/books/*book_id*             |modify a book’s information       |PUT
|/books/*book_id*             |Remove a book                     |DELETE
|/books                       |Retrieves all books               |GET
|/books/*book_id*             |Get a book                        |GET
|/users/books/*book_id*       |Borrow a book                     |POST
|/users/books/*book_id*       |Return a book                     |PUT
|/users/books                 |Get User borrowing history        |GET
|/users/books?returned=false  |Get books not yet been returned   |GET 
|/auth/register               |Creates a user account            |POST
|/auth/login                  |Logs in a user                    |POST
|/auth/logout                 |Logs out a user                   |POST
|/auth/reset-password         |Password reset                    |POST


   
# Installing Application and Running

   Clone the repo:   https://github.com/ezrqnkemboi/hello_books.git
   
   Then, install virtual environment: `pip install --user pipenv`
   
   Cd to the directory of the application through: `cd hello_books`
   
   Install virtual env requests: `pipenv install requests`
   
   Install all the dependencies through: `pip install -r requirements.txt`
   
   Activate the virtual environment: `pipenv shell`
   
   Run application: `python run.py`
   
# Running tests
   
   Cd to the directory of the application through: `cd hello_books`
   
   To run test, use: `coverage run -m unittest discover`
   
# Deployment Link
   Link: https://stark-falls-93345.herokuapp.com
   
# Designs Link
   Link: https://ezrqnkemboi.github.io/hello_books_designs/

# Contributors
   Ezrqn Kemboi
# Acknowldgement
   Andela Kenya Project
