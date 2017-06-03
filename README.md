# djangoBlog
a django based fully featured blog


## SETTING UP THE BLOG IN THE DJANGO DEVELOPMENT ENVIRONMENT
#### 1.0 ENSURE YOU HAVE THE FOLLOWING INSTALLED
* [pip](https://pip.pypa.io/en/stable/reference/pip_install/) 
install pip by running the following command in your terminal: 
```
[sudo] apt-get update
apt-get -y install python-pip
```
* [virtualenv](https://virtualenv.pypa.io/en/stable/installation/)
install the virtual environment by running the following commands:
```
$ [sudo] pip install virtualenv
```
#### setting up the virtual environment.
* create a virtual environment by running the following command in your terminal:
`virutalenv name`
* change directory into the created virtual environment by typing `cd name` into the terminal.
* activate the virtual environment by running the command `source bin/activate`
#### setting up the dependencies of the project
* install django by running the command `pip install django==1.8.6` in your terminal.
* install pytz into the virtual environment by running the command `pip install pytz` in your terminal.
### cloning the project
* given that your directory is in the `name` folder. you can clone your project into this folder by running the following command in your terminal ` git clone` [https://github.com/iankang/djangoBlog.git](https://github.com/iankang/djangoBlog.git) 
* change the name of the project to avoid confusion by running the following command `mv djangoBlog src`
### running the blog
* change the directory into the src folder by running the following command `cd src`
* run the project by running the following command :
```
python manage.py runserver 
```
if all is well, it should output an adress where you can view your blog.
in most cases it is http://127.0.0.1:8000/

