# awseb-imageryapp

1. User uploads an image
2. A message/event is sent over SQS
3. A worker app processes the image and uploads it in to S3 bucket
4. Processed Image can be accessed over internet 
