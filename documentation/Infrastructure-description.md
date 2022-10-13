# Infrastructure description:

## In Amazon Web Services:

1. Create A `Relational Database Service` (RDS) for A postgresql database
2. Create A `Amazon Simple Storage Service` (S3) Bucket for your front-end APP
3. Create An `Elastic Beanstalk` (EC2) to connect RDS and S3 

## CircleCI:
You need to login CircleCI using your Github account to then link it to desired repo then in your root create a directory .circleci containing config.yaml and then set your configuration for your CircleCI such that orbs/jobs/workflow, Then push the directory to your repo that is connected to CircleCI.
