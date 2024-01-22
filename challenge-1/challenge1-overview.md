## Challenge 1
The goal of this challenge is to have your first full stack application integrated and working correctly locally (not hosted online, relies on your computer running all parts of the application). If you are using a service such as Amazon RDS or DynamoDB, you may not need to have it running locally. As long as your client can communicate with the server and the server can interact with the data layer, where they are hosted is irrelevant. The next challenge will be to host all parts of your application.

## Prerequisites
- Select a tech stack for your application
- Have a tech stack installed and a new project set up for each of the pieces of your application. This may be one code base, it may be multiple depending on the stack selected. Most frameworks will create a generic project

## Challenge Minimum Requirements
- Create a dataset in for the data layer. It can be as complex or simple as needed. It could be one table or multiple.
- Set up a server to be able to pull a set of data from your data layer. This can be one or more data feeds.
- Set up a client to interact with the server and display the data from your data layer. The client can be as simple or complex as needed.

## Tips
- It is advisible to start as simple as possible and iterate over your design to make it more complete. Starting small and making sure everything iteracts correctly will prevent a lot of headache as you add more features
- Store the source code for your application in git (or any other source code management system) so that you have version control over your source code. Commit and push changes every time you have working code.
- If creating APIs in the back end layer, consider creating an [Open API Specification](https://swagger.io/specification/)

## Ideas for the application
- Create a dataset of customers, products and purchases. Initially have the server return a list of customers, number or orders and total spent which is displayed by the client. Iterate over this design to create separate views or pages and also allow the client to add, modify, and delete customers, products and purchases. 
