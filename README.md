# Simple tutorial to host a static website on Amazon S3 Bucket
Here's my sample hosted site - http://project-s3-kunal.com.s3-website.ap-south-1.amazonaws.com/

Let's Begin..!
Step 1 - Create a S3 Bucket with a globally unique name and you can also select your region.

![image](https://github.com/Kunaldahat/Website-Hostng-S3-AWS-/assets/96560952/4551e50e-159f-4795-afd5-be6767f3be2b)
![MicrosoftTeams-image (6)](https://github.com/Kunaldahat/Website-Hostng-S3-AWS-/assets/96560952/4caad76e-d9ef-405e-86eb-b95d9caca13f)

![image](https://github.com/Kunaldahat/Website-Hostng-S3-AWS-/assets/96560952/f9f3f278-2089-4397-b7b9-9f553fbb84a8)

Deselect "Block all public access" and click on Create bucket.

![image](https://github.com/Kunaldahat/Website-Hostng-S3-AWS-/assets/96560952/f5c62ab0-2548-4990-944c-496e2aee5ea0)


Step 2 - After creating Upload all your Website Content to the bucket.

![image](https://github.com/Kunaldahat/Website-Hostng-S3-AWS-/assets/96560952/9b7bef3b-0d20-4f0a-b954-3007666dee44)

Step 3 - Configure Bucket Policy under "Permission" tab click on "Bucket Policy" and Paste the following policy, replacing "your-bucket-name" with your actual bucket name.
(This policy is used to grant read access to all users, allowing them to retrieve the website files from the S3 bucket. Without this policy, the website files may not be accessible to the public, resulting in an inaccessible website.)

![image](https://github.com/Kunaldahat/Website-Hostng-S3-AWS-/assets/96560952/1b8f05c9-9242-4637-944c-73ec0edea397)

Step 4 - Go to "Properties" tab, scroll to bottom to the "Static Website hosting" and Enable it. Enter you website html file name (eg.,"index.html") in the index document filed.

![image](https://github.com/Kunaldahat/Website-Hostng-S3-AWS-/assets/96560952/3fb86992-02c1-49f9-8c1f-f95d24db8081)

Step 5 - Yo will find link to your website under "Static Website hosting" tab.

![image](https://github.com/Kunaldahat/Website-Hostng-S3-AWS-/assets/96560952/5744bc1e-bfac-4453-87f5-33c65b0e782f)

# That's it!!! Your static website is now hosted on Amazon S3 and accessible Publicly.
