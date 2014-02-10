Django application using a web service as model
===============================================

Simple hello world using Django

First install vagrant http://www.vagrantup.com/downloads.html

Go in the directory you cloned this repository and run the following commands

    $ vagrant up
    $ vagrant ssh
    $ cd /vagrant

You are back in the same directory but seen from the virtual machine

In order to get the Django application running go into hello_world directory and run

    $ python manage.py runserver 0.0.0.0:8000

Then browse to http://127.0.0.1:9000   (the host port 9000 is forwarded to the port 8000 in the VM)
