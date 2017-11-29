
To start the application just execute the command docker-compose -f ./integritas-docker-compose.yml up
The application needs of the follow ports 8484,8282,8686,61616(ActiveMQ) and 3306(MySQL).

The docker images will be download from cloud.canister.io

After to execute Docker compose file you can check REST controllers by Swagger URL http://localhost:8282/swagger-ui.html

# Docker compose
https://github.com/andreixmartins/i-docker/blob/master/integritas-docker-compose.yml

Command line to execute docker-compose 
    - docker-compose -f ./integritas-docker-compose.yml up



# Backend

- Port: 8484
https://github.com/andreixmartins/i-pay

- Port: 8282
https://github.com/andreixmartins/i-cart

- URL SWAGGER: http://localhost:8282/swagger-ui.html

# Frontend

- Port: 8686
https://github.com/andreixmartins/i-store

- URL: http://localhost:8686



