# My blog

My blog is a Blog application with Django that allows users to create, edit, and delete posts. The homepage list all blog posts, and there is a dedicated detail page for each individual post.

## Installation

1. Merge project

2. Use the package manager [pip](https://pip.pypa.io/en/stable/) to install custom packages

```bash
cd my_blog
pip install -r requirements.txt
py manage.py migrate 
py manage.py runserver
```
Then go to browser and search for /blog

## Description

My blog is a django blog that allows you to create, manage and filter your own posts.
It also has a profile manager inherited from django's default authentication system.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.