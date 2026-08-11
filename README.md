\# AWS S3 Static Website — Cloud Engineer Portfolio



A professional cloud engineer portfolio website hosted using Amazon S3 Static Website Hosting.



The project demonstrates AWS cloud fundamentals including Amazon S3, IAM, CloudFront, static website hosting, object storage and cloud-based content delivery.



\---



\## 🚀 Live Website



\### Amazon S3 Website



http://siddarth-static-website-2026.s3-website.ap-south-1.amazonaws.com



\### CloudFront



CloudFront distribution will be added after AWS account verification is completed.



\---



\## ☁️ Architecture



The current architecture uses Amazon S3 Static Website Hosting to serve the portfolio website directly to visitors.



!\[AWS S3 Static Website Architecture](architecture-diagram.png)



\### Current Architecture



```text

&#x20;                   User / Browser

&#x20;                        │

&#x20;                        │ HTTP Request

&#x20;                        ▼

&#x20;             ┌──────────────────────┐

&#x20;             │      Amazon S3        │

&#x20;             │  Static Website       │

&#x20;             │      Hosting          │

&#x20;             └──────────┬───────────┘

&#x20;                        │

&#x20;             ┌──────────┼──────────┐

&#x20;             │          │          │

&#x20;             ▼          ▼          ▼

&#x20;         index.html  style.css   images/

