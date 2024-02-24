# Part 5 - Distribute Website via CloudFront

## With AWS Management Console

- On AWS Management Console navigate to `S3` > `CloudFront` > `Create Distribution`
- ![Find Cloud Front](https://github.com/kffod/AWS-S3-BUCKET-CLOUDPROJECT/blob/7bdefebc80c5b946dab3953914306c04cfcb4498/Step5-Create%20%26%20Config%20Cloudfront/cloudfront.png)

  Use the following details to create a distribution:

  | Field                         | Value                                                                                                                                                                 |
  | ----------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
  | Origin > Origin domain        | \* **Don't select the bucket from the dropdown list**<br><br> Paste the Static website hosting endpoint of the form **<bucket-name>.s3-website-region.amazonaws.com** |
  | Origin > Enable Origin Shield | No                                                                                                                                                                    |

  ![Create Distribution - Step 1](https://github.com/kffod/AWS-S3-BUCKET-CLOUDPROJECT/blob/7bdefebc80c5b946dab3953914306c04cfcb4498/Step5-Create%20%26%20Config%20Cloudfront/cfdist.png)

- Leave the defaults for the rest of the options, and click "Create Distribution"
  ![Create Dist step 2](https://github.com/kffod/AWS-S3-BUCKET-CLOUDPROJECT/blob/7bdefebc80c5b946dab3953914306c04cfcb4498/Step5-Create%20%26%20Config%20Cloudfront/cfdist.png)

- _Note_: It may take up to 10 minutes for the CloudFront Distribution to be created
  ![Create Dist step 3](https://github.com/kffod/AWS-S3-BUCKET-CLOUDPROJECT/blob/7bdefebc80c5b946dab3953914306c04cfcb4498/Step5-Create%20%26%20Config%20Cloudfront/cfd2.png)
  ![step 4](https://github.com/kffod/AWS-S3-BUCKET-CLOUDPROJECT/blob/7bdefebc80c5b946dab3953914306c04cfcb4498/Step5-Create%20%26%20Config%20Cloudfront/cfd.png)
- Once the status of your distribution changes from "**In Progress**" to "**Deployed**", copy the **endpoint URL for your CloudFront distribution** found in the "**Domain Name**" column
  ![create step 5](https://github.com/kffod/AWS-S3-BUCKET-CLOUDPROJECT/blob/7bdefebc80c5b946dab3953914306c04cfcb4498/Step5-Create%20%26%20Config%20Cloudfront/cfd.png)
  _Note_ - Remember, as soon as your CloudFront distribution is Deployed, it attaches to S3 and starts caching the S3 pages. CloudFront may take 10-30 minutes (or more) to cache the S3 page. Once the caching is complete, the CloudFront domain name URL will stop redirecting to the S3 object URL

- In this example, the Domain Name value is `d826ux1r5av67.cloudfront.net`, but yours will be different.

  ![New Distribution](https://github.com/kffod/AWS-S3-BUCKET-CLOUDPROJECT/blob/7bdefebc80c5b946dab3953914306c04cfcb4498/Step5-Create%20%26%20Config%20Cloudfront/cfdash.png)
