# Distributed-Task-Management-System-in-RabbitMQ
This project involves creating a scalable, distributed task management system using NestJS for the backend and RabbitMQ for message queuing. The system would allow users to create, assign, and track tasks across multiple teams or departments within an organisation.

### Project Goals
- **Scalability**: Design a microservices architecture that allows independent scaling of components based on load.
- **Real-Time Updates**: Implement real-time task status updates using WebSocket.
- **Task Prioritization and Scheduling**: Allow users to prioritize and schedule tasks effectively.
- **Distributed Task Processing**: Facilitate asynchronous task processing using RabbitMQ.
- **Reporting and Analytics**: Provide insights into task management through analytics.

## Technologies Used
- **Backend Framework**: NestJS
- **Database**: MongoDB
- **Message Broker**: RabbitMQ
- **Real-Time Communication**: WebSocket

## What Has Been Done So Far
1. **Project Initialization**:
   - Created a new NestJS application using the Nest CLI.
   - Installed necessary dependencies, including Mongoose for MongoDB and RabbitMQ packages.

2. **API Gateway**:
   - Implemented an API Gateway module that serves as a single entry point for all client requests.
   - Integrated modules for Task, User, Notification, and Analytics services.

3. **Task Service**:
   - Developed a Task module to handle task creation, updates, retrieval, and deletion.
   - Implemented the Task schema to define the data structure for tasks.
   - Created a Task service for business logic and a Task controller for API endpoints.

## Getting Started

To run the application locally:

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd task-management-system

2. **Install dependencies**:
   ```bash
   npm install
3. **Set up MongoDB**:
- Ensure MongoDB is running locally or configure the connection to a cloud instance.
4. **Run the application**:
   ```bash
   npm run start
5. **Test the API**:
- Use Postman or any API testing tool to access the endpoints (e.g., POST /tasks, GET /tasks).

## Next Steps
- Implement the User Service for user management and authentication.
- Create the Notification Service for real-time updates.
- Develop the Analytics Service for reporting and insights.
- Integrate RabbitMQ for message queuing and distributed task processing.
- Implement testing and CI/CD pipelines.