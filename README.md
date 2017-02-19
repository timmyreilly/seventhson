This is miminum code required for an Azure Flask project deployment. 

Check out my [blog post](http://timmyreilly.azurewebsites.net/starter-site-for-flask-on-azure-web-apps/) if you have any other questions. 

Set an application setting:
key = `SERVER_PORT`  value = `80` 


Docker Commands: 
`$ sudo docker build -t flask-app:latest .`

Docker Run: 
`$ sudo docker run -p 80:80 flask-app` 

This helped: 
http://containertutorials.com/docker-compose/flask-simple-app.html 
And so did this: 
https://docs.docker.com/engine/getstarted/step_six/ 