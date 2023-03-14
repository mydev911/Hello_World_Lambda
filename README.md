# Hello_World_Lambda

## S3 bucket policy get and put object
```
{
    "Version": "2012-10-17",
    "Id": "Policy1678745606014",
    "Statement": [
        {
            "Sid": "Stmt1678745602854",
            "Effect": "Allow",
            "Principal": "*",
            "Action": [
                "s3:GetObject",
                "s3:PutObject"
            ],
            "Resource": "arn:aws:s3:::hellloworld21/*"
        }
    ]
}
```
