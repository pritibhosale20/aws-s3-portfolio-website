## aws-s3-portfolio-website
This is my personal portfolio website, which I **deployed on AWS** using **S3, CloudFront, and Route 53**
(Note: The website is currently not live, as the S3 bucket was deleted to avoid charges)

## 🚀 Technologies Used  
- **Frontend:** HTML, CSS  
- **Hosting:** AWS S3 (Static Website)  
- **CDN:** AWS CloudFront  
- **Domain Management:** AWS Route 53

## 🌍 Domain Setup with Route 53  
- Registered/Managed a domain in **Route 53**.  
- Created a **custom domain name** (yourportfolio.run.place)
- Configured **DNS records** (A, CNAME) to point to the CloudFront distribution.

## 🛠 How I Deployed It  
1. Uploaded website files to an S3 bucket  
2. Enabled static website hosting on S3
3. Created a CloudFront distribution to serve content efficiently 
4. Configured domain settings to map my domain to CloudFront

## 🎯 What I Learned  
- Hosting static websites on AWS S3  
- Configuring CloudFront for performance and security 
- Managing domains using Route 53.

## 🔍 How to View Locally  
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/my-portfolio.git

2. Open index.html in a browser   
