# Creating Your AWS S3 Bucket

## Using AWS Management Console

1. Navigate to the AWS Management Console and select `S3` > `Buckets` > `Create bucket`.

2. **General configuration:**
   - Enter a unique "Bucket name".
   - Choose a region of your preference.

   _Note_: Ensure that the bucket name is globally unique. Consider a naming convention like `my-website-bucket-123456789123`, replacing **123456789123** with your **12-digit AWS account ID**.

   ![Create S3 - Step 1](Step1-Create S3 Bucket/createings.png)

3. In the Bucket settings for Block Public Access section, **uncheck** "Block all public access" to allow public access to the bucket objects via the S3 object URL.

   _Note_: Enabling public access is necessary for hosting a static website, as the content needs to be publicly readable.

   ![Create S3 - Step 2](Step1-Create%20S3%20Bucket/s3create.png)

4. Click "Next" and then "Create bucket".

5. Once the bucket is created, click on its name to open the contents.

   ![Created S3 Bucket](Step1-Create%20S3%20Bucket/s3created.png)
