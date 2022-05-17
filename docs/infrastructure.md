Udagram using the following infrastructure:

AWS RDS Postgres
-----------------
The application uses AWS RDS running Postgres for hosting the database for storing data through the API

Database Endpoint: mydatabase.cv4ybrs0w0zl.us-east-1.rds.amazonaws.com

AWS Elastic Beanstalk
---------------------
The application API is deployed on AWS Elastic Beanstalk. The application is build, archived and uploaded.
Elastic Beanstalk save the built application on S3 bucket and runs the application.
All the environment variable that used by the application is safely added to Elastic Beanstalk environment configuration

EB URL: http://udagram-api-dev.eba-sbqexfm7.us-east-1.elasticbeanstalk.com/

AWS S3 Bucket
-------------
The frontend application is deployed using AWS S3 Bucket and all required assets are uploaded to this S3 bucket.

Bucket URL: http://myudagram.s3-website-us-east-1.amazonaws.com/
