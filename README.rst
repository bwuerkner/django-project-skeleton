django-project-skeleton
=======================

**django-project-skeleton** is my skeleton for Django projects. It provides a
directory structure for Django projects during development and deployment.


Meta
----

Author:
    Mischback

Contributors:
    `agirardeaudale <https://github.com/agirardeuadale>`_,
    `jmrbcu <https://github.com/jmrbcu>`_

Status:
    maintained, in development

Version:
    1.3

Django Version:
    1.9, 1.10, 1.11, 2.0, 2.1, 2.2b1

Python Version:
    2.7 (official support ending with 2019), 
    3.4 (official support ending March 2019), 
    3.5, 3.6, 3.7



Usage
-----

To use this repository just use the ``template`` option of `django-admin
<https://docs.djangoproject.com/en/1.11/ref/django-admin/#startproject>`_::

    $ django-admin startproject --template=https://github.com/Mischback/django-project-skeleton/archive/development.zip [projectname]

If you wish to automagically fill the ``apache2_vhost.sample`` the command is::

    $ django-admin startproject --template=https://github.com/Mischback/django-project-skeleton/archive/development.zip --name apache2_vhost.sample [projectname]


Documentation
-------------

You can see the documentation over at **Read the Docs**: `django-project-skeleton
<http://django-project-skeleton.readthedocs.org/en/latest/>`_
