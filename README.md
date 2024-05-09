
# Hosting A Static HTML Website on S3

This project demonstrates how to host a static HTML website using Amazon S3. The website is a basic HTML site that includes CSS for styling and JavaScript for basic interactions. The goal of this project is to utilize AWS S3 for simple and scalable web hosting.

## Features
- Amazon S3: Utilizes S3 for storing and delivering the web content.
- Public Access: Configures the S3 bucket to enable public access, making the website accessible to anyone on the internet.
- Static Website Hosting: Uses the static website hosting feature of S3, which allows the bucket to act like a basic web server.


## Technologies Used
- AWS S3
- AWS CloudShell
- HTML
- CSS
- JavaScript


## Setup and Deployment
- Step 1: Create the S3 Bucket
Using AWS CloudShell, execute the command aws s3 mb s3://your-bucket-name to create a new S3 bucket. Ensure that the bucket name is unique and follows AWS naming conventions.

- Step 2: Configure Bucket Permissions
Navigate to the Permissions tab of your bucket. Edit the Block public access (bucket settings) by unchecking “Block all public access.” Save the changes and confirm to enable public access.

- Step 3: Update the Bucket Policy
Still under the Permissions tab, add the policy code from the Bucket_policy_code.md file. This code configures the necessary permissions to allow public access to your static website.

- Step 4: Upload Website Files
Upload all necessary website files and folders into your S3 bucket. Ensure that the file structure in the bucket reflects that of your local environment to prevent any missing file issues.

- Step 5: Enable Static Website Hosting
Go to the Properties tab of your bucket and locate the “Static website hosting” section. Enable Static Website Hosting, enter “index.html” in the Index document field, and save your changes.

- Step 6: Access the Website
Find the generated URL for your static website in the Static website hosting section on the Properties tab. This URL can be used to access your site directly via the web.


## Accessing the Website
The website can be accessed through the S3 endpoint URL provided in the bucket's static website hosting configuration.


## Screenshots

![App Screenshot](https://snipboard.io/mZk4sc.jpg)
![App Screenshot](https://snipboard.io/XNOGa6.jpg)
![App Screenshot](https://snipboard.io/8opRic.jpg)

## 🔗 Links

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/samuel-tettey-fio/)

## Authors

- [@bigsam233](https://github.com/bigsam233)

