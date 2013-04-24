re_dj
=====
The outer mysite/ directory is just a container for your project. Its name doesn’t matter to Django; you can rename it to anything you like.

manage.py: A command-line utility that lets you interact with this Django project in various ways. You can read all the details about manage.py in django-admin.py and manage.py.

The inner mysite/ directory is the actual Python package for your project. Its name is the Python package name you’ll need to use to import anything inside it (e.g. import mysite.settings).

mysite/__init__.py: An empty file that tells Python that this directory should be considered a Python package. (Read more about packages in the official Python docs if you’re a Python beginner.)

mysite/settings.py: Settings/configuration for this Django project. Django settings will tell you all about how settings work.

mysite/urls.py: The URL declarations for this Django project; a “table of contents” of your Django-powered site. You can read more about URLs in URL dispatcher.

mysite/wsgi.py: An entry-point for WSGI-compatible webservers to serve your project. See How to deploy with WSGI for more details.
