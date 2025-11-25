# AWS

## A Collection of AWS Policies and Controls


(**S3-bucket-with-inteligent-tiering**)[https://github.com/jmmirl/AWS/blob/main/cf-template-S3-bucket-with-inteligent-tiering.yml]

CF Template that does the following  
Prompts for bucket name and region

Creates an S3 bucket in Intelligent-Tiering class (when objects are uploaded with that class)  

Ensures server-side encryption (AES-256) is enabled by default  

Uses AWS-managed SSE-S3 (no keys to manage)  

Includes the 3 Intelligent-Tiering instant-access tiers:  

* Frequent Access  
* Infrequent Access  
* Archive Instant Access  
