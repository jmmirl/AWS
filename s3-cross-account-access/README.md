# HowTo Cross account S3 bucket access with KMS 

We need two AWS Accounts for this test.
**Account A** is where the bucket and KMS key will live, and **Account B** is the destination account that is looking for access to the contents of the S3 bucket in Account A

## Step1
Create S3 bucket in the source account A
Create KMS Key for encrypting data in the S3 bucket

## Step2 
Use the sample **bucket-polcy.json** to update your S3 bucket policy to allow the root ARN of your account B to have access to the S3 bucket
update the ARN of the KMS key you created in the previous step.
Save this bucket policy.


