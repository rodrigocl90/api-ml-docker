## Instalación y ejecución

```bash
git clone https://github.com/rodrigocl/api-ml-docker.git && \
cd docker-ml-api && \
docker build -t ml-flask-api:1.0 . && \
docker run -d -p 5000:5000 ml-flask-api:1.0

