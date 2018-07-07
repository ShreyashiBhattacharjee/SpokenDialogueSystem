# Documentation

**Follow the steps to use the website** </br>

* Install python using he following command</br>
` pip install python</br> `

* To run django on ubuntu we will need virtual enviroment.</br>
* To install virtual enviroment run the following command</br>
`aptitude install python-pip virtualenv virtualenvwrapper</br>`
* Now make a folder name django in home directory using the command</br>
`mkdir django2`
* Move to this directory using</br>
`cd django2</br>`
* Now create the virtual enviroment in this folder by running the following command</br>
`virtualenv project</br>`
* So our virtual enviroment named project is created under the django2 directory.</br>
* Now a directory called my project is created insinde django2 directory</br>
* Move to that directory by running the following command</br>
`cd project</br>`
* Then move to bin directory present inside project directory</br>
* Now activate the virtual enviroment using the following command</br>
`source /home/user/django2/project/bin/activate</br>`
* Now we can see the name of our virtual enviroments in brackets in promt</br>
* This indicates the successful activation of our virtual enviroment.
* Now we will install django inside this virtual enviroment</br>
* To install django run the following commands</br>
`pip install django</br>`
* Now go back to django2 directory by using cd .. two times</br>
* Now to create the directory for our site use the following command</br>
`django-admin startproject mysite</br>`
* This will create a directory called mysite inside the bin directory of our virtual  enviroment</br>
* Now move to mysite</br>
* Run the foolowing command on the terminal</br>
`python manage.py runserver 0.0.0.0:8000</br>`
*Then open browser and write in the url section localhost:8000</br>
* If a page appears saying "Congratulations!it worked", that means django is successfully installed now</br>
* Now we will create an app in django <\br>
* For this in run the following command (make sure you are currently in mysite directory)</br>
django-adin startapp personal</br>
* Now this will create a directry called personal inside mysite directory.
* Now go to the settings.py file in mysite directory and find the following lines of code</br>
INSTALLED_APPS = [</br>
    'django.contrib.admin',</br>
    'django.contrib.auth',</br>
    'django.contrib.contenttypes',</br>
    'django.contrib.sessions',</br>
    'django.contrib.messages',</br>
    'django.contrib.staticfiles',</br>
]</br>
* Now add your app in this list as 'personal'</br>
* Also find this line in the settings.py file</br>
ALLOWED_HOSTS = []</br>
* Add your ip address here like this</br>
ALLOWED_HOSTS = ['ip_address', 'localhost', '127.0.0.1']</br>
* Now download all the folder from SpokenDialogueSystem repository and extract it</br>
* Copy all the code from that repository to your new made directoried respectively as it is.</br>
* Now run the server by running the command</br>
`python manage.py runserver 0.0.0.0:8000`
* Go to chrome and write localhost:8000 in the url space.
* The website will run.




