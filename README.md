# manjula-kadari-Task1

# Static Portfolio Website Using AWS S3

## Project Overview

This project demonstrates how to host a static website using **AWS S3 Cloud Storage** without provisioning or managing a server.

The website contains a resume/portfolio created using HTML and CSS, along with project images.

## Technologies Used

- AWS S3
- HTML
- Git
- GitHub

## Project Structure

```text
static-website/
├── index.html
├── style.css
├── images/
│   ├── profile.jpg
│   ├── project1.png
│   └── project2.png
└── README.md

Implementation steps
1. Create S3 Bucket

Created an S3 bucket to store the static website files.

<img width="1920" height="1080" alt="Screenshot (55)" src="https://github.com/user-attachments/assets/b1c626e1-a819-44cb-9425-3f8596ce6ce2" />

2. Upload Website Files

Uploaded the following files to the S3 bucket:

index.html
<img width="1920" height="1080" alt="Screenshot (56)" src="https://github.com/user-attachments/assets/2d8c64d0-0c83-4a7b-8704-706f5fbf56cc" />


3. Enable Static Website Hosting

Enabled Static Website Hosting in the S3 bucket and configured:
<img width="1920" height="1080" alt="Screenshot (57)" src="https://github.com/user-attachments/assets/c1812006-3581-443a-b003-e57a0004e00f" />

4. Configure Public Access

Configured the required S3 bucket permissions to allow users to access the website publicly.

<img width="1920" height="1080" alt="Screenshot (58)" src="https://github.com/user-attachments/assets/df965ac4-0846-49a1-bc0a-8047d2b354e1" />

5. Deploy Website

After uploading the files and configuring the bucket, the website became accessible through the S3 website endpoint.

<img width="1920" height="1080" alt="Screenshot (57)" src="https://github.com/user-attachments/assets/26ebd1ad-a82f-4e00-940b-ccb8d595002a" />

GitHub

The source code, CSS files, and project images are maintained in this GitHub repository.
http://github.com/Manjulakadari123/manjula-kadari-Task1

Outcome

Successfully deployed a static portfolio website using AWS S3 without using a traditional web server.

The website can be accessed through the S3 static website URL.
http://manjula-portfolio.s3-website-us-east-1.amazonaws.com


<img width="1920" height="1080" alt="Screenshot (59)" src="https://github.com/user-attachments/assets/9f4d5a84-fae5-4ae6-a12d-bd7f8fc221cd" />

Skills Demonstrated
AWS S3
Cloud Storage
Static Website Hosting
IAM / Bucket Policies
HTML & CSS
Git
GitHub
Cloud Deployment





