Static Website Deployment with AWS S3, CloudFront, and GitHub Actions

Project Overview

This repository contains the HTML and CSS files for a static website hosted on Amazon S3 and distributed using AWS CloudFront. The website design is responsive and built with modern HTML and CSS practices. GitHub Actions are used to automate the deployment process, ensuring that any changes pushed to the repository are 
automatically reflected on the live site.

Features

Static Hosting: The website is stored in an Amazon S3 bucket, providing a cost-effective and scalable solution for static content.
Content Delivery Network (CDN): AWS CloudFront is configured to distribute the website globally, improving load times and reliability.
Automated Deployment: GitHub Actions are set up to automatically deploy updates to the S3 bucket whenever changes are pushed to the main branch.

Project Structure

index.html: The main HTML file for the website.
style.css: The stylesheet for the website, defining its look and feel.
.github/workflows/deployToS3.yml: The GitHub Actions workflow file that handles the automated deployment to AWS S3 and CloudFront.

Contact

For any questions or issues, please reach out to jeffrey.k.apau@gmail.com.

