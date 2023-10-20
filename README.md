# Customer Relationship Management (CRM) Application
1. This app is created with **Python**, **Django**, and **Bootstrap 5**, with the use of **MySQL** to store the data.
2. Bootstrap *Components* such as Alerts, Navbar, *Tables* and *Cards*,  Django's *Forms* are utlised.
3. The functions of the app allow user to :
- perform **authentication and authorisation** such as sign up , login, and logout
- perform **CRUD** oprations such as add a new record, view records, update records, and delete records.   


## To run the local server
1. Open gitbash command prompt.
1. Run `cd [your_directory]/crm-django`
2. Create a virtual environment bu running `python -m venv [virtualEnvionmentName]`
3. Download the dependencies by runing `pip install django mysql mysql-connector-python`
4. Activate the virtual eneviroment by running `source [virtualEnvionmentName]/Scripts/activate`
5. Run `cd jiaCrm`
6. Run `python manage.py runserver`
7. Open the website at http://localhost:8000/
8. Quit the local server by clicking CTRL + C at gitbash command prompt.
9. Deactivate the virtual eneviroment by running `deactivate [virtualEnvionmentName]`