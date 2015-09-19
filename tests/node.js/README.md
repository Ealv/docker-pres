
Create an image from the Dockerfile
docker build -t node-test .


docker  run  -it  node-test 

docker  run  -it -v $PWD:/var/app node-test 
