
# Lambda S3 Event Processor

## Description

The **Lambda S3 Event Processor** is a serverless application that utilizes AWS Lambda to process events triggered by file uploads to an S3 bucket. This project showcases the integration of AWS Lambda with S3, allowing for automated processing of various file types upon their creation in the bucket.

## Features

- **Automatic Triggers:** The Lambda function is automatically invoked when new files are uploaded to the specified S3 bucket.
- **File Processing:** The function can handle various file types (e.g., text, images) and perform actions such as resizing images, extracting metadata, or processing text files.
- **Infrastructure as Code:** The application is deployed using AWS CloudFormation, ensuring reproducibility and easy management of AWS resources.
