# Microservices-new
A spring boot microservices project that combines a product service, order service, inventory service and notification service

# Product Service
* DB = mongodb
* Service configured to run on random port
# Order Service
* DB = mysql
* Service configured to run on port 8081
# Inventory Service
* DB = mysql
* Service configured to run on random port
# Eureka Discovery Service
* Configured to run on port 8761
# API Gateway Service
* Configured to run on port 8080
# KeyCloak Security Service
* Configured to run on port 8181
* Run using command `start-dev --http-port=8181`