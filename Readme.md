* ./mvnw package
docker build -t demo/demo .
docker run -p 8080:8080 demo/demo