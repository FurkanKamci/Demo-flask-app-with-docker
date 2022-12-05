
docker build -t my-flask-app .

docker images ls

docker run -d -p 5000:5000 my-flask-app
