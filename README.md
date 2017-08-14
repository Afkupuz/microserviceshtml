# microserviceshtml
for microservices presentation

Package docker with:
  docker build -t microserv .

Run container with:
  docker run -i -t -p 5050:5050 microserv /bin/bash
 
Launch app with:
  python app.py
  
Change the api call in /static/js/main.js file
