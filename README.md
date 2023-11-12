# serverless-API
Mini-project: Built a Serverless API with AWS Lambda, API Gateway, and DynamoDB

<img width="500" alt="image" src="https://github.com/ElizabethViolin/serverless-API/assets/130325688/e6a41792-c650-4635-be49-a51b8f6a1b22">

## How it works:
1. An HTTP request is made to your API Gateway endpoint.
2. API Gateway routes the request to the appropriate Lambda function based on the HTTP method and resource path.
3. The Lambda function performs the required CRUD operation by interacting with the DynamoDB table.
4. If it's a read operation, the Lambda function retrieves data from DynamoDB and returns it as an HTTP response. If it's a create, update, or delete operation, the Lambda function interacts with DynamoDB to modify the data, and a success or error response is returned to the client.

## Conclusion:
This setup allows you to build scalable and cost-effective serverless APIs while offloading most of the infrastructure management to AWS.
