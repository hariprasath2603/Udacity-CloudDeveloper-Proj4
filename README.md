# Udacity ToDos Serverless project
* Best practices are implemented
* Auth0 - Asymmetric RS256
* ToDo - Creation, Deletion, Upload, Modify are added


## Project Components
- Restful API (Lambda Functions, API Gateway and DynamoDb)
- Client (React)

## How to run the application
### Backend
To deploy an application run the following commands:

```bash
cd backend
npm install
sls deploy -v
````
### Frontend
```bash
cd client
npm install
npm run start
```

## Deplyment details
API Endpoint
```
https://wu55ljs6g6.execute-api.us-east-1.amazonaws.com/dev/todos
```
Postman Collection
```
Udacity C4 Project.postman_collection.json
```
