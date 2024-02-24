# Creating Your AWS S3 Bucket

## Using AWS Management Console

1. Navigate to the AWS Management Console and select `S3` > `Buckets` > `Create bucket`.

2. **General configuration:**
   - Enter a unique "Bucket name".
   - Choose a region of your preference.

   _Note_: Ensure that the bucket name is globally unique. Consider a naming convention like `my-website-bucket-123456789123`, replacing **123456789123** with your **12-digit AWS account ID**.

   [Create S3 - Step 1](https://github.com/kffod/AWS-S3-BUCKET-CLOUDPROJECT/blob/e992f7406556f60c21dfa4eef58d45f84abf59b4/Step1-Create%20S3%20Bucket/createings.png)

3. In the Bucket settings for Block Public Access section, **uncheck** "Block all public access" to allow public access to the bucket objects via the S3 object URL.

   _Note_: Enabling public access is necessary for hosting a static website, as the content needs to be publicly readable.

   [Create S3 - Step 2](https://github.com/kffod/AWS-S3-BUCKET-CLOUDPROJECT/blob/eb21bde813ad09f374e01fa2cbf4336c9c300923/Step1-Create%20S3%20Bucket/s3create.png)

4. Click "Next" and then "Create bucket".

5. Once the bucket is created, click on its name to open the contents.

   [Created S3 Bucket](https://github.com/kffod/AWS-S3-BUCKET-CLOUDPROJECT/blob/eb21bde813ad09f374e01fa2cbf4336c9c300923/Step1-Create%20S3%20Bucket/s3created.png)
