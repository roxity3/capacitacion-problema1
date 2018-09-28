docker build -t etinoco/orbis-training-docker:0.1.0 .
docker push etinoco/orbis-training-docker:0.1.0
docker build -t etinoco/orbis-training-docker:0.2.0 .
docker push etinoco/orbis-training-docker:0.2.0
docker run -d -p "1080:80" etinoco/orbis-training-docker:1.0.0
docker-compose build