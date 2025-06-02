# Creating-My-First-AWS-S3-Bucket
Step-by-step project: Launching and configuring my first AWS S3 bucket!

Step 1: Created a S3 bucket within the AWS console
- Navigated to https://aws.amazon.com/ and logged in which brings us to the console.
- Searched S3 in the search bar.
- Select "create bucket."
![image](https://github.com/user-attachments/assets/4e73f7a9-fff6-49fd-ae34-db4805d57453)
![image](https://github.com/user-attachments/assets/53842844-8c54-466b-8344-473100fbd42a)

Step 2: Configuring the bucket
- Navigate to bucket name and give the bucket a unique name. I chose "keshauns-test-aws-bucket."
- Scroll down and uncheck "Block all public access" because it will deny access to the bucket if we try and use the static URL.
- Scroll down further and select "create bucket."
![image](https://github.com/user-attachments/assets/d43e4af3-0212-4ded-b4ae-3dd25e68cd43)
![image](https://github.com/user-attachments/assets/8cdfccbd-941f-4b72-9ef7-36a720ad7098)

Step 3: Creating the webpage for the bucket
- After you create the bucket from the previous step, you'll see the bucket under the "General purpose buckets" list.
- Select your newly created bucket and select "upload" in the top right portion of the screen.
- Here I'm not a coding expert especially with HTML so I referred to chatgpt and chatgpt created a HTML code for my webpage titled "index.html"
- Navigate to the "Permissions" dropdown and chatgpt also gave me a quick bucket policy--it states this bucket is public and users who visit this bucket have read only access and the information from this bucket is being compiled from keshauns-test-aws-bucket.
- Select "upload."
![image](https://github.com/user-attachments/assets/daaf6cba-c82d-4ed9-be0e-a9e727f87d69)
![image](https://github.com/user-attachments/assets/65f03b7b-9794-4875-ac82-08a88714adaf)
![image](https://github.com/user-attachments/assets/5c91b560-3134-4103-9541-b60be79ac322)
![image](https://github.com/user-attachments/assets/bf5d3099-b87b-43f4-bd20-9056985968d3)
![image](https://github.com/user-attachments/assets/ec436b44-1911-4e0e-ae91-fc8ef8a6b854)

Step 4: Hosting the Static Website
- Now that we've created our webpage and configured it in our bucket, we're going to navigate to "Properties" within our bucket.
- Scroll to the bottom where it says "Static website hosting" and select "edit."
- You will select "enable" and then keep "Host a static website" selected and under "Index document" write the name of your webpage HTML code. Mine was "index.html"
- Scroll down and select "Save changes."
![image](https://github.com/user-attachments/assets/e960be8b-29a3-45c5-a6c8-7e2051088fd0)
![image](https://github.com/user-attachments/assets/7714458f-4bfd-409e-9403-b31d203d05df)
![image](https://github.com/user-attachments/assets/d974449c-c4a6-479a-a162-319a38f5b226)

Step 5: Test your bucket
- Now within your bucket, find the "Properties" tab and scroll down to the "Static website hosting" section.
- You should see your static webite endpoint that we just created. Click on it.
- If all works well, your HTML file and the text you chose to write should appear on the screen!
- Congratulation for making this far. You now know how to launch an AWS S3 bucket and host a static webiste!
- Make sure when you're down with this project to delete the contents of the S3 bucket and delete the bucket so you're not charge.
- Thanks for viewing and have a good day!
- ![image](https://github.com/user-attachments/assets/89db4be9-a5cc-4907-ac9a-14667d4eb0ea)
