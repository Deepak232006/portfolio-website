# Portfolio Website Hosting on AWS S3 & CloudFront

## Project Overview

This project demonstrates the deployment of a static portfolio website using Amazon Web Services (AWS). The website is built with HTML and CSS, stored in an Amazon S3 bucket, and delivered globally through Amazon CloudFront for improved performance and availability.

---

## Technologies Used

* HTML5
* CSS3
* Git & GitHub
* Amazon S3
* Amazon CloudFront

---

## Project Files

```
Portfolio-Website/
│── index.html
│── styles.css
│── README.md
│── images/
```

---

## Deployment Steps

### Step 1: Create the Website

* Developed a responsive portfolio website using HTML and CSS.
* Added images and styling for the portfolio.

### Step 2: Upload to GitHub

* Created a GitHub repository.
* Uploaded all project files.
* Committed and pushed the project to the repository.

### Step 3: Create an Amazon S3 Bucket

* Created a new S3 bucket.
* Uploaded all website files.
* Configured bucket permissions for static website hosting.

### Step 4: Configure Bucket Policy

* Added a bucket policy to allow public read access to website files.

### Step 5: Create CloudFront Distribution

* Created a CloudFront distribution using the S3 bucket as the origin.
* Configured `index.html` as the default root object.
* Waited for deployment to complete.

### Step 6: Test the Website

* Opened the CloudFront URL in a web browser.
* Verified that all pages, images, and styles loaded successfully.

---

## GitHub Repository

GitHub Repository:
https://github.com/YourUsername/YourRepository

---

## Live Website

CloudFront URL:
https://your-cloudfront-domain.cloudfront.net

---

## Screenshots Included

* GitHub Repository
* Amazon S3 Bucket
* S3 Bucket Policy
* CloudFront Distribution
* Live Website

---

## Outcome

The portfolio website was successfully hosted on AWS using Amazon S3 and Amazon CloudFront. The website is accessible through the CloudFront URL and demonstrates the use of cloud storage and content delivery services for static website hosting.

---

## Author

**Deepak Prabagaran**

Cloud Computing & DevOps – Task 1
