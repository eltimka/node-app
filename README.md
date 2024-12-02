# Read first
* This project is one of the subprojects of "Docker and K8S".
* In this project, we consider the simplest client that displays a single page and stores state in memory.

# Starting the project
* To start locally (without using Docker), you will need to have node installed
<br/>`npm install`
<br/>`npm start`
<br/>Open link
<br/>`http://localhost:4200/`
* To start using Docker,you need to:
* Install Docker
* Create an image 
<br/>`docker build . --tag=nodeapp:latest`
* Запустить контейнер
<br/>`docker run -p 4200:4200 nodeapp:latest`



