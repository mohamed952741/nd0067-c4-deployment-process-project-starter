# CircleCI:

1. The core orbs: `node`,`eb cli` and `AWS CLI`
2. Jobs:
   - Build
    - Start by creating a docker image
    - install node
    - check the entire code
    - Install all the front-end dependencies
    - Install all the back-end dependencies
    - Linting the front-end code to make sure code is formatted correctly
    - Build the Front-end
    - Build the Back-end
  - Deploy:
    - Create a docker image
    - install node, eb and aws-cli
    - check the entire code
    - Deploy the front-end code to a S3 bucket
    - Deploy back-end code to Elastic Beanstalk

3. Workflow:
   Start by building project, then wait for approval, then when it is approved start deploying project to AWS