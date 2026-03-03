# Scalable-Inventory-API 

Scalable-Inventory-API is a serverless backend application designed to manage inventory operations through RESTful APIs. The system is built using Java and deployed on AWS using a fully managed, event-driven architecture. It demonstrates how scalable backend services can be implemented without provisioning or maintaining servers.

The application follows a serverless design where client HTTP requests are routed through Amazon API Gateway, processed by a Java function deployed on AWS Lambda, and persisted in Amazon DynamoDB. This architecture ensures automatic scaling, high availability, and cost efficiency.

The backend is developed using Java 17 with Maven for build management. The Lambda function handles API Gateway proxy events and returns structured HTTP responses. The system is stateless and horizontally scalable by design.

                                                       AWS Services Used 
1.Amazon API Gateway - 
     Used to create and manage REST endpoints. It acts as the entry point for client requests and routes them to the Lambda function.

2.AWS Lambda - 
     Executes backend business logic in a serverless environment. It processes incoming API requests and interacts with the database.

3.Amazon DynamoDB - 
     Stores inventory data in a highly scalable and low-latency NoSQL database.

4.AWS IAM - 
     Manages secure permissions between API Gateway, Lambda, and DynamoDB.

5.Amazon CloudWatch - 
     Used for monitoring logs and tracking Lambda execution metrics.

                                                            Key Features

                                                      Serverless architecture

                                                        REST API integration

                                                      Event-driven processing

                                                         Automatic scaling

                                                   No server management required
