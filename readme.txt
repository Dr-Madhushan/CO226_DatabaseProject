Follow these steps to install the app properly

1. Extract the folder "project" to the local disk

2. Open Command prompt at the opened folder location

3. Perform the following commands in the CMD;
	pip install virtualenvwrapper-win
	mkvirtualenv venv
	workon venv
	pip install django
	pip install mysql-connector

4. run the SQL scripts CreateDB.sql and PopulateDB.sql in order

5. Change the line 6 in the following path to
	"C:\path_to_folder\co226\relax\views.py"

	db = mc.connect(host="localhost", user="root", passwd="your_sql_root_password", database='project')

6. In the Command Prompt run the following code to run the server
	python manage.py runserver
	
	you will see something like this in the cmd;

	(test) C:\path_to_folder\co226>python manage.py runserver
	Watching for file changes with StatReloader
	Performing system checks...

	System check identified no issues (0 silenced).
	December 10, 2020 - 19:58:26
	Django version 3.1.3, using settings 'co226.settings'
	Starting development server at http://127.0.0.1:8000/
	Quit the server with CTRL-BREAK.

7. Open the browser and go to " http://127.0.0.1:8000/ "

8. Use following userIDs to login
	Distributor account: 
		User ID - DEM01
		Password- W*AkUT*yN%

		User ID - DEM02
		Password- RKQA~RXqYs

	Customer Account:
		User ID - CEM01
		Password- QYnSok#1Ts

		User ID - CEM02
		Password- fkfV3f_VbH

9. Or create your own Company account with register link in the home page
	after creating your account you can see your userID in the navbar of home page
