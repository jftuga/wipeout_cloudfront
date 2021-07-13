# wipeout_cloudfront
Disable and then delete CloudFront Distributions and OAIs

## Usage
```
wipeout_cloudfront
Disable and then delete AWS CloudFront Distributions and associated OAIs

Set the AWS_PROFILE environment variable to use a different profile from the AWS credential file

Usage:
  wipeout_cloudfront [command]

Available Commands:
  completion  generate the autocompletion script for the specified shell
  delete      Delete a CloudFront Distribution
  deleteOAI   Delete CloudFront Origin Access Identifier (OAI)
  disable     Disable a CloudFront Distribution
  help        Help about any command
  list        List distributions and their OAIs
  listOAI     List CloudFront Origin Access Identities (OAIs)
  s3check     Search for OAI in S3 bucket permissions
```
