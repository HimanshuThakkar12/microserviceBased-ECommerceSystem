# Microservice-based-E-commerce-system

A scalable and fault tolerant microservices based E-commerce system with Eureka Discovery Server. The architecture has three micro services as shown in high level architecture diagram below. The model also comprises of discovery server and API gateway. Discovery server maintains local copy at each service to manage URL of each services.


![Microservice Diagram drawio](https://github.com/Divarshana-Saxena/Microservice-based-E-commerce-system/assets/140905073/d12bede0-e4b1-4855-b39d-1c9e2af30156)






Following image shows that we are successfully storing product information with HTTP status as 201 Created. 




![Screenshot (12)](https://github.com/Divarshana-Saxena/Microservice-based-E-commerce-system/assets/140905073/8e320a94-1621-4535-8767-34c2a7bd7ddf)





Following image shows that we can successfully retreive product information from our database with HTTP status as 200 OK. 




![Screenshot (16)](https://github.com/Divarshana-Saxena/Microservice-based-E-commerce-system/assets/140905073/a5a905f6-b576-4988-b9e1-03f2c733f9aa)






Image snippet of our databases and tables of inventory and order service.




![Screenshot (18) (1)](https://github.com/Divarshana-Saxena/Microservice-based-E-commerce-system/assets/140905073/a183edcc-0332-4ff6-87b3-014e61e527fc)







Following image shows that we can successfully make order after checking in with inventory service if product is in stock or not information with HTTP status as 201 Created. 




![Screenshot (20)](https://github.com/Divarshana-Saxena/Microservice-based-E-commerce-system/assets/140905073/0b56223d-e3d9-423f-9d48-a5c700ccf87a)







The application supports service discovery, API gateway, Circuit Breaker and Load Balancing.
