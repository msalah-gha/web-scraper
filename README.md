Task:
system consists of two components:

1 web scraper
1 web server
All the components should run with docker.
You need to do the following:


Write a simple app that retrieves a new random "Fortune of the Day" message from the endpoint below every 10s
http://dojodevopschallenge.s3-website-eu-west-1.amazonaws.com/fortune_of_the_day.json


Expose the random message as a HTML page in the web server container every 10 seconds

-----------------

Simple Web scraper job, running php script inside jenkins container every minute to get random result 
and pushing the result to nginx container

docker compose used.

To run nginx and display result use 0.0.0.0:8989/task.html
