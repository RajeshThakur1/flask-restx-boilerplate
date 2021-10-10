# Flask RestX Api Boilerplate
Version 1.0  
  
&nbsp;  

This is a boilerplate for any flask_restx application.  


### What's included?  
    - app
    - requirements.txt
    - manage.py

### What's not included?
    - Migrations
    - Database
    - Development environment (Read README)


### **_Prerequisites_**
>**Git**  

    - sudo apt install git  

>**Python3**  

    - sudo apt install python3  

>**Virtualenv**  

    - sudo apt install python3-virtualenv  

>**Pip**  

    - sudo apt install python3-pip  

>**python-as-python3**  

    - sudo apt install python-as-python3

### _How to get started_?  
- Clone the repository using **git clone https://github.com/Cybertronian123/Api_Boilerplate.git**
- Make a new folder using  **mkdir \<foldername\>**
- Cd into the folder that you cloned **cd Api_Boilerplate/**
- Run the setup file **python3 setup.py**
- At the __Name of your Project:__ input box, type the **\<foldername\>** that you created
- Cd into the folder **cd \<foldername\>**
- Create the virtual environment: **virtualenv env**
- Activate the environment: **source env/bin/activate**
- Install the requirements: **pip install -r requirements.txt**
- Initialise the database: **python manage.py db init**
- Migrate the database: **python manage.py db migrate --message 'inital migration'**
- Apply the migrations: **python manage.py db upgrade**
- Run: **python manage.py run**
