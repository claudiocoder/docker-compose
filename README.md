# Build docker file

docker build .
docker build -t cmoreno/visits:latest .


# Dcoker compose file
docker-compose up

docker-compone up --build


# LAunch in background
docker-compose up -d

# Stop docker compose
docker-compose down 

