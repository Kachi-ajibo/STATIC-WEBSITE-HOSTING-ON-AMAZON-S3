# STATIC-WEBSITE-HOSTING-ON-AMAZON-S3
In this project, I built and deployed a static website for a café using Amazon S3, applying real-world security, cost optimization, and disaster recovery best practices.
The goal was not just to host a website, but to understand how AWS services work together to deliver a secure, cost-effective, and highly durable static web solution. Through this hands-on lab, I gained practical experience with S3 static website hosting, data protection, lifecycle management, and cross-region replication.
This project demonstrates my ability to design simple cloud architectures while considering availability, durability, security, and cost efficiency.

 **Steps Taken**
 
1️⃣ **Created an S3 Bucket and Enabled Static Website Hosting**
Created an Amazon S3 bucket.
Enabled static website hosting on the bucket.
Uploaded the website files (HTML and images).
Accessed the S3 website endpoint to confirm the site was live.

2️⃣**Configured Public Access with a Bucket Policy**
Added a bucket policy to allow public read access.
Ensured users could view the website without manually setting permissions on each object.
Maintained security by restricting write access.

3️⃣ **Enabled Versioning for Data Protection**
Enabled S3 Versioning to protect against accidental deletion or overwriting.
Tested versioning by uploading updated files and confirming older versions were retained.
This ensured quick recovery from unintended changes.

4️⃣** Implemented Lifecycle Policies for Cost Optimization**
To manage storage cost effectively:
Moved older object versions to S3 Standard–Infrequent Access (IA) after 30 days.
Automatically deleted previous versions after 365 days.
Balanced durability and availability while minimizing long-term storage cost.

5️⃣** Enabled Cross-Region Replication for Disaster Recovery**
Created a secondary S3 bucket in a different AWS region.
Enabled cross-region replication to automatically copy all objects.
Improved durability and ensured data availability even if one region experiences issues.

 **Key Skills Demonstrated**
 
Static website hosting with Amazon S3
Secure public access using bucket policies
Data protection with S3 versioning
Cost optimization using lifecycle rules
Disaster recovery through cross-region replication
