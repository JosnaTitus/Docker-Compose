                                        Mysql cluster using docker-compose
                                        
                                        
Steps to solve this Assignment: -

  1.Pull the latest code i.e; Open terminal & type following command: -

      git clone https://github.com/JosnaTitus/Docker-Compose.git
      
  2.Go to cloned repo-directory and Build image using command: -

      cd DevOps_Assignment2
      
      sudo docker build . -t assignment_2

  3.Start the container using command: -

      sudo docker run --name pucsd_assignment_2 -p 4040:4040 -d assignment_2
      
  4.Use config command to configure your file: -
     
      sudo docker-compose config
      
  5.Use up command to run the docker compose file: -
        
       sudo docker-compose up

  6.Connect to MYSQL using a bash shell using command: -

       sudo docker exec -it pucsd_assignment_2 /bin/bash
       
  7.Use down command to shut down your docker compose file: -

       sudo docker-compose down

