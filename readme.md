docker exec -it 138955c6fd2d bash

docker exec -it 138955c6fd2d python train_model.py

curl --header "Content-Type: application/json" --request POST --data '{"flower":"1,3,2,5"}' http://127.0.0.1:5000/iris_post
