# Infrastructure description:

In Amazon Web Services:

1. Create A `Relational Database Service` (RDS) for postgresql database
2. Create A `Amazon Simple Storage Service` (S3) Bucket for your frontend
3. Create An `Elastic Beanstalk` (EC2) for your API

In CircleCI:

You need to login CircleCI using your Github account to then link it to desirable repo then create in your root directory .circleci folder contain config.yaml and set configuration for Your CircleCI such as orbs/jobs/workflow
`Then` push your directory to your repo that is connected to CircleCI
