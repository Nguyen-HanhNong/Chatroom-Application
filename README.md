# Chatroom Application

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)

## What is this application?
This is a chatroom website that enables users to enter chatrooms with other users and send messages to each other in real time.

## Choice of programming languages and frameworks

The website was primarily made using Python and more specifically, Django as my backend framework of choice. Django was chosen for several reasons:
- Django has a more structured and opinionated approach to web development compared to other similar frameworks like Flask. This can make it easier to build maintainable and scalable applications, which is important for adding functionality.
- Even though Django is quite monolithic, Django follows a "batteries included" philosophy, which means it comes with a lot of functionality out of the box. 
- Django has a robust set of features and tools for building web applications, including an ORM (Object-Relational Mapper) for interacting with databases, a template engine for building views, and a built-in user authentication system. These features helped me build a full-featured chat application more quickly and easily.

The user and messages were stored in an SQLite database, with the front end of the program being written in HTML and the jQuery framework. The jQuery framework was crucial in delivering asynchronous JavaScript to display messages in the chat rooms.

## Video of the application running:
![](https://user-images.githubusercontent.com/81977350/210283849-9c186111-71ef-41eb-80a4-b528b1ea4e83.gif)

## Instructions to compile and run the application
1. Make sure to have the following installed: [Python](https://www.python.org/downloads/) and [Django](https://www.djangoproject.com/download/)
2. Next, download the source code or clone the repository.
3. First, make sure that the database is set up and fresh with the following command: `python manage.py migrate chatroom zero`
4. Next, to start the server, make sure you are in the root directory, and then in a terminal, run the following command: `python manage.py runserver`
5. The server should start up and you can open the website by typing `http://127.0.0.1:8000/` in any modern browser.

The following commands will be useful:

### Command to run the server:
`python manage.py runserver`

### Command to reset the database:
`python manage.py migrate chatroom zero`

## Potential Improvements and Advancements
- Enable proper account management: account sign-up and sign-out functionality
- Allow all users to be able to see past open chat-rooms
- Change the CSS to display all the messages on one side and display all the online users in the chatroom and their usernames on another side
