# Website
Repository for website work. This website is a static website hosted on Route 53 in AWS. It is run through Cloudfront to access the s3 bucket for forwarding to https from http. The contact form page has an api call to a lambda function in order to forward contact information to an email address without using a database.

Recent updates: I added YAML to automate updates to AWS s3 buckets for distribution.

I added a blog section. It's dirty, but it works! I'll clean it up in time.
