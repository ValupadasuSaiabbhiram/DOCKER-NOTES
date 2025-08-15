# Creating a Docker Image

Create a new folder and name it as hello-docker

In hello-docker folder create a file hello.js and type

> console.log('Hello world!')

create a new Dockerfile

> FROM node:20-alpine      #latest nodejs runtime version
>
> \
> WORKDIR /app                  #set working directory as app this is where our commands are run
>
> \
> COPY . .                                #copies everything from our current directory to the docker image
>
> \
> CMD node hello.js             #specify command to run the app

Now, Run the command

> docker build -t  hello-world .

where t stands for tag (optional).

next the path to docker file



To check the image is created successfully or not type:

> docker images
