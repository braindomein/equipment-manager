========================
	SETTING UP
========================

Before running the application open the properties file located inside the "conf" folder. Make sure that the port used is open in your machine, if not just change the port in this file to a different one.

Next check and make sure the "jdbcUrl" points to a database that actually exists in the machine. If you want to use a different name you can change the name here as well. From there confirm the user login details to connect to that database on the "jdbcUser" and "jdbcPassword".

DONE !!!

========================
RUNNING THE APPLICATION
========================

To run the application just click on the "RunApplication.bat" file and on your browser access the application dashboard on url "http://localhost:8075/" or in the case where you changed the port number in the properties file use that one instead  i.e. "http://localhost:serverPort/".

Notes:

* When unzipping the project zip file, make sure that all zip file contents are in the same location/folder.

		"I’m not a great programmer; I’m just a good programmer with great habits."
		― Kent Beck
