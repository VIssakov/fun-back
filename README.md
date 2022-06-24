
    docker build -t fun-back:dev ./
    docker run -d --name fun-back -p 8000:8000 fun-back:dev