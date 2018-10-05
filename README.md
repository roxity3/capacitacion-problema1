docker build -t etinoco/orbis-training-docker:0.1.0 .
docker push etinoco/orbis-training-docker:0.1.0
docker build -t etinoco/orbis-training-docker:0.2.0 .
docker push etinoco/orbis-training-docker:0.2.0
docker run -d -p "1080:80" etinoco/orbis-training-docker:1.0.0
docker-compose build
docker run -it -v $(pwd):/app -w /app etinoco/orbis-training-docker:0.2.0 npm install
docker run -it -p 3030:3030 -p 35729:35729  -v $(pwd):/app -w /app etinoco/orbis-training-docker:0.2.0 npm start