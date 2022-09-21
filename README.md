# Java-Practice

## HOW TO RUN THE PROGRAM

This is a simple program that reads XML files and uploads parsed data to a MySQL database

Setting up the Code
-------------------

1. Run the database setup script
	- Open MySQL Workbench
	- Click on 'file' in the top left hand corner
	- Select 'Open SQL Script' and navigate to the SQL file located in this folder
	- Select the option 'Reconnect to database' (the icon directly below the 'Tools' tab)
	- After entering the required password to reconnect, click on the 'Execute' icon (the lightning bolt)
	- Refresh the schemas to find the new rmb database with a clients table

2. In Eclipse, import the project
	- click on 'File'
	- Select 'Import'
	- Expand the 'General' folder
	- Select 'Existing Projects into Workspace' and click next
	- Browse your machine for the 'rmb' subfolder located under this folder
	- When you find the first 'rmb' folder, select it and then click finish
	- You should now see the 'rmb' folder under your package explorer in Eclipse

3. Change the database connection info
	- In the source code, update the database URL, user id and password for your local environment
	- Update the file path for the XML file to your machine

4. Finally, run the program in Eclipse and check the clients table in MySQL to see if it worked

