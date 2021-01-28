Requirement Of Location sharing site
1. Ruby 2.7.2 Rails 6.1
2. Postgres DB


Download the application in your local computer. 
Create database: location_app
Then run: rake db:migrate or import DB using export DB file
now start the project & go to root location
sign up using 
	1. First name
	2. Last name
	3. Username [unique,required field]
	4. email [unique,required field]
	5. password [required field, 6 characters minimum]
	6. confirm password [required field]
	
Log In using 
	1. email 
	2. password
	
After you logged in it will redirect "Share Location tab" & show the openLayer google map
when you click anywhere on the map a Bootstrap Modal will open & show 
	1. Latitude 
	2. Longitude
	3. Save & sharing criteria
		1. Save for Private [ only save location for user himself]
		2. Save for Individual [when you click on this it opens user list pop up. Select users manually.]
		3. Save for Public [shares location to all users]
		
When you click "Users" menu tab it shows all user list using the application
It shows user details with share Locatin option
when you click "Show Public Share Location" of a conciquent user it redirects another page
it will show all public location of that user
Example: username= bapan
url will be: http://127.0.0.1:3000/bapan   
