# AWS-cloudtrail-analyser-
This repository includes the following files:

cloudformation.yaml: This file contains the CloudFormation template responsible for deploying the stack of resources.
cloudtrail_analyzer.py: This file contains the source code for the Lambda function used to analyze CloudTrail logs.
Please note that this code is provided for reference purposes only, as it will also be available in the inline editor within the Lambda console after the CloudFormation stack is deployed.
if you want to delete everything at the end then there is a file to help you do it effectively as If you attempt to delete the stack from the console directly, it will fail due to the presence of content in the created S3 buckets. Therefore, it is recommended to use this script for a smooth teardown process.
teardown.sh: This file is a Bash script designed to delete the CloudFormation stack of resources. It handles the process gracefully by addressing the issue of S3 buckets associated with the stack having contents that must be deleted before the stack can be removed.
