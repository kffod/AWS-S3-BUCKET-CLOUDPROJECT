# Deploying Your Website with AWS

## Introduction
Welcome to the cloud adventure! This project is all about taking your static website to new heights on Amazon Web Services (AWS). Buckle up as we embark on a journey to set up your site in the digital skies.

### Project Goals
1. Create a cozy spot for your website on an S3 bucket.
2. Boost content delivery speed with the magical CloudFront, ensuring a seamless user experience.
3. Learn how to delete your S3 bucket when needed.

## Adventure Plan

### 1. Create Your AWS Campsite
[Create Bucket](https://github.com/kffod/AWS-S3-BUCKET-CLOUDPROJECT/tree/a3450c8fd69987cc016c880ebd3e9693799a97a6/Step1-Create%20S3%20Bucket)
[Upload Files](https://github.com/kffod/AWS-S3-BUCKET-CLOUDPROJECT/tree/a3450c8fd69987cc016c880ebd3e9693799a97a6/Step2-upload%20files%20S3)
- Start by creating a public S3 bucket, your digital camping ground.
- Upload your website files into the bucket, like setting up your tent.

### 2. Secure Your Campsite with IAM Rangers
[Secure Bucket](https://github.com/kffod/AWS-S3-BUCKET-CLOUDPROJECT/tree/a3450c8fd69987cc016c880ebd3e9693799a97a6/Step3-Secure%20S3%20Bucket)
[Config Policies](https://github.com/kffod/AWS-S3-BUCKET-CLOUDPROJECT/tree/a3450c8fd69987cc016c880ebd3e9693799a97a6/Step4-Config%20Bucket%20Permission)
- Configure the S3 bucket for secure website hosting.
- Meet the IAM (Identity and Access Management) rangers to control access.

### 3. Light Up the Sky with CloudFront Fireworks
[Config CloudFront](https://github.com/kffod/AWS-S3-BUCKET-CLOUDPROJECT/tree/a3450c8fd69987cc016c880ebd3e9693799a97a6/Step5-Create%20%26%20Config%20Cloudfront)
- Enter CloudFront, the firework show of AWS.
- Create a CloudFront distribution, connecting it to your S3 bucket – the grand finale.

### 4. Enjoy the Starry Night at Your CloudFront Campsite
[View Endpoint](https://github.com/kffod/AWS-S3-BUCKET-CLOUDPROJECT/tree/a3450c8fd69987cc016c880ebd3e9693799a97a6/Step6-Access%20Endpoint)
- Once CloudFront works its magic, get a unique CloudFront endpoint.
- Open your web browser like a virtual telescope and behold your website shining in the digital sky.

## Deleting Your AWS Campsite
[Delete S3](https://github.com/kffod/AWS-S3-BUCKET-CLOUDPROJECT/tree/75006e3319b0f53a59943b0b0c483b1ca7b8bf02/Step7-Delete%20S3%20Bucket)

### 1. Safely Pack Up Your Tent
- Before deleting, make sure your website files are safely backed up.
- Confirm that you no longer need the S3 bucket.

### 2. Delete Your AWS Campsite
- Head to the AWS S3 service.
- Locate your bucket and choose to delete it.
- Confirm the deletion – your digital campsite will be cleared.

## Friendly Reminders
- Static website hosting needs a public S3 bucket, but CloudFront can dance with both public and private buckets.

## Before You Start Your Adventure
- Ensure your AWS account is ready.
- Download and unzip the starter code provided.

## Your Steps in the Cloud

### 1. Pitch Your AWS Tent
- Log in to the AWS Console.
- Navigate to the S3 service and create a public bucket.
- Upload your website files.

### 2. Secure Your Tent and Set Up Camp
- Dive into your S3 bucket settings.
- Configure it for website hosting.
- Use IAM to secure your campsite.

### 3. Let CloudFront Fireworks Begin
- Head to CloudFront in the AWS Console.
- Create a new CloudFront distribution.
- Adjust settings for the perfect firework display.

### 4. Stargaze at Your Website
- Once CloudFront is done, get the unique CloudFront endpoint.
- Open your web browser, enter the endpoint, and marvel at your website in the digital starry night.

Remember, every adventure has its challenges, so ensure you test and tweak to make your website shine brightly in the AWS sky. Happy cloud adventures! 🚀✨
