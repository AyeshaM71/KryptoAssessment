# KryptoAssessment
Created a price alert application that triggers an email when the user’s target price is achieved.
Login page is created where user enters his/her email and password.
The email is considered to be the primary key
Create page is made available to set alerts , where user enters the limit price of cryptocurrency and the name(id) of cryptocurrency.
The current value of the cryptocurrencies is been fetched using requests library in python and is compared with the limit price set by the user and a mail is sent accordingly when the current price has reached limit price.

1. Run app.py
2. Run main.py
3. Create module will create an alert and send email.
4. delete, status modules are incomplete.
5. We have used dictionaries to store the data (Haven't used any DBMS).
6. We have created a seperate server file(main.py) which has an infinite loop that verifies all the created limit amount with the curent price of respective crytocurrency.

Tech used:
1) Python
2) Flask
3) SMTPlib
4) Requests lib
5) MIMEText
6) HTML
7) CSS
8) REST api
