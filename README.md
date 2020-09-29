# HACKERSOME-BLOG
## Author

[PatriciaAnduru](https://github.com/PatriciaAnduru)

# Description
Hackersome-blog is a personal blogging website where you can create and share your opinions and other users can read and comment on them. The blog also has random quotes that inspire the users.

## Live Link
[View Site](https://hackersome-blog.herokuapp.com/)


## User Story

* As a user, I would like to view the blog posts on the site
* As a user, I would like to comment on blog posts
* As a user, I would like to view the most recent posts
* As a user, I would like to an email alert when a new post is made by joining a subscription.
* As a user, I would like to see random quotes on the site
* As a writer, I would like to sign in to the blog.
* As a writer, I would also like to create a blog from the application.
* As a writer, I would like to delete comments that I find insulting or degrading.
* As a writer, I would like to update or delete blogs I have created.


## BDD
>Login Inputs

| Inputs |  Description |
| :---         |          ---: |
| Username  | Account username, ``eg johndoe``|
| Password  | Account password, ``eg parseword``|

>Signup inputs

| Inputs |  Description |
| :---         |          ---: |
| Username  | Account username, ``eg johndoe``|
| Email  | User email, ``eg morty@testmail.com``|
| Password  | Account password, ``eg parseword``|
| Confirm Password  | Account password, ``eg parseword``|


> Blog inputs

| Inputs | Description  |
|---|---|
|  Blog title | the title of the blog eg; `` Car news``  |
|  Blog post| The blog post itself|
| Comment| A comment on the blog post|




## Development Installation
To get the code..

1. Cloning the repository:
  ```bash
  https://github.com/PatriciaAnduru/passie-blog.git
  ```
2. Move to the folder and install requirements
  ```bash
  cd passie-blog
  pip install -r requirements.txt
  ```
3. Exporting Configurations
  ```bash
  export SQLALCHEMY_DATABASE_URI=postgresql+psycopg2://{User Name}:{password}@localhost/{database name}
  ```
4. Running the application
  ```bash
  python3.6 manage.py server
  ```
5. Testing the application
  ```bash
  python3.6 manage.py test
  ```
Open the application on your browser `127.0.0.1:5000`.


## Technology used

* [Python3.6](https://www.python.org/)
* [Flask](http://flask.pocoo.org/)
* [Heroku](https://heroku.com)
* [Bootstrap](https://getbootstrap.com/)


## Known Bugs
* There are no known bugs.

## Contact Information 

If you have any question, contributions, or for collaborations please email me at [andurupatricia@gmail.com]

## License
* *MIT License:*
* Copyright (c) 2020 **Patricia Anduru**
