How It Works
File Upload: When a new file is uploaded to the lbmfuncbucket, an S3 event notification is generated.
Lambda Trigger: This event triggers the associated AWS Lambda function.
Processing Logic: The Lambda function processes the file according to the defined business logic (e.g., resizing images or parsing text).
Output Handling: Results from the processing can be logged, stored back in S3, or sent to another service, such as DynamoDB.
