# Report


## Part 1. Ready-made docker

- making shure that docker is installed and docker engine is running
- getting nginx:
    
    ![text](screenshots/part1/1.PNG)

- check for the docker image with 'docker images':

    ![text](screenshots/part1/2.PNG)

- run docker image with 'docker run -d [image_id|repository]' and check that the image is running with 'docker ps':

    ![text](screenshots/part1/3.PNG)

- view container information with 'docker inspect [container_id|container_name]':

    ![text](screenshots/part1/4.PNG)

- - size:
 
    ![text](screenshots/part1/5size.PNG)

- - ip:

    ![text](screenshots/part1/6ip.PNG)

- - list of mapped ports:

    ![text](screenshots/part1/7ports.PNG)


- stop docker image with 'docker stop [container_id|container_name]' and check that the image has stopped with 'docker ps'
    
    ![text](screenshots/part1/8stopps.PNG)


- run docker with mapped ports 80 and 443 on the local machine with 'run' command:

    ![text](screenshots/part1/9mappedPortsRun.PNG)

- check that the nginx start page is available in the browser at localhost:80:

    ![text](screenshots/part1/10startPage.PNG)