                                        MYSQL cluster using docker-compose
                                        
                                        
Steps to solve this Assignment: -

  1.Pull the latest code i.e; Open terminal & type following command: -

          git clone https://github.com/JosnaTitus/Docker-Compose.git
      
  2.Go to cloned repo-directory and Build image using command: -

          cd DevOps_Assignment2
      
          sudo docker build . -t abc

  3.Start the container using command: -

          sudo docker run --name abc -p 4040:4040 -d abc
      
  4.Use config command to configure your file: -
     
          sudo docker-compose config
       
  5.Use up command to run the docker compose file: -
        
          sudo docker-compose up

  6.Connect to MYSQL using a bash shell using command: -

          sudo docker exec -it abc /bin/bash
       
7. To display all the running process, use the command:-
     
          sudo docker-compose ps
       
  8.Use down command to shut down your docker compose file: -

          sudo docker-compose down

