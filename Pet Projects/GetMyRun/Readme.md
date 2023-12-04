# GetMyRun
GetMyRun is a small Python program written to scrape Google Sheets data which, in this case, contains training information, and return it to the user.

Ideally, this tool will remove the step of opening a browse or app. 

-----
Project Structure
main.py will call the application's services

Other .py files will be named consistent with the services they provide.
- today's run gets the run where today's date matches the row in the excel file

Services the program will need:
1. today's run
2. this week's mileage
3. functionality to send the daily run info somewhere
	1. this is the notification, email, etc. to communicate to the end user