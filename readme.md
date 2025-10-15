# Static Website Hosting on AWS S3 + CloudFront

## Overview
This project demonstrates hosting a static website using AWS S3 and distributing it globally with CloudFront CDN and HTTPS via AWS Certificate Manager.

## Tools Used
- Amazon S3
- AWS CloudFront
- AWS IAM
- AWS Certificate Manager (ACM)

## Steps Implemented
1. Created an S3 bucket and enabled static website hosting.
2. Configured the bucket policy for public access.
3. Created a CloudFront distribution for content delivery.
4. Implemented HTTPS using an ACM certificate.
5. Verified global access through the CloudFront URL.

## Outcome
Website successfully hosted and globally accessible via CloudFront with secure HTTPS.

## Screenshots
| Description | Screenshot |
|--------------|-------------|
| S3 Bucket Setup | ![S3 Bucket](screenshots/s3-bucket.png) |
| Bucket Policy | ![Bucket Policy](screenshots/bucket-policy.png) |
| CloudFront Distribution | ![CloudFront](screenshots/cloudfront-distribution.png) |
| Final Website Result | ![Website Result](screenshots/website-result.png) |
