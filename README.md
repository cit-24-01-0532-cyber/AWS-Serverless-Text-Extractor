
# 🛡️ Smart Document Parser (AWS Textract)

An AI-powered serverless application that extracts text from images and PDFs automatically using Amazon Textract.

## 🚀 Overview
This project automates the process of OCR (Optical Character Recognition). When a document is uploaded to an S3 bucket, an AWS Lambda function is triggered to analyze the document using AI and save the extracted text into another S3 bucket.

## 🏗️ Architecture
1. **Source S3 Bucket**: User uploads an image or PDF.
2. **S3 Event Trigger**: Notifies Lambda upon upload.
3. **AWS Lambda (Python)**: Orchestrates the process.
4. **Amazon Textract**: Uses Machine Learning to read and extract text from the document.
5. **Destination S3 Bucket**: Stores the final `.txt` file with extracted data.



## 🛠️ Tech Stack
- **AWS Services**: S3, Lambda, Textract, IAM
- **Language**: Python 3.12 (Boto3 SDK)

## 📸 Screenshots
 []
 []
