# AWS: Cloud Servers

Deploy a Node.js server to AWS EC2.

## Usage

- endpoint:
  - /bikes
  - returns STRING

## Deployed Servers

- GUI Deploy:
  [Link](Aws-web-server-new-env.eba-zwp4xyta.us-west-2.elasticbeanstalk.com)

- CLI Deploy:
  [Link](http://aws-web-server-cli-env.eba-ndjsgukz.us-west-2.elasticbeanstalk.com)

## Process

- GUI Deploy:

  - create aws role (add permissions)
  - create application
  - in servie access, add created role to service role and EC@ instance profile
  - set rest to default
  - wait for deployment

- CLI Deploy

  - create user in aws IAM
  - in terminal:
    - eb configure
    - provided keys
    - default region
    - default output format
    - eb init
    - default region
    - create new application / enter name
    - select YES for using Node.js
    - default platform
    - CodeCommit & SSH both NO
    - eb create 'name goes here'

## Contributors

- Joshua Shea
- Jacob Knaack
