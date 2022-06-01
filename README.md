This CC Hackathon project was developed as a purpose to imitiate the working of a RabbitMQ Server which acts as a broker between client and database.
A ride can be booked by the producer which is allocated to the freely available consumers and the ride details are synchronously saved to database.
Nodes involved : Producer, Consumer and Database.
The request is manually created using POSTMAN application through get/post methods which stacks in the queue until it is received by one of the consumers.

Technologies used : 
1) Database : MongoDB
2) Language : Python
3) Environment : Docker (via yml)

