# Part 4 - Configure S3 Bucket

## With AWS Management Console

- Go to the `Properties` tab and then scroll down to edit the `Static website hosting` section.
![S3 Static Site - Step 1](https://github.com/kffod/AWS-S3-BUCKET-CLOUDPROJECT/blob/499a258fd73c0950d893fffd4dabba62a56856a2/Step4-Config%20Bucket%20Permission/propstatic.png)

- Click on the "Edit" button to see the Edit static website hosting screen.

- Now, **enable** the Static website hosting, and provide the default home page (`index.html`) and error page for your website (optional).

    ![S3 Static Site - Step 1](https://github.com/kffod/AWS-S3-BUCKET-CLOUDPROJECT/blob/499a258fd73c0950d893fffd4dabba62a56856a2/Step4-Config%20Bucket%20Permission/static2.png)
   ![S3 Static Site - Step 1](https://github.com/kffod/AWS-S3-BUCKET-CLOUDPROJECT/blob/499a258fd73c0950d893fffd4dabba62a56856a2/Step4-Config%20Bucket%20Permission/propen.png)

_Did you notice that enabling the static website hosting requires you to make your bucket public?_

_In the snapshot above, it says "**For your customers to access the content at the website endpoint, you must make all your content publicly readable.**"_

For both "Index document" and "Error document", enter "index.html" and click "Save".

After successfully saving the settings, check the Static website hosting section again under the Properties tab. You must now be able to view the website endpoint as shown below=
![S3 Static Site - Step 1](https://github.com/kffod/AWS-S3-BUCKET-CLOUDPROJECT/blob/499a258fd73c0950d893fffd4dabba62a56856a2/Step4-Config%20Bucket%20Permission/statcompleted.png)
