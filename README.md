# Store Application
The application needs the following ports <b>8484,8282,8686,61616(ActiveMQ) and 3306(MySQL)</b>.
The docker will download the images from cloud.canister.io.
To start the application just execute the command; 
    
    - docker-compose -f ./integritas-docker-compose.yml up
    
After application start you can check REST controllers by Swagger URL.

http://localhost:8282/swagger-ui.html


Database data and schema sql files will be used by Spring Boot when application starts. 

https://github.com/andreixmartins/i-cart/blob/master/src/main/resources/data.sql

https://github.com/andreixmartins/i-cart/blob/master/src/main/resources/schema.sql


# Docker compose

https://github.com/andreixmartins/i-docker/blob/master/integritas-docker-compose.yml


# Backend

Port: 8484 - https://github.com/andreixmartins/i-pay

Port: 8282 - https://github.com/andreixmartins/i-cart

URL SWAGGER: http://localhost:8282/swagger-ui.html

# Frontend

Port: 8686 - https://github.com/andreixmartins/i-store

URL: http://localhost:8686



