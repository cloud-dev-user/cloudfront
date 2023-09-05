# cloudfront
# This Repository contents are created from reference url :  https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/GettingStarted.SimpleDistribution.html

1. Open AWS Console and Create S3 bucket name " my-sample-bucket"   # make sure name of s3 bucket is unique 
2. Complete the Object Ownership section as follows:
       Choose ACLs enabled
       In Object Ownership, choose Bucket owner preferred.
       Unselect Block all public access.
       In the warning section, select the check box for I acknowledge that the current settings might result in this bucket and the objects within becoming public.
3. Uplaod image in S3 bucket
4. Go to Amazon cloudfront page in aws console and create cloudfront distribution
      Follow the table shown in https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/GettingStartedCreateDistribution.html
5. Access the content os s3 bucket


