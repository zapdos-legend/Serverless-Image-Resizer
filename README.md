# Serverless-Image-Resizer
Built a serverless image resizer using AWS Lambda and Amazon S3 to automatically resize uploaded images.

## 🎯 Purpose

The purpose of this project is to automatically resize images whenever they are uploaded to Amazon S3 using a serverless architecture.

This project demonstrates:

* Automatic image processing using AWS Lambda
* Event-driven serverless automation
* Image upload handling through Amazon S3
* Scalable and cost-efficient serverless workflows
* Real-time image resizing without managing servers

Whenever a new image is uploaded to the S3 bucket, AWS Lambda automatically triggers and resizes the image.

## 🧰 AWS Services Used

* **AWS Lambda** – Used for automatically processing and resizing uploaded images.
* **Amazon S3** – Used for storing original and resized image files.

## 📸 Project Screenshots

### 1. S3 Bucket
This shows the created S3 bucket for storing data.
![S3](S3%20Bucket.png)

### 2. S3 Bucket Upload
This shows files uploaded into the S3 bucket.
![S3 Upload](S3%20Bucket%20Uplod.png)

### 3. Lambda Function
This shows the AWS Lambda function configuration.
![Lambda](Lambda%20AWS.png)

### 4. Lambda Function Upload
This shows Lambda function deployment/upload.
![Lambda Upload](Lambda%20Function%20Uplod.png)

### 5. Lambda Event Code
This shows the event trigger code for automation.
![Event Code](Lambda%20Event%20Code.png)

### 6. CloudWatch Logs
This shows execution logs from AWS CloudWatch.
![CloudWatch](Cloud%20Watch.png)

## 📂 Project Files

### Create S3 Script
[View create_s3.py](create_s3.py)

### Lambda Function Script
[View lambda_function.py](lambda_function.py)

### Requirements File
[View requirements.txt](requirements.txt)
