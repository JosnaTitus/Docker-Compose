                                        MYSQL cluster using docker-compose
                                        
Problem Statement: 

      We have created the MySQL container from scratch and loaded the desired schema. Now we need to MySQL cluster using the docker-compose. You need to create a 3 node cluster and that cluster must be accessible from the outside world. 

      One should run the command "docker-compose up" and able to connect to MySQL cluster using Mysql client (eg: Mysql Workbench)                                        
                                        
Steps to solve this Assignment: -

  1.Pull the latest code i.e; Open terminal & type following command: -

          git clone https://github.com/JosnaTitus/Docker-Compose.git
      
  2.Go to cloned repo-directory and Build image using command: -

          cd Docker-Compose
      
          sudo docker build . -t abc

  3.Start the container using command: -

          sudo docker run --name abc -p 4040:4040 -d abc
      
  4.Use config command to configure your file: -
     
          sudo docker-compose config
       
  5.Use up command to run the docker compose file: -
        
          sudo docker-compose up

  6.To display all the running process, use the command:-
     
          sudo docker-compose ps
          
  7.Connect to MYSQL using a bash shell using command: -

          sudo docker exec -it abc /bin/bash
       
  8.Use down command to shut down your docker compose file: -

          sudo docker-compose down

