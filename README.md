# Chatroom Application

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)

## What is this application?
This is a chatroom website which enables users to enter chatrooms with other users and send messages to each other in real-time.

## Choice of programming languages and frameworks

The website was primarily made using Python and more specifically, Django as my backend framework of choice. Django was chosen for several reasons:
- Django has a more structured and opinionated approach to web development compared to other similar frameworks like Flask. This can make it easier to build maintainable and scalable applications, which is important for adding functionality.
- Even though Django is quite monolithic, Django follows a "batteries included" philosophy, which means it comes with a lot of functionality out of the box. 
- Django has a robust set of features and tools for building web applications, including an ORM (Object-Relational Mapper) for interacting with databases, a template engine for building views, and a built-in user authentication system. These features helped me build a full-featured chat application more quickly and easily.

The user and messages were stored in a SQLite database, with the front-end of the program being written in HTML and the jQuery framework. The jQuery framework was crucial in delivering the asynchronoux JavaScript to display messages in the chat rooms.


python manage.py runserver
./manage.py migrate

python manage.py migrate chatroom zero 
