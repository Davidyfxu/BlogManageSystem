# Blog Manage System
> This project should also be named as 'Multi-users Content Publishing System' and it achieves the functions of making accounts, writing the articles and uploading files.

## Table of contents
* [General info](#general-info)
* [Screenshots](#screenshots)
* [Technologies](#technologies)
* [Setup](#setup)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)



## General info

Blog Manage System is a web project that achieve online writing articles, publishing articles and upload various files, such as images, photos, videos and so on, and exchanging ideas or comments between users. This django project implements most functions of blog websites and even it could add the Pub/Sub functions like Youtube or twitter. I think it's a good way for new nerd to broaden the opinion about backend jobs and improve the coding ability.

This project is aimed for the practice of the backend framework *Django* and learning basic frontend knowledge  of *HTML*. This project is programmed basing on Django and HTML, and some functions need running with Redis. I draw the diagram below to show my project from the top level.

After implementing this project, I hope you can get some brand-new points about MVC model which is the nearly hottest structure in modern web framework.



## Screenshots

This section is about 3 important pictures:

1. Diagram about the whole project framework
2. Homepage about Blog System
3. Subsystem navigation of other 4 parts in this project

![Framework Diagram](https://github.com/David-xyf/BlogManageSystem/blob/main/imgs/Multi-users%20Content%20Publishing%20System.png)

![BlogHomepage](https://github.com/David-xyf/BlogManageSystem/blob/main/imgs/BlogHomepage.png)

![NavigationPage](https://github.com/David-xyf/BlogManageSystem/blob/main/imgs/NavigationPage.png)



## Technologies

* Python - version 3.6
* Django - version 2.2
* Redis - version 3.5.3
* awesome-slugify - version 1.6.5
* Markdown - version 2.6.9
* Pillow - version 4.2.1
* sorl-thumbnail - version 12.7.0
* django-braces - version 1.13.0
* ......



## Setup

The following commands are the easiest way to run this web project.

### requirements.txt

```bash
pip install -r requirements.txt
```

**Tips: I strongly suggest you to create a new venv to install these python libs.**

### Running the django project

```python
python manage.py runserver
```

### Running the Redis（Windows）

```
redis-server.exe redis.windows.conf
```

For Mac/Linux, you can search the way of how to use redis from website.(it's easy to complete by yourself)

**In fact, if you don't care to see how many people saw this article, you did not need to open or use Redis.**



## Code Examples

I just upload all my code in my github repo.



## Features
List of features ready and TODOs for future development
* Multi-users register
* Accounts management
* Content share
* File upload
* ...

To-do list:
* Push this django project into the cloud server, such as Heroku, AWS and etc. 
* Transfer data from sqlite to other databases, like Mysql.

If you can achieve it or extend to implement other functions, please email to me and let me know your solutions.



## Status

Project is finished basically.



## Notice

1. **Sorry for my poor English**
   Initially I programmed this project in Chinese and then translated some key words because I hope more people from different cultures can give me more suggestions. However, in some sub-webpages, they may still be shown in Chinese but I think it will not influence you to understand this demo and you can use google to translate these Chinese words.  If there're any mistake in English expressions in this project, please let me know and modify it.
2. **Admin account**
   I made an original account to provide people with login and test.
   Username: admin    Password: xyf20201228

## Contact

Created by [@david-xyf](https:/david-xyf.github.io/) - feel free to contact me!"
