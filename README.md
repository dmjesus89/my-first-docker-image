# My-first-docker-image
Creating my first docker image based ubuntu with flash


To build the image

docker build . -f Dockerfile.dockerfile -t diego/my-custom app 

After build we should push at docker registry 

docker push diego/my-custom-app
