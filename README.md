# Simple tutorial to host a static website on Amazon S3 Bucket
Here's my sample hosted site - http://project-s3-kunal.com.s3-website.ap-south-1.amazonaws.com/

Let's Begin..!\
Step 1 - Create a S3 Bucket with a globally unique name and you can also select your region.

![MicrosoftTeams-image (6)](https://github.com/Kunaldahat/Website-Hostng-S3-AWS-/assets/96560952/1402ea0b-6577-4ecf-83b3-c1d92778c29e)

![MicrosoftTeams-image (9)](https://github.com/Kunaldahat/Website-Hostng-S3-AWS-/assets/96560952/ec5ccd80-c275-4a78-bde5-d488d78fdc01)


Deselect "Block all public access" and click on Create bucket.

![MicrosoftTeams-image (8)](https://github.com/Kunaldahat/Website-Hostng-S3-AWS-/assets/96560952/960268c2-3a54-49e4-afba-9cf1cff90393)


Step 2 - After creating the bucket, upload all your Website Content to it.

![MicrosoftTeams-image (10)](https://github.com/Kunaldahat/Website-Hostng-S3-AWS-/assets/96560952/337de439-221a-44a5-b1cc-90906ece353b)


Step 3 - Configure Bucket Policy under "Permission" tab click on "Bucket Policy" and Paste the following policy, replacing "your-bucket-name" with your actual bucket name.\
(This policy is used to grant read access to all users, allowing them to retrieve the website files from the S3 bucket. Without this policy, the website files may not be accessible to the public, resulting in an inaccessible website.)

![MicrosoftTeams-image (11)](https://github.com/Kunaldahat/Website-Hostng-S3-AWS-/assets/96560952/368dbb04-6d1c-43d9-b95e-5e969969dafd)


Step 4 - Go to "Properties" tab, scroll to the bottom to "Static Website hosting" and Enable it. Enter you website html file name (eg.,"index.html") in the index document field.

![MicrosoftTeams-image (12)](https://github.com/Kunaldahat/Website-Hostng-S3-AWS-/assets/96560952/f423c000-0f1c-4cc0-9782-dc1ccc2a7c29)

Step 5 - You will find link to your website under "Static Website hosting" tab.

![MicrosoftTeams-image (13)](https://github.com/Kunaldahat/Website-Hostng-S3-AWS-/assets/96560952/34b464ee-642d-4c2e-a1e4-b707b6250fce)

# That's it!!!  Your static website is now hosted on Amazon S3 and accessible Publicly.
