# AWS Static Website Hosting POC

POC-23

## Services Used
- Amazon S3
- Amazon CloudFront
- GitHub
- AWS CodePipeline

## Objective
Host a static HTML/CSS website using Amazon S3 and deliver content through CloudFront CDN.

## Architecture

GitHub
 ↓
CodePipeline
 ↓
S3 Bucket
 ↓
CloudFront
 ↓
Users
