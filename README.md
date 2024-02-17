# jenkins-python

Python application is a interpreter language. Hence we didn't need to complile code. We will need to copy paste code to the server
where we want to run our application.

After copy code, we wll need to insatll all dependencies mentioned in the requirement.txt file. The dependencies are required to run
your application.

There are many framework, which provides an inbuilt webserver like FastAPI, Django, Flask etc. We can build application using this framework.
For running application, we can just run main file using python command. It will start server and you can access application on the browser

Ensure to install python and pip

On Ubuntu 22.04 , Python is already installed, you check it by running command
- python3 -V

Install pip using below command
- sudo apt install -y python3-pip

After running jenkins pipeline, you can access the server where you have deloyed the application and then you can app using below command
- python3 app.py

Ensure that security group allow the port 5000 on server and you can access application using url http://<ipaddress>/5000
