# Create image and container

docker build -t st-web .

docker run -p 3000:3000 st-web

# or docker-compose

docker network create dragonbound

docker compose up

## to down docker-compose

docker compose down
