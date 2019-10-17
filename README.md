 ## Django Polls Application [![Build Status](https://travis-ci.com/ChatchapongC/django-polls.svg?branch=master)](https://travis-ci.com/ChatchapongC/django-pollls) 
 Django application to conduct the Web-based polls and record voting score for each polls.  
 Moreover, This app can set the duration for voting.
 ## Requirements

 The application requires
 * Python 3.6 or newer
 * Django 2.1.2 or newer
 * Python add-on modules as in [requirements.txt](requirements.txt)

 ## How to Run
1. Open shell, change the directory where you want to clone this repository to your computer then:  
    - HTTP:
    ```shell script
    git clone https://github.com/ChatchapongC/polls-app-django.git
    ```
    - SSH:
    ```shell script
    git clone git@github.com:ChatchapongC/polls-app-django.git
    ```
2. After you clone the repository change file **_.env.example_** to _**.env**_ then go to the directory and type:
    ```shell script
    python manage.py migrate
    ```
3. Now test your web app is it working by 
     ```shell script
    python manage.py runserver
    ```
    then go to [http://127.0.0.1:8000/polls](http://127.0.0.1:8000/polls)
    
4. If your web app is working well then create your account to access the admin site:
    ```shell script
    python manage.py createsuperuser
    ```
   ```shell script
   >Username: (enter_your_username)
   >Email address: (enter_your_email)
   >Password: ********
   >Password (again): ********
   >Superuser created successfully.
   ```
 5. Go to edit your polls app on [http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin)

