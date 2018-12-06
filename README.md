docker build -t foo/node  -> setting the image

docker run -d -p 3000:3000 --name node-app foo/node -> running the container

docker run -t 8000:80 --link node-app:app --name nginx-proxy fo/nginx --> linking nginx proxy with node app