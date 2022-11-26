# udagram

## AWS services used
 - RDS for Database `udagram.c5i71rz4edej.us-east-1.rds.amazonaws.com`
 - [S3 buckets to upload the frontend](http://mybucket22888866.s3-website-us-east-1.amazonaws.com/)
 - [EB to host the nodejs backend](http://udagramapi-env-1.eba-nex22up2.us-east-1.elasticbeanstalk.com/)


## Dependencies

```
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```

## Pipeline
![Screenshot](https://github.com/Ibrahimzn/finalproject/blob/master/docs/digrams/pipelinedigram.png?raw=true)

## Infrastructure description
![Screenshot](https://github.com/Ibrahimzn/finalproject/blob/master/docs/digrams/AWSservicesusedforhostingdigram.png?raw=true)