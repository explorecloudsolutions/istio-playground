docker build -f ./dockerfile -t my-gateway . && docker tag my-gateway:latest chthota/my-gateway:latest && docker push chthota/my-gateway:latest

docker build --tag=shows:latest  .
docker tag shows:latest chthota/shows:latest
docker push chthota/shows:latest



docker build --tag=reviews:latest .
docker tag reviews:latest  chthota/reviews:latest 
docker push chthota/reviews:latest