                                        Mysql cluster using docker-compose
                                        
                                        
Steps to solve this Assignment: -

  1.Pull the latest code i.e; Open terminal & type following command: -

      git clone https://github.com/JosnaTitus/Docker-Compose.git
      
    Go to cloned repo-directory and Build image using command: -

      cd DevOps_Assignment2
      
      sudo docker build . -t assignment_2

    Start the container using command: -

      sudo docker run --name pucsd_assignment_2 -p 4040:4040 -d assignment_2

    Connect to MYSQL using a bash shell using command: -

      sudo docker exec -it pucsd_assignment_2 /bin/bash

