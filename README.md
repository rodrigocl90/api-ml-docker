Para instalar y correr:

git clone https://github.com/rodrigocl90/api-ml-docker.git
cd docker-ml-api
docker build -t ml-flask-api:1.0 .
docker run -d -p 5000:5000 ml-flask-api:1.0
