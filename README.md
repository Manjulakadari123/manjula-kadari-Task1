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

Implementation Steps
1. Create S3 Bucket

Created an S3 bucket to store the static website files.

2. Upload Website Files

Uploaded the following files to the S3 bucket:

index.html

3. Enable Static Website Hosting

Enabled Static Website Hosting in the S3 bucket and configured:

Index document: index.html
4. Configure Public Access

Configured the required S3 bucket permissions to allow users to access the website publicly.

5. Deploy Website

After uploading the files and configuring the bucket, the website became accessible through the S3 website endpoint.

GitHub

The source code is maintained in this GitHub repository.

Outcome

Successfully deployed a static portfolio website using AWS S3 without using a traditional web server.

The website can be accessed through the S3 static website URL.

Skills Demonstrated
AWS S3
Cloud Storage
Static Website Hosting
IAM / Bucket Policies
HTML & CSS
Git
GitHub
Cloud Deployment
