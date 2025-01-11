# Project 9

# AWS-Managed-GenAI-Tools

Exploring Amazon's  Generative AI Managed Services and Tools


As a Generative AI Solutions Consultant, you are to recommend leveraging AWS AI services to a Legal firm to enhance data processing and analysis workflows. Your current project involves utilizing Amazon Comprehend, Translate, Transcribe, and Textract to automate the analysis and transformation of various data types. The goal is to streamline data handling processes for the firm, ensuring accurate insights and efficient translation,transcription and extraction of information from diverse data sources


<img width="715" alt="Screenshot 2025-01-10 at 20 37 46" src="https://github.com/user-attachments/assets/527fe9ab-73af-4d24-a7a4-f20028bddf4a" />



# Activity Guide: Exploring AWS Managed AI Services (Comprehend, Translate, Transcribe, Textract)

1. Set Up the AWS Environment (AWS Management Console)
Create an AWS Account:
Ensure you have an AWS account to access Amazon Comprehend, Translate, Transcribe, and Textract.
Configure IAM Roles:
Create an IAM role with policies granting access to S3, Comprehend, Translate, Transcribe, and Textract services.

2. Create an S3 Bucket for Data Storage (Amazon S3)
Create a Bucket:
Use the S3 Console to create a bucket for storing input and output data.
Configure Bucket Policies:
Set appropriate permissions for the AI services to access the bucket.

3. Analyze Insights in Text with Amazon Comprehend (Amazon Comprehend)
Real-time Text Analysis:
Use the Comprehend Console to analyze customer reviews, extracting:
Sentiment (positive, negative, neutral).
Entities (e.g., names, dates, locations).
Key phrases and syntax.
Review Outputs:
View insights and JSON structures for deeper understanding and integration.

4. Translate Text Between Languages with Amazon Translate (Amazon Translate)
Input Text:
Select the source and target languages (e.g., French to English).
Enter or upload text to translate.
View Results:
Review the translated text and explore JSON samples for debugging or programmatic use.

5. Create an Audio Transcript with Amazon Transcribe (Amazon Transcribe)
Step 1: Create an S3 Bucket and Upload Audio:
Upload a sample audio file (e.g., transcribe-sample.mp3) to your S3 bucket.
Step 2: Create a Transcription Job:
Define the input audio file and output settings using the Transcribe Console.
Run the transcription job and monitor its status.
Step 3: Review Results:
Download and review the transcription results in JSON or plain text format.

6. Extract Text and Structured Data with Amazon Textract (Amazon Textract)
Analyze Documents:
Upload scanned documents (e.g., PDFs) to Textract for processing.
Extract Data:
Extract raw text, form data, and table data.
Highlight bounding box features to locate extracted elements visually.
Download Results:
Save outputs in JSON, CSV, or text format for further analysis.

7. Integrate AI Capabilities into Workflows
Combine Insights:
Use outputs from Comprehend, Translate, Transcribe, and Textract to enrich your data workflows.
Automate with AWS Lambda:
Trigger AI services automatically when files are uploaded to S3.

8. Clean Up Resources
Delete S3 Buckets:
Empty and delete S3 buckets to avoid unnecessary charges.
Remove Transcribe Jobs:
Delete transcription jobs from the Transcribe Console.
Revoke IAM Roles:
Detach or delete IAM roles and permissions used during the lab.
