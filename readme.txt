Mobile ERP

Mobile ERP is our attempt to revolutionize the way current ERP industry works. Mobile phones have become the integral part of everyday life, they are becoming one's Digital identity.

Features

1. Each employee will be able to mark his attendance (“Check-In”) from his smartphone, instead of waiting in long queues at the attendance machine. The “Check-In” option will be available only when the user is connected to company’s local intranet, to avoid fraud attendance. This attendance will be more genuine as one is not likely to hand-over his mobile for a duration, as it is the case with the swipe cards.
2. At the end of day, employee will “Check-Out” via the app. As soon as he Check’s out, he will be shown a feedback form about his day at the office, which can include anything related to office , be it transportation, canteen, management, team etc. This form can be filled at any later point of time, even when not connected to internet. This feedback will be automatically submitted, on his next Check-In.
3. An employee, in a “Checked-In” state, can see status of his colleagues [“Checked-In”, “Checked-Out”, and “Not arrived yet”]. For colleagues who have checked-in, he can “Poke” them, which will send a notification to the respective colleague. This can be used to arrange meets, lunch-breaks etc.
4. The feedback from the employees can be used to generate reports for the HR team, in terms of charts, graphs and trends. Based on this data, management can work towards improving the working environment for the employees and hence the overall productivity of the organization.

How to Use
1)  Install the APK provided.
2)  Create a new employee. Open this url:      http://warm-badlands-1642.herokuapp.com/create/:emp_id/:email/:name
Say, you want to create a new Employee named, “John Doe”, with email “john.doe@company.com” and employee_id as “K1432”. To create this user, open this url:
http://warm-badlands-1642.herokuapp.com/create/K1432/john.doe@company.com/John%20Doe
3)  Open the app.
4)  You should see the registration screen, on connection complete.
5)  Enter john.doe@company.com as email, and click on Register.
6)  On success, you should see a Dialog. Click ‘Login Now’. (We are working on “Verification email    API”, currently it works without any authentication).
7)  Now, your device has been associated with your email, and has become your identity.
8)  You do not need to remember any passwords to Login. Your phone's unique “device_id” is all the authentication we need.
 
TODO-List (Currently working on)
1)  	#Urgent           	- Fix the “Verification Email” thingy.
2)  	#Urgent           	- Create a web interface for creating a new employee.
3)  	#Low 	            	- Create a web interface to view list of Employees and corresponding 	charts and trends for that employee
4)  	#Medium        	- Fix the “Poke” thingy.
 

Future Vision
1.  An auto-attendance system can be used in which, if the employee's mobile is connected to the company's Wi-Fi network, it will mark his presence attendance.
2.  If participating companies agree, we can build a rating or benchmarking system, so that potential employees and job-seekers, can browse and compare different companies.
3.  The “Poke” feature can be extended to build a fully-functional communicator, with Chats, Notes-Sharing, and other capabilities.
