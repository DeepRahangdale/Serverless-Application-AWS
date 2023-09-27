# LevelUp! Lab for Serverless

## Lab Overview And High Level Design

Let's start with the High Level Design.
![High Level Design](./images/high-level-design.jpg)

An Amazon API Gateway is a collection of resources and methods. For this tutorial, We will create a Serverless Full Stack Application( Serverless Full Stack Application is a modern and scalable web application) where using React.js and Material UI for the frontend, Node.js on AWS Lambda for the backend, and DynamoDB for data storage. The application's main feature is to display data from a DynamoDB table in a user-friendly web interface and provide a "Remove" button to delete selected records. Users can interact with the data and remove items as needed, creating a simple but practical web application.

![High Level Design](./images/Serverless_Web_App.png)

* Amazon API Gateway:

Amazon API Gateway is a crucial component of this application. It acts as a gateway to manage the collection of resources (endpoints) and methods (HTTP verbs) that the frontend and backend will use to communicate with each other securely.

* Serverless Full Stack Application:

This application follows a serverless architecture, which means it leverages cloud services to handle various aspects like scalability, security, and resource management without the need for traditional server infrastructure. It is designed to be modern and scalable, ensuring it can accommodate growth and changing demands.

* Frontend Technology:

The frontend of the application is built using React.js, a popular JavaScript library for creating user interfaces. Material UI is used to enhance the design and user experience, providing a set of pre-designed UI components.

* Backend Technology:

Node.js is employed for the backend logic of the application. AWS Lambda functions, running Node.js code, handle various backend tasks such as processing API requests, interacting with the database, and executing business logic.

* Data Storage:

DynamoDB, an AWS NoSQL database service, is utilized as the data storage solution. It's a scalable and highly available database that allows efficient data retrieval and management.

* Main Application Feature:

The primary functionality of this application is to display data stored in a DynamoDB table in a user-friendly web interface. Users can interact with the displayed data and, notably, remove items from the table using a "Remove" button.

* User Interaction:

Users can engage with the application by viewing, selecting, and removing records from the DynamoDB table. The "Remove" button provides an intuitive way to delete specific records as needed.

* Practicality:

The application focuses on solving a practical problem: managing and interacting with data. By allowing users to remove records, it addresses a common use case, making it a valuable and straightforward web application.

## Setup

