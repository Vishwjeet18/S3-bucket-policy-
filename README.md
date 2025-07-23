# S3-bucket-policy-
S3 bucket policy

{
  "Version": "2012-10-17",
  "Statement": [
    {
    
      "Sid": "PublicReadImage",
      "Effect": "Allow",
      "Principal": "*",
      "Action": "s3:GetObject",
      "Resource": "arn:aws:s3:::mybucketvishwjeetbidkar/*"
    }
  ]
}


