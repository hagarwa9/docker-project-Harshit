# docker-project-Harshit\

Execute the following steps to build the docker image and host the web service through docker:

step1: Clone this repo using git clone https://github.com/hagarwa9/docker-project-Harshit.git

step2: Go into the directory
       You can see web folder that has assets to be served from inside docker container.
       You see Dockerfile and nginx.conf files for the configuration parameters.
       
step3 : Run command:
        docker build -t <docker-project-name> .
        Once the build is complete and the image is created, run docker

step4: docker run -p 8000:90 <docker-project-name>

step5: Go to http://localhost:8000 on the web browser to see the changes.
