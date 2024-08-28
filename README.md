This is a simple web application built using Flask and dockerized to run in containers. It demonstrates how to build, run and manage the application using Docker. It also includes Docker Compose for running multi-container applications and uses Docker Hub to store image.

Step 1: Clone the repository
https://github.com/AvinashKumar-Nagarro/flask-app.git

Step 2: Change folder
cd flask-app

Using Dockerfile
Step 3: Build Docker image
docker build -t flask-app .

Step 4: Run Docker container
docker run -d -p 8080:80 flask-app

Step 5: Access the app
Open any browser and hit http://localhost:5000

Using Docker Compose
Step 3: Run Docker container
docker-compose up --build

Step 4: Access the app
Open any browser and hit http://localhost:5000
