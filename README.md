# AWS Static Website with S3 and CloudFront

This is my first cloud project 🚀  
I created a simple static website hosted on **Amazon S3** and distributed with **Amazon CloudFront** to enable HTTPS and caching.

## 🔹 Project Overview
- **Amazon S3** → used to host a static `index.html` file.
- **Bucket Policy** → configured for public read access.
- **Amazon CloudFront** → added as CDN for performance and HTTPS support.
- **Default Root Object** → set to `index.html` so the site loads correctly from the root domain.

## 🔹 Live Demo
🌍 Website available at: [https://d2l3f9671h40lr.cloudfront.net](https://d2l3f9671h40lr.cloudfront.net)

## 🔹 Files
- `index.html` → main webpage with a simple "Hello World" message.

## 🔹 Next Steps
- Add CSS/JS to improve the page.
- Connect a custom domain with Route 53.
- Experiment with versioning and logging in S3.
