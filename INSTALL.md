## Dependencies

OpenMolDB should run on any OS that can run Django 1.4.x.
It was tested on current version of Arch Linux and Arch Linux ARM (yes it runs on Raspberry Pi)

* Python 2.7.x or 2.6.x
* Django 1.4.x
* OpenBabel 2.3.x with Python bindings
* Any database supported by Django
* Any web server that can run Django

## Installation

git clone https://github.com/samoturk/openmolDB.github

Then deploy it as you would any other Django project.

Set servername variable in openmoldb/views.py to the name of your server.
Have a look at settings.py and set your database engine, time zone, etc.