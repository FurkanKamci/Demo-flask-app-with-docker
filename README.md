
docker build -t app .

docker images ls

docker run -d -p 5000:5000 app
